### Resource distributed by Snowflake Software Ltd. For support visit developer.laminardata.aero

#### This schema bundle comprises the complete list of schemas used to serve the GeoJSON data found on the Laminar Data APIs.

#### This bundle contains all the schemas you will need to get started developing against the JSON endpoints of the Laminar Data APIs.

#### The top level schema for each of the Laminar Data APIs is listed below:

flights_by_gufi_geojson_schema.json:
* v1/flights/{gufi}

flight_summary_geojson_schema.json
* v1//tiles/{zoom}/{x}/{y}/flights
* v1/airlines/{airline}/flights
* v1/aerodromes/{orig}/departures
* v1/aerodromes/{dest}/arrivals
* v1/aerodromes/{orig}/destinations/{dest}/flights
* v1/icao-prefixes/{prefix}/firs/{fir}/flights

flight_plans_geojson_schema.json
* v2/airlines/{airline}/flightplans
