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

## [Wikidata5m](https://deepgraphlearning.github.io/project/wikidata5m)

This dataset has the shortcoming that it is not provided in rdf but must be converted. Our converter covers only parts of it at the moment and does not create any ontological data. 

Download:
- [Raw](https://www.dropbox.com/s/563omb11cxaqr83/wikidata5m_all_triplet.txt.gz?dl=1)
- [Corpus](https://www.dropbox.com/s/7jp4ib8zo3i6m10/wikidata5m_text.txt.gz?dl=1)https://www.dropbox.com/s/7jp4ib8zo3i6m10/wikidata5m_text.txt.gz?dl=1

Convert it to java with the following Python3 script:
```python3
import gzip


def escape_turtle_string(input_string):
    escape_characters = {
        '\\': '\\\\',
        '"': '\\"',
        '\n': '\\n',
        '\t': '\\t',
        '\r': '\\r',
    }
    escaped_string = ""
    for char in input_string:
        if char in escape_characters:
            escaped_string += escape_characters[char]
        else:
            escaped_string += char
    return escaped_string


output_path = "wikidata5m.ttl"

with open(output_path, 'w') as of:
    input_gzip_path = "wikidata5m_text.txt.gz"
    prefixes = {"wd": "http://www.wikidata.org/entity/",
                "rdfs": "http://www.w3.org/2000/01/rdf-schema#",
                "ent": "http://www.wikidata.org/entity/",
                "prop": "http://www.wikidata.org/wiki/Property:"}

    for k, v in prefixes.items():
        of.write(f"@prefix {k}: <{v}> .\n")
        # print(f"@prefix {k}: <{v}> .")

    with gzip.open("wikidata5m_all_triplet.txt.gz", 'rt') as input:

        for line in input:
            s, p, o = line.split()
            l = [s, p, o]
            out = []
            for y in l:
                if y[0] == "Q":
                    out.append("ent:" + y)
                elif y[0] == "P":
                    out.append("prop:" + y)
                else:
                    out.append(y)
            of.write(f"{out[0]} {out[1]} {out[2]} .\n")
    with gzip.open("wikidata5m_text.txt.gz", 'rt') as input:
        for line in input:
            sep_pos = line.find("\t")  # it is tab seperated
            id = line[0:sep_pos]
            comment = escape_turtle_string(line[sep_pos + 1:-1])  # -1 to remove the trailing \n
            of.write(f"<wd:{id}> <rdfs:comment> \"{comment}\" .\n")
```
