---
layout: ontology_detail
id: omicon
title: The Omics Ontology
jobs:
  - id: https://travis-ci.org/GLOMICON/the-omics-ontology
    type: travis-ci
build:
  checkout: git clone https://github.com/GLOMICON/the-omics-ontology.git
  system: git
  path: "."
contact:
  email: cjmungall@lbl.gov
  label: Chris Mungall
description: The Omics Ontology is an ontology...
domain: stuff
homepage: https://github.com/GLOMICON/the-omics-ontology
products:
  - id: omicon.owl
  - id: omicon.obo
dependencies:
 - id: envo
 - id: ro
 - id: pato
 - id: bfo
tracker: https://github.com/GLOMICON/the-omics-ontology/issues
license:
  url: http://creativecommons.org/licenses/by/3.0/
  label: CC-BY
---

Enter a detailed description of your ontology here
