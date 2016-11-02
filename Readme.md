###Resource distributed by Snowflake Software Ltd. For support visit developer.laminardata.aero

####This schema bundle comprises the complete list of schemas used to serve the XML data found on the Laminar Data APIs.

####Data downloaded from the Laminar Data API will not directly validate against the schemas found in this bundle, to do this you will need to alter the header of the XML downloaded from Laminar so that the xmlns declarations point to a local resource rather than an online location.

####This bundle contains all the schemas you will need to get started developing against the XML endpoints of the Laminar Data APIs, including both source and reference schemas.

####The top level schema for each of the Laminar Data APIs is listed below:

####FLIGHT DATA APIs

/airlines/{airline.prefix}/flights

/flights/{gufi}

/tiles/{zoom}/{x}/{y}/flights

#####\fixm\3.0.1\core\fixm.xsd

####WEATHER DATA APIs

/aerodromes/{aerodrome.icao}/metar

/aerodromes/{aerodrome.icao}/taf

/icao-prefixes/{icao.prefix}/sigmets

/sigmets/{id}

#####\AvXML-1.1\iwxxm\1.1\iwxxm.xsd

####NOTAM APIs

/icao-prefixes/{icao.prefix}/firs/{fir.icao}/notams

/notams/{notam.id}

#####\aixm\5.1\extensions\event\eventExtension\SnowflakeEventExtension.xsd

####AERONAUTICAL DATA APIs

/icao-prefixes/{icao.prefix}/firs/{fir.icao}/route-segments

/aerodromes/{aerodrome.icao}

/icao-prefixes/{icao.prefix}/firs/{fir.icao}/airspaces

/airspaces/{airspace.icao}

/icao-prefixes/{icao.prefix}/firs/{fir.icao}/designated-points

/icao-prefixes/{icao.prefix}/firs/{fir.icao}/designated-points/{icao}

/icao-prefixes/{icao.prefix}/firs/{fir.icao}/navaids

/icao-prefixes/{icao.prefix}/firs/{fir.icao}/navaids/{icao}

#####\aixm\5.1\core\AIXM_Features.xsd

####REGULATION DATA APIs

/icao-prefixes/{icao.prefix}/airspace-regulations

/icao-prefixes/{icao.prefix}/aerodrome-regulations

/regulations/{id}

#####\aixm\5.1\extensions\LaminarData\FlowRegulation\FlowRegulation_Extension.xsd

####REFERENCE DATA APIs

/airlines

/airlines/{airline.prefix}

/icao-prefixes

/icao-prefixes/{icao.prefix}

/icao-prefixes/{icao.prefix}/firs

/icao-prefixes/{icao.prefix}/firs/{fir.icao}

#####\gml\3.2.1\gml.xsd
