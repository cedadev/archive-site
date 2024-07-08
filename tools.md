---
title: Tools
layout: base_ceda
permalink: /tools/
---

## General Download Services

 - **[OPeNDAP](https://data.ceda.ac.uk)** - Can be used for browsing the archive file system and interactive downloads. It's also a <a href="https://help.ceda.ac.uk/article/4431-ceda-archive-web-download-and-services">scriptable interface</a> (API) to the archive over http, allowing remote subsetting within IDL, Matlab. Python etc.
- **FTP  -** The [File Transfer Protocol](https://help.ceda.ac.uk/article/280-ftp) is very common and is a good interface if you need to automate your data downloads. 
- **JASMIN file system -** _JAMSIN users should consult the JASMIN documentation on direct_ [CEDA Archive access](https://help.jasmin.ac.uk/article/3838-ceda-archive) _and appropriate_ [data transfer mechanisms](https://help.ceda.ac.uk/category/217-data-transfer)
## Metadata Services

- **[CEDA Catalogue](https://catalogue.ceda.ac.uk/)** - Browsing information about the datasets in the archive. 
- [CSW](https://csw.ceda.ac.uk/geonetwork/srv/eng/csw?SERVICE=CSW&VERSION=2.0.2&REQUEST=GetCapabilities) Programatically interrogating the CEDA Catalogue using **[Catalogue Service for the Web](http://www.opengeospatial.org/standards/cat)** - service API. You can also use this service to harvest the metadata using the [OAI-PMH](https://csw.ceda.ac.uk/geonetwork/srv/eng/oaipmh?verb=ListRecords&metadataPrefix=oai_dc) protocol.


## Specific data set services

Tools to subset or aggregate data before downloading are available for some data. These are linked to from the catalogue page for that dataset.

- [Web Processing Service](https://ceda-wps-ui.ceda.ac.uk/) (WPS) 
- [Earth System Grid Federation](https://esgf-index1.ceda.ac.uk/projects/esgf-ceda/) (ESGF) 
- [Satellite Data Finder](https://geo-search.ceda.ac.uk/) (Sentinel and Landsat missions currently) 
- [Flight Finder](https://flight-finder.ceda.ac.uk/) (airborne data) 
- [Met Office MIDAS stations search](midas_stations) 
- [CORRAL catalogue](https://utils.ceda.ac.uk/corral)

## Data format checkers

When producing data you can use these tools to work out it's formated correctly.

 - [CSV checker](https://utils.ceda.ac.uk/cgi-bin/badccsv/csvchecker)
 - [NASA-Ames checker](https://utils.ceda.ac.uk/nachecker)

