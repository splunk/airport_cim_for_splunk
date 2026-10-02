### Departures

The fields relating to departing aircraft

| Dataset Name  | Field Name  | Data Type | Description | Examples |
|:--------------|:------------|:----------|:------------|:---------|
|Airfield|destAirport|String(3)|IATA code for the airport where the aircraft is going to in that leg|LGW|
|Airfield|SOBT|int(10)|Scheduled Off Block Time - Epoch|0516469200|
|Airfield|AOBT|int(10)|Actual Off Block Time - Epoch|0516469200|
|Airfield|EOBT|int(10)|Estimated Off Block Time - Epoch|0516469200|
|Airfield|TOBT|int(10)|Target Off Block Time - Epoch|0516469200|
|Airfield|COBT|int(10)|Calculated Off Block Time - Epoch|0516469200|
|Airfield|EGTO|int(10)|Estimated Gate Open Time - Epoch|0516469200|
|Airfield|AGTO|int(10)|Actual Gate Open Time - Epoch|0516469200|
|Airfield|EBST|int(10)|Estimated Boarding Start Time - Epoch|0516469200|
|Airfield|ABST|int(10)|Actual Boarding Start Time - Epoch|0516469200|
|Airfield|EGCL|int(10)|Estimated Gate Closed Time - Epoch|0516469200|
|Airfield|AGCL|int(10)|Actual Gate Closed Time - Epoch|0516469200|
|Airfield|TSAT|int(10)|Target Startup Approval Time - Epoch|0516469200|
|Airfield|ESAT|int(10)|Estimated Startup Approval Time - Epoch|0516469200|
|Airfield|ASAT|int(10)|Actual Startup Approval Time - Epoch|0516469200|
|Airfield|ATOT|int(10)|Actual Take Off Time - Epoch|0516469200|
|Airfield|CTOT|int(10)|Calculated Take Off Time - Epoch|0516469200|
|Airfield|TTOT|int(10)|Target Take Off Time - Epoch|0516469200|
|Airfield|ETOT|int(10)|Estimated Take Off Time - Epoch|0516469200|
|Airfield|ACGT|int(10)|Actual Commence of Ground Handling Time - Epoch|0516469200|
|Airfield|AEBT|int(10)|Actual End of Boarding Time - Epoch|0516469200|
|Airfield|ASRT|int(10)|Actual Start Up Request Time - Epoch|0516469200|
|Airfield|PBST|int(10)|Planned Boarding Start Time - Epoch|0516469200|
|Airfield|PLCT|int(10)|Planned Last Call Time - Epoch|0516469200|
|Airfield|ALCT|int(10)|Actual Last Call Time - Epoch|0516469200|
|Airfield|AXOT|int|Actual Taxi Out Time - duration in seconds|900|
|Airfield|EXOT|int|Estimated Taxi Out Time - duration in seconds|900|
|Airfield|SID|String|Standard Instrument Departure|MAXIT1G, BPK7G|
|Airfield|viaAirport|String(3)|IATA code for an intermediate airport on this departing leg, when the route has more than one port of call|NAS, DND|


[Contents](./contents.md)<br />
[Home](./)
