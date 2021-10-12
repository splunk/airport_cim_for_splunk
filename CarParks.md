### Car Parking (Beta)

The fields relating to aspects of passenger car parking accross the airport

Events
| Dataset Name  | Field Name  | Data Type | Description | Examples |
|:--------------|:------------|:----------|:------------|:---------|
|ParkingEvents|eventTime|int(10)|Time the event was generated|0516469200|
|ParkingEvents|vehicleId|String|The unique identifier of the vehicle|ABC123|
|ParkingEvents|eventType|String|Type of gate access or booking|pre-book,rollup,valet,taxi|
|ParkingEvents|eventOutcome|String|Outcome of the interaction and eventType|success,fail|
|ParkingEvents|gateId|String|The unique identifier of the gate device|short_stay_1|
|ParkingEvents|gateLocation|String|Physical location of gate device|Terminal 1 Short Stay|
|ParkingEvents|gateType|String|Type of gate device usage|entrance,exit,valet| 

Faults
| Dataset Name  | Field Name  | Data Type | Description | Examples |
|:--------------|:------------|:----------|:------------|:---------|
|ParkingFaults|eventTime|int(10)|Time the event was generated|0516469200|
|ParkingFaults|eventType|String|Type of fault event|motor failure,paper outage|
|ParkingFaults|eventStatus|int(1)|Active status of fault event|1,0|
|ParkingFaults|gateId|String|The unique identifier of the gate device|short_stay_1|
|ParkingFaults|gateLocation|String|Physical location of gate device|Terminal 1 Short Stay|
|ParkingFaults|gateType|String|Type of gate device usage|entrance,exit,valet|




[Contents](./contents.md)<br />
[Home](./)
