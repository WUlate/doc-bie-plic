# Integration of Plinian Core in Biodiversity Information Explorer

## Introduction
This repository contains the documentation of the integration of the [Plinian Core (PliC)](https://github.com/tdwg/PlinianCore) standard in the Biodiversity Information Explorer (BIE) module of the [Atlas of Living Australia (ALA)](https://www.ala.org.au/). The integration was carried out to support the [Living Atlas](https://living-atlases.gbif.org/) community incorporating species information in national and institutional portals based on ALA software.

These tasks were done in the context of the [GBIF Capacity Enhancement Support Programme (CESP)](https://www.gbif.org/programme/82219/capacity-enhancement-support-programme) [2020-006 project](https://www.gbif.org/project/4YJIFEvYJi5kfuUVzNcfYH/from-shared-experiences-to-shared-knowledge-and-common-solutions-collaborating-to-improve-web-based-tools-in-latin-america-and-the-caribbean) *"From shared experiences to shared knowledge and common solutions: collaborating to improve web-based tools in Latin America and the Caribbean"*. To achieve this, the [National Education and Research Network (RNP) of Brazil](https://www.rnp.br/) and the non-profit organization [Research Institute of Biodiversity Informatics in Costa Rica (CRBio)](http://www.crbio.org) established a cooperation agreement within the scope of the objectives of the [Global Information System Biodiversity (GBIF)](https://www.gbif.org/).

PliC is a generalistic specification, oriented to share descriptions and nomenclature, as well as legal, conservation, and management details, and other aspects of species level information from local and regional sources ([Pando 2018](https://doi.org/10.3897/biss.2.25869)). Current PliC version (3.2.2.6) was made publicly available in December 2022. A Species Information Interest Group and a Task Group of [Biodiversity Information Standards (TDWG)](https://www.tdwg.org/)  have reviewed definitions of terms and formal declarations to ratify PliC as a TDWG Standard. 

Several full-fledged implementations of PliC were produced, between 2014 and 2019, including the [Atlas of Living Costa Rica](http://www.crbio.org), the [Cross-Nature Project](https://datos.iepnb.es/), the [Vasque Country (Spain) Official Nature Information System](https://www.opendata.euskadi.eus/katalogoa/-/txostenak-ikerketak/espezieei-buruzko-informazioa-euskadiko-naturari-buruzko-informazio-sistema/), the [Colombian Biodiversity Catalog](https://catalogo.biodiversidad.co/) and [Enciclovida (Mexican Species Catalog)](https://enciclovida.mx/).

One of the most used tools to share standardized biodiversity data is the GBIF [Integrated Publishing Toolkit (IPT)](https://www.gbif.org/ipt). The IPT is an open source web application that allows institutions to standardize, to publish and share biodiversity data sets through Living Atlases, GBIF, and other biodiversity networks. The toolkit simplifies the process of publishing core data types (e.g. taxon occurrence, taxon checklists, sampling event) and, by means of extensions, it is possible to associate additional data with records of the core type.

This repository includes the documentation to publish species records with IPT, following the PliC standard. It also contains the links to the modified ALA repositories which allow the processing and display of this information.

## Deliverables

### Deliverable 1
Prepare the data in the Plinian Core standard\
**Description**: Generate test data files in DwCA format using PliC extensions\
**Deliverable**: Datasets\
**Repositories**:
https://www.sibbr.gov.br/page/cesp.html?lang=pt_BR#s
https://github.com/AtlasBiodiversidadCostaRica/doc-bie-plic/data
                     
### Deliverable 2
Presentation of the Plinan Core extension at the TDWG event\
**Description**: Formalization of the PliC extension in the registered GBIF extensions in the TDWG event\
**Deliverable**: Video and powerpoint presentation\
**Repositories**:
https://www.sibbr.gov.br/page/cesp.html?lang=pt_BR#s
https://www.youtube.com/watch?v=DcnCLWVXaBU&t=141s

### Deliverable 3
Extend the functionality of the Indexer (bie-index)\
**Description**: Modify code to add PliC fields to indexing processes\
**Deliverable**: development code\
**Repositories**:
https://www.sibbr.gov.br/page/cesp.html?lang=pt_BR#s
https://github.com/AtlasBiodiversidadCostaRica/bie-index


### Deliverable 4
Adapt functionality in the visualization (ala-bie)\
**Description**: Add new fields to the ALA Portals view\
**Deliverable**: development code\
**Repositories**:
https://www.sibbr.gov.br/page/cesp.html?lang=pt_BR#s
https://github.com/AtlasBiodiversidadCostaRica/ala-bie


### Deliverable 5
Create documentation for users throughout the process\
**Description**: Add or generate detailed documentation on preparing, indexing, and displaying species information using the BIE\
**Deliverable**: documentation\
**Repositories**:
https://www.sibbr.gov.br/page/cesp.html?lang=pt_BR#s
https://github.com/AtlasBiodiversidadCostaRica/doc-bie-plic
