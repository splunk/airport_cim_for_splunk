# How to use the CIM

The Splunk4Airports CIM has been compiled using multiple data sources in order to gain a uniformed approach to Airport data. You can see the data sources used in the [Readme](./README.md)

### How does it work

The first step is to identify the various values for the fields listed in the CIM. 
For example; in the Airfield > Aircraft dataset You'll see the following:
|Airfield|flightNumber|int(4)|The numerical flight number of the aircraft|1234|
|Airfield|airline|String|The IATA code for the operating airline|EZY, DY, AA|
|Airfield|FQFC|String|Fully Qualified Flight Code|EZY1234|
