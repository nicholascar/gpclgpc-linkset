# GPC / LGPC Linkset
This code repository contains a Linkset - a specialised Dataset linking objects in two other Datasets.

This Linkset contains [SKOS mapping properties](https://www.w3.org/TR/skos-reference/#mapping) between Concepts in the [GPC](http://linked.data.gov.au/def/gpc) and Concepts in the [LGPC](http://linked.data.gov.au/def/lgpc) vocabularies.

GPC, "Government Purpose Classification" is an [Australian Bureau of Statistics (ABS)](https://www.abs.gov.au) a vocabulary of classifiers for use in the collection, analysis and dissemination of local government finance statistics in Australia. It is online as a webpage as the [Revised Government Purpose Classification 2006](https://www.abs.gov.au/AUSSTATS/abs@.nsf/Latestproducts/5514.0.55.001Appendix92005).

LGPC, "Local Government Purpose Classification" is an [Australian Bureau of Statistics (ABS)](https://www.abs.gov.au) a vocabulary of classifiers for use in the collection, analysis and dissemination of local government finance statistics in Australia. It is online as a webpage as the [Local Government Purpose Classification, 2008](https://www.abs.gov.au/AUSSTATS/abs@.nsf/DetailsPage/5514.0.55.0022008).

The original LGPC document publication, linked to immediately above, contains the correspondence information used for this Linkset.


## Linkset relations
This Linkset uses only [SKOS Mapping Properties](https://www.w3.org/TR/skos-reference/#mapping) to map between AGIFT & COFOG-A. Only the following properties are used:

* `skos:exactMatch`
* `skos:broadMatch`
* `skos:narrowMatch`


## Repository Contents
This repository contains the following files and folders:

* [README.md](README.md) - this file
* [resources/](resources/) - background information: the GPC & LGPC vocabularies as RDF (turtle) files as well as the original LGCP document publication which contains the correspondence information used for this Linkset
* [header.ttl](header.ttl) - this Linkset’s data.ttl header information, stored separately for ease of access
* [example-data.ttl](example-data.ttl) - this Linkset's links as an RDF (turtle) file
* [example-data-unreified.ttl](example-data-unreified.ttl) - the Linkset's links as triples, unreified
* [data.ttl](data.ttl) - this Linkset's links as an RDF (turtle) file
* [data-unreified.ttl](data-unreified.ttl) - the Linkset's links as triples, unreified
* [methods/](methods/) - a folder containing the interim correspondences.xlsx file used for correspondence transpcription from the LGPC PDF document and a Python script to turn data-flat.ttl into data.ttl


## Rights & License
The content of this repository is licensed for use under the [Creative Commons 4.0 License](https://creativecommons.org/licenses/by/4.0/). See the [license deed](LICENSE) all details.

Please note:

The GPC & LGPC vocabularies' content is copyright of the ABS, as per the notification in their source documents that reads:

> This work is copyright. Apart from any use as permitted under the Copyright Act 1968, no part may be reproduced by any process without prior written permission from the Commonwealth. Requests and inquiries concerning reproduction and rights in this publication should be addressed to The Manager, Intermediary Management, Australian Bureau of Statistics, Locked Bag 10, Belconnen ACT 2616, by telephone (02) 6252 6998, fax (02) 6252 7102, or email: <intermediary.management@abs.gov.au>.

The correspondences that constitute the links in this Linkset are considered part of the LGPC vocabulary and thus fall under the same rights notice.


## Contacts
*Linkset author & technical contact:*  
**Nicholas Car**  
SURROUND Australia Ptl Ltd  
<nicholas.car@surroundaustralia.com>  
<http://orcid.org/0000-0002-8742-7730>  
