### Aircraft CIM Placeholder

| Dataset Name  | Field Name  | Data Type | Description | Examples | Splunk Eval (If applicable) |
|:--------------|:------------|:----------|:------------|:---------|:----------------------------|
| Airfield      | flightUid   | String    |A unique identifier for the flight leg | 6300189 ||
|Airfield|flightNumber|int(4)|The numerical flight number of the aircraft|1234||
|Airfield|airline|String|The IATA code for the operating airline|EZY, DY, AA||
|Airfield|FQFC|String|Fully Qualified Flight Code|EZY1234|airline. “” .flightNumber|
|Airfield|arrivalOrDeparture|String|Is the aircraft departing or arriving|Departure, Arrival||
|Airfield|aircraftParkingPosition|String|Gate or hard stand where the aircraft is located|A10||
|Airfield|passengerGate|String|The public gate which the passengers will use to board or disembark.|A10||
|Airfield|remoteOperationalGate|String|An additional location used to transfer passengers to or from a remote parking position.|A10||
|Airfield|runway|String|The runway in use for this aircraft movement|26L||
|Airfield|terminal|String|Terminal where the passengers will be processed.|North, 1, 2, 3||
|Airfield|paxBusInd|Boolean|If true, an airside bus will be used for the passengers.|True, false||
|Airfield|registration|String|The aircraft registration number as assigned by the aircraft manufacturer|G-XWBD||
|Airfield|agentInfo|String|Identification of the handling agent for the flight leg|MA, ALS||
|Airfield|paxCount|String|The actual count of passengers on the aircraft|100||



[Back to contents](./contents.md)
