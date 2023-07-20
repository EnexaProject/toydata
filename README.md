# Toy Data 
This repository contains toy data created for the sole purpose of testing the pipeline. 

## Breweries from DBpedia 

Retrievable from: https://dbpedia.org/sparql

Query:
```SPARQL
construct where {?s ?p ?o. ?s a dbo:Brewery. FILTER(!isLiteral(?o)) } LIMIT 10000
```

## [KG_extraction_for_ENEXA](https://github.com/INDElab/KG_extraction_for_ENEXA_Hackathon)

Storage stats: 37923 triples (6205 distinct subjects, 369 distinct predicates, 14772 distinct objects)

Files: 
- https://github.com/INDElab/KG_extraction_for_ENEXA_Hackathon/raw/main/KGs/extracted_graph_for_enexa_hackathon_LLM_KnowGL.ttl
- https://github.com/INDElab/KG_extraction_for_ENEXA_Hackathon/raw/main/KGs/ontology_version_1.ttl

## Linked Geo Data 2015-11-02

This dataset is larger, i.e.: 

Storage stats: 37923 triples (6205 distinct subjects, 369 distinct predicates, 14772 distinct objects)

Files at http://downloads.linkedgeodata.org/releases/2015-11-02/
```
[- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Abutters.node.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Abutters.way.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-AerialwayThing.node.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-AerialwayThing.way.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-AerowayThing.node.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-AerowayThing.way.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Amenity.node.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Amenity.way.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-BarrierThing.node.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-BarrierThing.way.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Boundary.node.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Boundary.way.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Craft.node.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Craft.way.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-CyclewayThing.node.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-CyclewayThing.way.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-EmergencyThing.node.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-EmergencyThing.way.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-HistoricThing.node.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-HistoricThing.way.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Leisure.node.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Leisure.way.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-LockThing.node.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-LockThing.way.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-ManMadeThing.node.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-ManMadeThing.way.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-MilitaryThing.node.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-MilitaryThing.way.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Office.node.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Office.way.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Place.node.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Place.way.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-PowerThing.node.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-PowerThing.way.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-PublicTransportThing.node.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-PublicTransportThing.way.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-RailwayThing.node.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-RailwayThing.way.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-RouteThing.node.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-RouteThing.way.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Shop.node.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Shop.way.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-SportThing.node.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-SportThing.way.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-TourismThing.node.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-TourismThing.way.sorted.nt.bz2
- http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-18-CyclewayThing.node.sorted.nt.bz2
](http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Abutters.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Abutters.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-AerialwayThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-AerialwayThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-AerowayThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-AerowayThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Amenity.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Amenity.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-BarrierThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-BarrierThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Boundary.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Boundary.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Craft.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Craft.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-CyclewayThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-CyclewayThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-EmergencyThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-EmergencyThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-HistoricThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-HistoricThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Leisure.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Leisure.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-LockThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-LockThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-ManMadeThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-ManMadeThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-MilitaryThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-MilitaryThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Office.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Office.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Place.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Place.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-PowerThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-PowerThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-PublicTransportThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-PublicTransportThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-RailwayThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-RailwayThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-RouteThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-RouteThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Shop.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Shop.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-SportThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-SportThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-TourismThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-TourismThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-18-CyclewayThing.node.sorted.nt.bz2)http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Abutters.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Abutters.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-AerialwayThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-AerialwayThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-AerowayThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-AerowayThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Amenity.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Amenity.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-BarrierThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-BarrierThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Boundary.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Boundary.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Craft.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Craft.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-CyclewayThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-CyclewayThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-EmergencyThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-EmergencyThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-HistoricThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-HistoricThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Leisure.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Leisure.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-LockThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-LockThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-ManMadeThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-ManMadeThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-MilitaryThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-MilitaryThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Office.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Office.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Place.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Place.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-PowerThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-PowerThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-PublicTransportThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-PublicTransportThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-RailwayThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-RailwayThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-RouteThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-RouteThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Shop.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-Shop.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-SportThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-SportThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-TourismThing.node.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-02-TourismThing.way.sorted.nt.bz2
http://downloads.linkedgeodata.org/releases/2015-11-02/2015-11-18-CyclewayThing.node.sorted.nt.bz2
```

Script to download them like `bash download_script.sh lgd_links.txt`:
```
#!/bin/bash

# Check if the file path is provided as an argument
if [ -z "$1" ]; then
    echo "Please provide the file path as an argument."
    exit 1
fi

# Read the file line by line
while IFS= read -r link; do
    # Skip empty lines
    if [ -z "$link" ]; then
        continue
    fi

    # Download the file using wget
    echo "Downloading: $link"
    wget "$link"
    echo "Download complete!"

done < "$1"
```

Extract them: 
```
bzip2 -d *
```

Concat them:
```
cat *.nt > lgd-2015-11-02-all.nt
```
