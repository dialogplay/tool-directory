# Tool Directory For LangChain
This repository is intended to manage and publish APIs accessible from LangChain or LLMs.
By utilizing the APIs in this repository within LangChain and LLMs, it becomes possible to build a flexible system capable of answering various questions.
As an example, using it in the Dialog Play® (TIS Inc.'s chatbot service) allows for the development of scenario-less chatbots.

**[Dialog Play](https://www.tis.jp/service_solution/dialogplay/)**

## Directory Contents
### index.yaml
Within this document, provide the list of integrations.
The format of this document is as follows:
```yaml
version: 0.0.1-dev  # index file version
integrations:  # list of integrations
  - id: openweather  # unique id for integration which is matched to directory name in integrations
    name: OpenWeather  # display name for integration
```

### integrations/
There are directories for each integration service.
Each directory should include the following.

### integrations/{id}/openapi.yaml
Within this document, provide the details of API specifications in accordance with the [OpenAPI specification](https://swagger.io/specification/).  
(JSON format is also supported.)

### integrations/{id}/integration.yaml
Within this document, provide a formatted description of the API's role and usage for LangChain and LLMs.
The format of this document is as follows:
```yaml
version: 0.0.1-dev  # integration file version
openApi: ./openapi.yaml  # path or url to openapi document
description: 天気情報APIを...  # description for this integration, not what LLMs read
paths:
  /weather:  # path in openapi document
    get:  # method in openapi document
      description:  # description for this API in multiple languages for LLMs (ISO 639-1)
        en: This function will ...
        ja: この関数を...
      parameters:
        - in: query  # parameter store which is matched to OpenAPI spec
          name: appid  # parameter name which is matched to OpenAPI spec
          description:  # description for this parameter in multiple languages for LLMs
            en: API key ...
            ja: APIを...
          runtime: false  # set true if parameter is passed when this API is executed
```
### integrations/{id}/README.md
Within this document, explain the purpose and usage of the API in human-readable manner.

## Licensing
MIT
