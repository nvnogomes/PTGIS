# PTGIS

The data used to populate the database was the one contained in the shapefiles that are freely obtained from the portuguese DGT. (http://www.dgterritorio.pt/)

The Madeira main island polygons were not valid, so the MakeValid command from the SQLServer was used to accomplish the union of polygons.

The tabled prefixed with CAOP2016 are the ones imported from the shapefiles, and server as base to union polygons by municipality, district, NUTS3, and NUTS3.
The NUTS3 and NUTS2 maps where build with base in the Wikipedia list of municipalities by NUTS (https://pt.wikipedia.org/wiki/NUTS_de_Portugal)
