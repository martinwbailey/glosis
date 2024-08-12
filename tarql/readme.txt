https://tarql.github.io/


/Users/martinbailey/code/glosis/tarql


sh tarql-1.2/bin/tarql examples/sample-2.sparql examples/TechCrunchcontinentalUSA.csv

sh tarql-1.2/bin/tarql lucas/lucas2018_tarql.sparql lucas/LUCAS-SOIL-2018.csv  > soil-data.rdf



Here is a Lucas mapping from Glosis : 

https://github.com/glosis-ld/glosis/blob/4fc33ecf24f68a92a967671a117b62c63c1f30c8/data_alignment/LUCAS/LUCAS_mapping_v3e.ttl
https://github.com/pvgenuchten/glosis/blob/93c09509053db5bc42638ea0237405f6d5196644/transformations/LUCAS_mapping_v3d.ttl

Follow in pvgenuchten footsteps, he uses tarql for this transformer tool
I think this is used to convert CSV procedure data into RDF classes as part of the actual Glosis ontology

https://github.com/pvgenuchten/glosis/tree/93c09509053db5bc42638ea0237405f6d5196644/utils/transformer_tool