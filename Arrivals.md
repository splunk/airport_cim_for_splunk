### Arrivals

The fields relating to arriving aircraft

| Dataset Name  | Field Name  | Data Type | Description | Examples |
|:--------------|:------------|:----------|:------------|:---------|
|Airfield|originAirport|String(3)|IATA code for the airport where the aircraft came from in that leg|LGW|
|Airfield|SIBT|int(10)|Scheduled In Block Time - Epoch|0516469200|
|Airfield|AIBT|int(10)|Actual In Block Time - Epoch|0516469200|
|Airfield|EIBT|int(10)|Estimated In Block Time - Epoch|0516469200|
|Airfield|TIBT|int(10)|Target In Block Time - Epoch|0516469200|
|Airfield|ETDN|int(10)|Estimated Touchdown (ELDT) - Epoch|0516469200|
|Airfield|ETEN|int(10)|Estimated Ten Minutes Out - Epoch|0516469200|
|Airfield|ATDN|int(10)|Actual Touchdown (ALDT) - Epoch|0516469200|
|Airfield|ATEN|int(10)|Actual Ten Minutes Out - Epoch|0516469200|
|Airfield|AFAT|int(10)|Actual Final Approach Time - Epoch|0516469200|
|Airfield|approachZoneEntry|int(10)|Time the aircraft entered the approach zone - Epoch|0516469200|
|Airfield|LPocATO|int(10)|Actual time of operation at the last port of call - Epoch|0516469200|
|Airfield|AXIT|int|Actual Taxi In Time - duration in seconds|451|
|Airfield|EXIT|int|Estimated Taxi In Time - duration in seconds|300|
|Airfield|viaAirport|String(3)|IATA code for an intermediate airport on this arriving leg, when the route has more than one port of call|BGI, SIN|



[Contents](./contents.md)<br />
[Home](./)
