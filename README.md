# OpenFlight
 OpenFlight is a dataset containing global airports information and
  static flight information without real time data such as daily flights.

## Data
  
[Airports.csv](./airports.csv) is a CSV file showing name,iata,icao,lat,lon,country and alt 
of each airport. There also is a json file for Airports.
- [Airports.json](./airports.json)

[FlihgtSummary.json](FlightSummary.json) is a JSON file showing the callsign, icao code of the origin 
and destination of each flight. There should be a CSV file for Flights. **Note** This data sheet
 is not complete. The goal is to collect each Scheduled flight in the world.

## Tool

[util](./util.py) is a python script supporting,
- convertCode(code) converts  an airport code from icao to iata or from iata to icao.

- findCountry(code) /=returns the country where the airport locates.

