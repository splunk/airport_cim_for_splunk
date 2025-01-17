### De-Icing

The fields relating to the De-Icing of departing aircraft

| Dataset Name | Field Name | Data Type | Description |
|:-------------|:-----------|:----------|:------------|
|Training | firstName | string(15) | Example: Carrol|
|Training | lastName | string(15) | Example: Tucker|
|Training | employeeNum | String(15) | Example: 1859|
|Training | courseName | String(50) | Example: Airside Driving|
|Training | instructor.firstName | String(15) | Example: John|
|Training | instructor.lastName | String(15) | Example: Younger|
|Training | instructor.trainingCerts | String() | Examples: De-icing, Anti-icing (United, American, Delta, Southwest), CRJ, 737-Family, 319, 320, 321. or Cert #|
|Training | takenOn | int(10) | Epoch Time|
|Training | completedOn | int(10) | Epoch Time|
|Training | trainingCerts | String() | Examples: De-icing, Anti-icing (United, American, Delta, Southwest), CRJ, 737-Family, 319, 320, 321. or Cert #|
|Training | expiresOn | int(10) | Epoch Time|
|Airfield | aircraftCondition | String(12) |  Frost,Snow,Heavy Snow,Ice,Acc Ice|
|GroundOps | assetId | String(6) | Truck ID Number, Pumper Number, Tanker Number, Static Boom Number|
|GroundOps | boomOpA.firstName | String(15) | Carrol|
|GroundOps | boomOpA.lastName | String(15) | Tucker|
|GroundOps | boomOpA.employeeNum | String(15) | 1859|
|GroundOps | boomOpA.trainingCerts | String(30) | Examples: De-icing, Anti-icing (United, American, Delta, Southwest), CRJ, 737-Family, 319, 320, 321. or Cert #|
|GroundOps | boomOpB.firstName | String(15) | Karina|
|GroundOps | boomOpB.lastName | String(15) | Coleman|
|GroundOps | boomOpB.employeeNum | String(15) | 721|
|GroundOps | boomOpB.trainingCerts | String() | Examples: De-icing, Anti-icing (United, American), CRJ, 737-Family, 319, 320 or Cert #|
|GroundOps | RecordID | int(12) | 5431|
|GroundOps | assetType | String(6) | Deicer, Boom, Tanker|
|GroundOps | companyName | String(15) | Company Providing Service|
|GroundOps | completedOn | int(10) | Epoch Time|
|Airfield | airline | String(6) | The IATA code for the operating airline|
|GroundOps | deviceId | String | Guid, ex: 5e5fedb6054b18c6887e3e14|
|GroundOps | driver.firstName | String(15) | Brady|
|GroundOps | driver.lastName | String(15) | Andrews|
|GroundOps | driver.employeeNum | String(15) | 2651|
|GroundOps | driver.trainingCerts | String() | Examples: Airside Driving, De-icing (United), CRJ, 737- or Cert #|
|GroundOps | passenger.firstName | String(15) | Jeff|
|GroundOps | passenger.lastName | String(15) | Gordon|
|GroundOps | passenger.employeeNum | String(15) | 302|
|GroundOps | passenger.trainingCerts | String(30) | Example: Airside Driving|
|GroundOps | editedBy.employeeNum | String(15) | 9071|
|GroundOps | flagged | Boolean | True,False|
|Airfield | fleetType | String(12) | A319, CRJ, A320,737/800-|
|Airfield | FQFC | String(10) | Flight Number, Example: US3154 (Not considered unique) see registration|
|GroundOps | GHR.gallons | int(6) | Gallons (Ground Hose Reel)|
|GroundOps | gearOnly | Boolean | True,False|
|GroundOps | geoPosition.lat | String(15) | 35.21382|
|GroundOps | geoPosition.lon | String(15) | -80.943054|
|GroundOps | iceTransaction | String | Guid, d6f678fd-8b37-4dad-85df-9cfae70184a3|
|GroundOps | iceTransaction.groupId | String | 43590217498|
|GroundOps | iceTransactionId | String | 5e5fedb6cbaa71a7d147a75b|
|GroundOps | inspectionOnly | Boolean | True,False|
|GroundOps | lastPost.failMessage | String(50) | Example: Server failed to respond|
|GroundOps | lastPost.failureOn | int(10) | Epoch Time|
|GroundOps | notes | String(256) | Text|
|GroundOps | padId | String(15) | Example: Sierra Pad, Charlie Pad, Echo Pad, Num 2 Pad|
|GroundOps | postfailCount | int(10) | 271|
|GroundOps | postedOn | int(10) | Epoch Time|
|GroundOps | postedTo | String | Server Name, URL|
|GroundOps | postedVia | String(15) | Method: Network Name or Manually|
|GroundOps | precipCode | int(6) | Numeric code describing type of precip|
|GroundOps | slotId | String(6) |  Slot Number on Pad, ex: 1,2,3,4…|
|GroundOps | src_ip | String(16) | Source IP Address|
|Airfield | airportId | String(6) | Current Airport (Not Destination or Arriving From) Example: KCLT, KATL,KIAD : ICAO reference, IATA code|
|GroundOps | supercededById | Boolean | True,False|
|GroundOps | tactileCheck | Boolean | True,False|
|Airfield | registration | String | Aircraft Tail Number, ex: N247UW, N123UW|
|GroundOps | teamLead.employeeNum | String(15) | 794671|
|GroundOps | trainingMode | Boolean | True,False|
|GroundOps | type1.freezePoint | int(6) | Temp|
|GroundOps | type1.gallonsA | int(10) | Gallons Number|
|GroundOps | type1.gallonsB | int(10) | Gallons Number|
|GroundOps | type1.gallons.enteredManually | Boolean | True,False|
|GroundOps | type1.kFactor | int() ||
|GroundOps | type1.percent  | int() ||
|GroundOps | type1.position1 | Boolean | True,False|
|GroundOps | type1.position2 | Boolean | True,False|
|GroundOps | type1.position3 | Boolean | True,False|
|GroundOps | type1.position4  | Boolean | True,False|
|GroundOps | type1.pulseCount | int() ||
|GroundOps | type1.start | int(10) | Epoch Time|
|GroundOps | type1.stop | int(10) | Epoch Time|
|GroundOps | type1.temp | int() | Temperture|
|GroundOps | type4.gallonsA | int(10) | Gallons Number|
|GroundOps | type4.gallonsB | int(10) | Gallons Number|
|GroundOps | type4.gallons.enteredManually | Boolean | True,False|
|GroundOps | type4.kFactor  | int() ||
|GroundOps | type4.position1 | Boolean | True,False|
|GroundOps | type4.position2 | Boolean | True,False|
|GroundOps | type4.position3 | Boolean | True,False|
|GroundOps | type4.position4 | Boolean | True,False|
|GroundOps | type4.pulseCount | int() ||
|GroundOps | type4.start  | int(10) | Epoch Time|
|GroundOps | type4.stop | int(10) | Epoch Time|
|GroundOps | weatherCode | String(10) | Weather Code, Example: IF (Ice Fog)|
|GroundOps | eventType | String(10) | Type of Service Performed. Examples: Refueling, Sanitation, Towing, Cargo Loading, De-icing, Anti-icing.|
|Airfield | runway | String() | Runway Designation Example: 26L|
|Airfield | taxiway | String() | Examples: C1, D3, F2, F, E, Q3, N4|
|Airfield | stand | String(50) | Examples: Cargo A, Cargo 1, 2, 3, 3, ANG Apron, South hanger, Ramp X|



[Contents](./contents.md)<br />
[Home](./)
