---
title: Tools
layout: base_ceda
---

## General Download Services


 - **[OPeNDAP](https://data.ceda.ac.uk)** - Can be used for browsing the archive file system and interactive downloads. It's also a <a href="https://help.ceda.ac.uk/article/4431-ceda-archive-web-download-and-services">scriptable interface</a> (API) to the archive over http, allowing remote subsetting within IDL, Matlab. Python etc.
 - <strong><a>FTP</a>&nbsp; -&nbsp;</strong>The <a href="https://help.ceda.ac.uk/article/280-ftp">File Transfer Protocol</a> is very common and is a good interface if you need to automate your&nbsp;data downloads.
 - <strong>JASMIN file system -&nbsp;</strong><em>JAMSIN users should consult the JASMIN documentation on direct&nbsp;</em><a href="https://help.jasmin.ac.uk/article/3838-ceda-archive">CEDA Archive access&nbsp;</a><em>and appropriate&nbsp;</em><a href="https://help.ceda.ac.uk/category/217-data-transfer">data transfer mechanisms</a>

## Metadata Services

 - <strong><a href="https://catalogue.ceda.ac.uk/">CEDA Catalogue</a></strong>&nbsp;-&nbsp;Browsing information about the datasets in the archive.
 - <a href="https://csw.ceda.ac.uk/geonetwork/srv/eng/csw?SERVICE=CSW&amp;VERSION=2.0.2&amp;REQUEST=GetCapabilities">CSW</a> Programatically interrogating the CEDA Catalogue using&nbsp;<strong><a href="http://www.opengeospatial.org/standards/cat">Catalogue Service for the Web</a></strong>&nbsp;- service API. You can also use this service to harvest the metadata using the <a href="https://csw.ceda.ac.uk/geonetwork/srv/eng/oaipmh?verb=ListRecords&amp;metadataPrefix=oai_dc">OAI-PMH</a> protocol.

## Specific data set services

<p>Tools to subset or aggregate data before downloading are available for some data. These are linked to from the catalogue page for that dataset.</p>

 - <a href="https://ceda-wps-ui.ceda.ac.uk/">Web Processing Service</a> (WPS)
 - <a href="https://esgf-index1.ceda.ac.uk/projects/esgf-ceda/">Earth System Grid Federation</a> (ESGF)
 - <a href="https://geo-search.ceda.ac.uk/">Satellite Data Finder</a> (Sentinel and Landsat missions currently)
 - <a href="https://flight-finder.ceda.ac.uk/">Flight Finder</a> (airborne data)
 - <a href="/midas_stations">Met Office MIDAS stations search</a>
 - <a href="/corral">CORRAL catalogue</a>

## Data format checkers

When producing data you can use these tools to work out it's formated correctly.

 - [CSV checker](/cgi-bin/badccsv/csvchecker)
 - [NASA-Ames checker](/nachecker)

