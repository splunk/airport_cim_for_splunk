# Hold Baggage CIM

There is no know universal schema for Hold Baggage, with vendors creating their own data structures. This part of the CIM has been compiled from the most commonly seen fields. For more information about how the baggage CIM was created, see the Baggage section on the [How To](./howto.md) page.

| Dataset Name  | Field Name  | Data Type | Description | Examples |
|:--------------|:------------|:----------|:------------|:---------|
| Baggage | bagTag | int(10) | The unique bag tag number, usually the barcode generated at check-in. IATA Resolution 751 | 0174682930 |
| Baggage | passengerName | String(<=20)  | Passenger name - Following IATA Passenger Services Resolution Manual format | TUGWELL/KL MR |
| Baggage | flightUID | String | The unique identifier for the flight. Allow you to connect Baggage and Airfield Datasets | 6300189 | 
| Baggage | ULDID | String | Unit Load Device. Some larger aircraft only accept bags that have been first loaded into a ULD | ABC12345678 |
|Baggage|SOBT|int(10)|Scheduled Off Block Time - Epoch|0516469200|















[Contents](./contents.md)<br />
[Home](./)
