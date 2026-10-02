### Aircraft CIM

The fields within this section of the CIM are all related to the specific aircraft of the flight leg. Use this in conjunction with the [Departures](./Departures.md) and [Arrivals](./Arrivals.md) sections of the CIM

| Dataset Name  | Field Name  | Data Type | Description | Examples |
|:--------------|:------------|:----------|:------------|:---------|
| Airfield      | lastUpdated | int(10)   | The time the record was last updated. This should be used as your _time field when indexing your AODB events | 0516469200 |
| Airfield      | flightUID   | String    |A unique identifier for the flight leg | 6300189 |
|Airfield|flightNumber|int(4)|The numerical flight number of the aircraft|1234|
|Airfield|serviceType|String(1)|The IATA service type of the flight. Refer to [serviceTypes](https://github.com/ktugwell/Splunk4Airports/blob/main/lookups/serviceTypes.csv) lookup. | J (Scheduled), C (Charter), P, F, G, D, H, I |
|Airfield|airline|String|The IATA code for the operating airline|EZY, DY, AA|
|Airfield|FQFC|String|Fully Qualified Flight Code|EZY1234|
|Airfield|departureOrArrival|String(1)|Is the aircraft departing or arriving|D, A|
|Airfield|aircraftParkingPosition|String|Gate or hard stand where the aircraft is located|A10|
|Airfield|passengerGate|String|The public gate which the passengers will use to board or disembark.|A10|
|Airfield|remoteOperationalGate|String|An additional location used to transfer passengers to or from a remote parking position.|A10|
|Airfield|runway|String|The runway in use for this aircraft movement|26L|
|Airfield|terminal|String|Terminal where the passengers will be processed.|North, 1, 2, 3|
|Airfield|paxBusInd|Boolean|If true, an airside bus will be used for the passengers.|True, false|
|Airfield|registration|String|The aircraft registration number. The value may be stored with or without a hyphen.|G-XWBD, GDBCH|
|Airfield|agentInfo|String|Identification of the handling agent for the flight leg|MA, ALS|
|Airfield|paxCount|String|The actual count of passengers on the aircraft|100|
|Airfield|callsign|String|The air traffic control callsign for the flight. This can differ from the ICAO flight identifier.|BAW4EP, SHT7R|
|Airfield|ICAOFlightId|String|The ICAO flight identifier|BAW353, AIC161|
|Airfield|ICAOAirline|String(3)|The ICAO code for the operating airline|BAW, AIC, KLM|
|Airfield|flightSuffix|String(1)|The flight number suffix, when present|D, P, F|
|Airfield|aircraftIATAType|String|The IATA aircraft type code|319, 359, 32N|
|Airfield|aircraftICAOType|String|The ICAO aircraft type code|A319, A359, A20N|
|Airfield|flightStatus|String(2)|The operational status code of the flight movement|SH, LB, AB, CX, EX, DV|
|Airfield|cancelled|Boolean|If true, the flight movement is cancelled|true, false|
|Airfield|regulated|Boolean|If true, the flight movement is ATFM regulated|true, false|
|Airfield|diverted|Boolean|If true, the flight has been diverted|true, false|
|Airfield|divertAirport|String(3)|IATA code for the airport the flight was diverted to|STN, FRA, BHX|
|Airfield|airport|String(3)|IATA code for the airport this movement belongs to|LHR|
|Airfield|internationalDomestic|String(1)|Whether the route is international or domestic|I, D|
|Airfield|provisionalStand|String|The stand allocated before it is confirmed|311, 236|
|Airfield|standType|String(1)|Whether the stand is a pier or remote stand. P is pier, R is remote.|P, R|
|Airfield|standHold|Boolean|If true, a stand hold is required|true, false|
|Airfield|gateType|String(1)|The type of passenger gate|S, C, P|
|Airfield|pier|String|The pier code for the passenger gate|2A, 6|
|Airfield|boardingStatus|String(2)|The local boarding status at the gate|BC, GB, PW|
|Airfield|codeShares|String|Multi-value. One value per codeshare flight designator.|AA6705, QR6014|
|Airfield|linkedFlightUID|String|The unique identifier of the linked turnaround flight leg|15694139|
|Airfield|aircraftOnGround|Boolean|If true, the linked aircraft is on the ground|true, false|



[Contents](./contents.md)<br />
[Home](./)
