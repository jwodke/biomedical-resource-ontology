# biomedical-resource-ontology (BRO)
A repository to store and maintain our version of BRO.

*Scope of ontology:* A meta-ontology describing biomedical resources for
computational biomedicine (specifically, at this time, for the BioCypher
project).

## Changes affected after adoption and migration of BRO 3.2.1
Version 4.1.1: We removed all properties related to classes removed in v4.1.0 and 
updated the preamble.

Version 4.1.0: We reduced BRO to its core purpose, describing biomedical
resources, by removing all other top-level classes. The sole remaining top-level
class is `Resource`. BRO is now provided in turtle format.

Version 4.0.0: We moved BRO to GitHub and added one class (`Adapter`). We
incremented the major version to indicate the migration.

## BRO projects
- [BioCypher](https://biocypher.org): a meta-graph for BC adapters
(https://meta.biocypher.org)

## BRO history
BRO has been intially developed by Jessica Tenenbaum and coworkers and published
in the [Journal of Biomedical
Informatics](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3050430/) (doi:
10.1016/j.jbi.2010.10.003) and is hosted (until version 3.2.1) on
[BioPortal](https://bioportal.bioontology.org/ontologies/BRO).
