## MapMatching using Streams Geospatial Toolkit in Bluemix

This project provides a simple SPL data flow for ingesting tuples through the HTTP server of Streams (streamx.inet toolkit)
and then doing map matching using a preconfigured map, which can be modified in the Main.spl file, the `mapfile` parameter can
be modified to consume a different OSM file depending on the area of operation.

The output from the map matching operator is submitted to a `WebSink` operator that allows for the user to consume the output
using the REST API.

The code can be deployed into BlueMix that is described in further detail on the StreamsDev blog (Real-time Map Matching using BlueMix).
