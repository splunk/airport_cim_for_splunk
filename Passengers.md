# Passengers CIM

Fields in the CIM are compiled mainly from the ACRIS and IATA standards. A-CDM does not have many suitable conventions for passenger related data. To see more about the data sources used, see the [about](./About.md) page.

| Dataset Name  | Field Name  | Data Type | Description | Examples |
|:--------------|:------------|:----------|:------------|:---------|
| Security      | passengerName | String(<=20)  | Passenger name - Following IATA Passenger Services Resolution Manual format | TUGWELL/KL MR |
| Security | from | String | The departing airport and/or country | Gatwick, London |
| Security | to | String | The arriving airport and/or country | Amsterdam, Schiphol |
| Security | airline | String | The IATA code of the airline, sometimes called "Carrier" | EZY |
| Security | flightNumber | int(4) | The flight number | 1234 |
| Security | FQFC | String | The Fully Qualified Flight Code, a concatenation between airline and flightNumber | EZY1234 |
| Security | seat | String | The seat the passenger will occupy on the flight | 17B |
| Security | passengerGate | String | The public gate the aircraft is departing from | 10A |
| Security | boardTime | int(4) | 4 digit 24hr time format scheduled boarding time of the flight | 0900 |
| Security | BPSOBT | String | The scheduled off block time as printed on the boarding pass. The IATA standards does *not* include the year, so it's better to link the flight from the Airfield dataset to this record if you wish to do year-on-year analysis. %d%b%H%M | 01JAN0900 |
| Security | class | int(1) | The class of travel - refer to [PADIS Codeset 9873](https://github.com/ktugwell/Splunk4Airports/blob/main/lookups/padis_9873.csv) | 1, 2, 3 |
| Security | dateOfIssue | String | The date the boarding pass was issued. %d%b%y | 01JAN21 |


# <a id="Processing"></a>Processing (Beta)

This section mainly relates to X-Ray Machine and Walk-Through Metal-Detector(WTMD) data:

| Dataset Name  | Field Name  | Data Type | Description | Examples |
|:--------------|:------------|:----------|:------------|:---------|
| Security      | WTMDID | int   | The unique ID of the WTMD | 000000 |
| Security | passengerDirection | int(1) | The direction the passenger walks through the WTMD. 1 = Forwards, 0 = Backwards | 0, 1 |
| Security | zoneAlarm | int(20) | A digital representation of the alarming zones for the WTMD. a 0000000000000000000 would be no alarm, a 11111111111111111111 would be every zone alarmed. 5 digits per 4 zones in the following order: Head, Shoulders to Waist, Waist to Knees, Knees to Feet. 00000000001111100000 would typically be an alarm on a large, metallic belt. | 00000000000000001111 (Shoes alarmed) |
| SEcurity | alarm | Boolean | Was the passthrough and alarm | True, False |
| Security | randomAlarm | Boolean | Whether the alarm was randomly generated | True, False |


[Contents](./contents.md)<br />
[Home](./)
