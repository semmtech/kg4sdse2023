# About
This repository contains RDF snippets as referred to in the paper "Towards Recommendations for Knowledge-graph-based Requirements Management in Construction: A Report on the EU DigiChecks Project" as presented by Bram Bazuin, Sander Stolk, and Marco Stevens on the KG4SDSE 2023 workshop at CAiSE23.

The snippets contain examples of graph-based requirements expressed in level 2b (enriched text) and level 3 (model-based). All examples use the Turtle serialization and adopt the CEN 17632 ontology. The prefix `prmt:` is used with key PRM relations not covered by this ontology, such as those for V&V. Work done in the various work packages of the DigiChecks project will determine more fully the necessary ontological terminology for PRM, recommend existing ontologies appropriate for expressing these terms or, if necessary, develop an ontology for that purpose.


## Directory structure
* `rdf`
  * `enriched-text-1.ttl` - Example of an enriched-text requirement (level 2b).
  * `enriched-text-2.ttl` - Example of an enriched-text requirement (level 2b) split by the applicant into two distinctive parts.
  * `model-based.ttl` - Example of a model-based requirement (level 3), expressed with the Numerate Web ontology and based on the first derived requirement that is defined in `enriched-text-2.ttl`.

## Acknowledgements
This project has received funding from the European Union’s Horizon Europe research and innovation programme – Project 101058541 – DigiChecks.
