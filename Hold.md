# Hold Baggage CIM

There is no know universal schema for Hold Baggage, with vendors creating their own data structures. This part of the CIM has been compiled from the most commonly seen fields. For more information about how the baggage CIM was created, see the Baggage section on the [How To](./howto.md) page.

| Dataset Name  | Field Name  | Data Type | Description | Examples |
|:--------------|:------------|:----------|:------------|:---------|
| Baggage | bagTag | int(10) | The unique bag tag number, usually the barcode generated at check-in. IATA Resolution 751 | 0174682930 |
| Baggage | passengerName | String(<=20)  | Passenger name - Following IATA Passenger Services Resolution Manual format | TUGWELL/KL MR |
| Baggage | flightUID | String | The unique identifier for the flight. Allow you to connect Baggage and Airfield Datasets | 6300189 | 
| Baggage | ULDID | String | Unit Load Device. Some larger aircraft only accept bags that have been first loaded into a ULD | ABC12345678 |
|Baggage|SOBT|int(10)|Scheduled Off Block Time - Epoch|0516469200|
|Airfield|FQFC|String|Fully Qualified Flight Code|EZY1234|
|Baggage|messageType|String|If applicable - the type of message being recorded. | BSM, BPM, BUM |
|Baggage|messageAction|String|Is the message new, and update, or a deletion| UPT, NEW, DEL |
|Baggage|level|int|The level in which the bag has been seen. Most airports operate a 5 level system. Some more modern solutions only have 3 levels. Refers to the security level in which the bag was cleared for departure. 1 = Automatic Clearing by Computer Algorithm. 5 = Manual search to be performed by control authorities. | 1,2,3,4,5|
















[Contents](./contents.md)<br />
[Home](./)
