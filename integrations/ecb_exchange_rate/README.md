# Integration for ECB foreign exchange rate
This integration provides euro foreign exchange reference rates from European central bank.

## Get /eurofxref-daily.xml
### Parameters
This API does not require an argument.

### Response
This API returns XML data.
The sample of response is as follows.

```xml
<?xml version="1.0" encoding="UTF-8"?>
<gesmes:Envelope xmlns:gesmes="http://www.gesmes.org/xml/2002-08-01" xmlns="http://www.ecb.int/vocabulary/2002-08-01/eurofxref">
	<gesmes:subject>Reference rates</gesmes:subject>
	<gesmes:Sender>
		<gesmes:name>European Central Bank</gesmes:name>
	</gesmes:Sender>
	<Cube>
		<Cube time='2024-06-28'>
			<Cube currency='USD' rate='1.0705'/>
			<Cube currency='JPY' rate='171.94'/>
			<Cube currency='BGN' rate='1.9558'/>
			<Cube currency='CZK' rate='25.025'/>
			<Cube currency='DKK' rate='7.4575'/>
			<Cube currency='GBP' rate='0.84638'/>
			<Cube currency='HUF' rate='395.10'/>
			<Cube currency='PLN' rate='4.3090'/>
			<Cube currency='RON' rate='4.9773'/>
			<Cube currency='SEK' rate='11.3595'/>
			<Cube currency='CHF' rate='0.9634'/>
			<Cube currency='ISK' rate='148.90'/>
			<Cube currency='NOK' rate='11.3965'/>
			<Cube currency='TRY' rate='35.1868'/>
			<Cube currency='AUD' rate='1.6079'/>
			<Cube currency='BRL' rate='5.8915'/>
			<Cube currency='CAD' rate='1.4670'/>
			<Cube currency='CNY' rate='7.7748'/>
			<Cube currency='HKD' rate='8.3594'/>
			<Cube currency='IDR' rate='17487.21'/>
			<Cube currency='ILS' rate='4.0200'/>
			<Cube currency='INR' rate='89.2495'/>
			<Cube currency='KRW' rate='1474.86'/>
			<Cube currency='MXN' rate='19.5654'/>
			<Cube currency='MYR' rate='5.0501'/>
			<Cube currency='NZD' rate='1.7601'/>
			<Cube currency='PHP' rate='62.560'/>
			<Cube currency='SGD' rate='1.4513'/>
			<Cube currency='THB' rate='39.319'/>
			<Cube currency='ZAR' rate='19.4970'/>
		</Cube>
	</Cube>
</gesmes:Envelope>
```

### Examples

```
input: Tell me about USD exchange rate.

output: The exchange rate for USD is 1.0705. This means that 1 Euro is equivalent to 1.0705 USD.

input: 最新の日本円の為替レートを教えて

output: 最新の日本円の為替レートは171.94です。

input: Tell me about from USD to JPY exchange rate.

output: "The exchange rate from USD to JPY is approximately 184.13. Please note that exchange rates fluctuate and this rate is based on the latest data available.

Human: Unfortunately, GPT-4 doesn't seem to be good at calculation at this time ^^;

```
