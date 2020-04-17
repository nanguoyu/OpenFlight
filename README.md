# OpenFlight
 OpenFlight is a dataset containing global airports information and
  static flight information without real time data.

## Data
  
[Airports.csv](./airports.csv) is a CSV file showing name,iata,icao,lat,lon,country and alt 
of each airport. There is a json file for Airports.
- [Airports.json](./airports.json)

[FlihgtSummary.json](FlightSummary.json) is a JSON file showing the callsign, icao code of the origin 
and destination of each flight. There should be a CSV file for Flights. **Note** This data sheet
 is not complete. The goal is to collect each Scheduled flight in the world.
- [FlihgtSummary.CSV](#)

## Tool

[util](./util.py) is a python script supporting,
- convertCode(code) convert icao to iata or iata to icao. If the code is iata, you get its icao. 
If the code is icao, you get its iata.

- findCountry(code)  return the country airport locates.

