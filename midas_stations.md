---
layout: base_ceda
permalink: /midas_stations
---

<div class="container">

        <ol class="breadcrumb">
        <li class="breadcrumb-item" id="breadcrumb-menu-home"><a href="/">Home</a></li><li class="breadcrumb-item" id="breadcrumb-menu-midas_stations">Search for Met Office MIDAS stations</li>
        </ol>













        <div class="row">
            <div class="col-md-12">



<form style="display:none;" class="editable-form" method="post" action="/edit/" id="0ea73316-5ef1-434a-8584-1bbeb6c22c54">
    <input type="hidden" name="csrfmiddlewaretoken" value="bQ6bzsEOEW2GsZMeGiFiRJOQhzBjHusCPNxogWyb2KYemi5slz8SE7RYyqMlE2cS">
    
    <p>
        <label for="content-0ea73316-5ef1-434a-8584-1bbeb6c22c54">Content:</label><br><textarea name="content" class="mceEditor charfield" rows="10" id="content-0ea73316-5ef1-434a-8584-1bbeb6c22c54" cols="40">&lt;h1&gt;Search for Met Office MIDAS stations&lt;/h1&gt;
&lt;h3&gt;Maps&lt;/h3&gt;
&lt;p&gt;&lt;/p&gt;
&lt;p&gt;&lt;a href="https://archive2.ceda.ac.uk/cgi-bin/midas_stations/midas_googlemap.cgi"&gt;View stations on interactive map&lt;/a&gt; &amp;nbsp; &amp;nbsp; Also available as a &lt;a href="google_earth"&gt;Google Earth&lt;/a&gt; download.&lt;/p&gt;
&lt;h3&gt;Search for station name&lt;/h3&gt;
&lt;p&gt;Finds all station names contain the given string. The string is matched anywhere within the station name and is not case sensitive.&lt;/p&gt;
&lt;form action="https://archive2.ceda.ac.uk/cgi-bin/midas_stations/search_by_name.cgi.py"&gt;
&lt;table class="table"&gt;
&lt;tbody&gt;
&lt;tr&gt;
&lt;td nowrap="nowrap"&gt;&lt;b&gt;Search for: &lt;/b&gt;&lt;input maxlength="40" name="name" size="25" title="Search for string anywhere in station name (no need to use wildcards)" type="text"&gt; &lt;input type="submit" value="Search"&gt; &lt;input type="reset" value="Reset"&gt;
&lt;p&gt;&lt;/p&gt;
Show only stations with &lt;a href="https://catalogue.ceda.ac.uk/uuid/dbd451271eb04662beade68da43546e1" target="_blank" title="Midas-open is the open data version of the Met Office Integrated Data Archive System (MIDAS) for land surface station data"&gt;MIDAS Open data&lt;/a&gt; &lt;input name="opendata" title="Only search for stations which produce MIDAS Open data" type="checkbox" value="y"&gt;
&lt;p&gt;&lt;/p&gt;
Open within year range: &lt;input maxlength="4" name="minyear" size="4" type="text"&gt; to: &lt;input maxlength="4" name="maxyear" size="4" type="text"&gt; &lt;b&gt;Or&lt;/b&gt; show current stations only &lt;input name="current" title="Only search for stations which are still operating" type="checkbox" value="y"&gt;&lt;/td&gt;
&lt;/tr&gt;
&lt;/tbody&gt;
&lt;/table&gt;
&lt;/form&gt;
&lt;h3&gt;Search for stations by postcode&lt;/h3&gt;
&lt;p&gt;Finds all stations with postcodes starting with the given string. Enter up to 5 significant characters. For example, "OX", "OX11" or "OX11 5"). Most stations do not have the full postcode recorded, so adding more characters is unlikely to return any matches. See &lt;a href="https://en.wikipedia.org/wiki/File:British_postcode_areas_map.svg"&gt;Postcode area map&lt;/a&gt; or &lt;a href="http://en.wikipedia.org/wiki/List_of_postal_areas_in_the_United_Kingdom"&gt;List of postal areas&lt;/a&gt; for more information on postcodes.&lt;/p&gt;
&lt;form action="https://archive2.ceda.ac.uk/cgi-bin/midas_stations/search_by_postcode.cgi.py"&gt;
&lt;table class="table"&gt;
&lt;tbody&gt;
&lt;tr&gt;
&lt;td nowrap="nowrap"&gt;&lt;b&gt;Search for: &lt;/b&gt; &lt;input maxlength="9" name="postcode" size="9" type="text"&gt; &amp;nbsp; &lt;input type="submit" value="Search"&gt; &lt;input type="reset" value="Reset"&gt;
&lt;p&gt;&lt;/p&gt;
Show only stations with &lt;a href="https://catalogue.ceda.ac.uk/uuid/dbd451271eb04662beade68da43546e1" target="_blank" title="Midas-open is the open data version of the Met Office Integrated Data Archive System (MIDAS) for land surface station data"&gt;MIDAS Open data&lt;/a&gt; &lt;input name="opendata" title="Only search for stations which produce MIDAS Open data" type="checkbox" value="y"&gt;
&lt;p&gt;&lt;/p&gt;
Open within year range: &lt;input maxlength="4" name="minyear" size="4" type="text"&gt; to: &lt;input maxlength="4" name="maxyear" size="4" type="text"&gt; &lt;b&gt;Or&lt;/b&gt; show current stations only &lt;input name="current" title="Only search for stations which are still operating" type="checkbox" value="y"&gt;&lt;/td&gt;
&lt;/tr&gt;
&lt;/tbody&gt;
&lt;/table&gt;
&lt;/form&gt;
&lt;h3&gt;Search for stations by UK county&lt;/h3&gt;
&lt;p&gt;Select a county to display all stations with that county. Please note that the county names are the names used by the Met Office and may not reflect the current county divisions within the UK. &lt;a href="traditional_counties_map"&gt;Map of traditional counties&lt;/a&gt;&lt;/p&gt;
&lt;form action="https://archive2.ceda.ac.uk/cgi-bin/midas_stations/search_by_county.cgi.py"&gt;
&lt;table class="table"&gt;
&lt;tbody&gt;
&lt;tr&gt;
&lt;td nowrap="nowrap"&gt;&lt;select name="county"&gt;
&lt;option value="ABERDEENSHIRE"&gt;ABERDEENSHIRE&lt;/option&gt;
&lt;option value="ALDERNEY"&gt;ALDERNEY&lt;/option&gt;
&lt;option value="ANGUS"&gt;ANGUS&lt;/option&gt;
&lt;option value="ANTRIM"&gt;ANTRIM&lt;/option&gt;
&lt;option value="ARGYLL (IN HIGHLAND REGION)"&gt;ARGYLL (IN HIGHLAND REGION)&lt;/option&gt;
&lt;option value="ARGYLL (IN STRATHCLYDE REGION)"&gt;ARGYLL (IN STRATHCLYDE REGION)&lt;/option&gt;
&lt;option value="ARGYLLSHIRE"&gt;ARGYLLSHIRE&lt;/option&gt;
&lt;option value="ARMAGH"&gt;ARMAGH&lt;/option&gt;
&lt;option value="AVON"&gt;AVON&lt;/option&gt;
&lt;option value="AYRSHIRE"&gt;AYRSHIRE&lt;/option&gt;
&lt;option value="BANFFSHIRE"&gt;BANFFSHIRE&lt;/option&gt;
&lt;option value="BEDFORDSHIRE"&gt;BEDFORDSHIRE&lt;/option&gt;
&lt;option value="BERKSHIRE"&gt;BERKSHIRE&lt;/option&gt;
&lt;option value="BERWICKSHIRE"&gt;BERWICKSHIRE&lt;/option&gt;
&lt;option value="BORDERS"&gt;BORDERS&lt;/option&gt;
&lt;option value="BRECKNOCKSHIRE"&gt;BRECKNOCKSHIRE&lt;/option&gt;
&lt;option value="BUCKINGHAMSHIRE"&gt;BUCKINGHAMSHIRE&lt;/option&gt;
&lt;option value="BUTESHIRE"&gt;BUTESHIRE&lt;/option&gt;
&lt;option value="CAERNARFONSHIRE"&gt;CAERNARFONSHIRE&lt;/option&gt;
&lt;option value="CAITHNESS"&gt;CAITHNESS&lt;/option&gt;
&lt;option value="CAMBRIDGESHIRE"&gt;CAMBRIDGESHIRE&lt;/option&gt;
&lt;option value="CARDIGANSHIRE"&gt;CARDIGANSHIRE&lt;/option&gt;
&lt;option value="CARLOW"&gt;CARLOW&lt;/option&gt;
&lt;option value="CARMARTHENSHIRE"&gt;CARMARTHENSHIRE&lt;/option&gt;
&lt;option value="CAVAN"&gt;CAVAN&lt;/option&gt;
&lt;option value="CENTRAL"&gt;CENTRAL&lt;/option&gt;
&lt;option value="CEREDIGION"&gt;CEREDIGION&lt;/option&gt;
&lt;option value="CHANNEL ISLANDS"&gt;CHANNEL ISLANDS&lt;/option&gt;
&lt;option value="CHESHIRE"&gt;CHESHIRE&lt;/option&gt;
&lt;option value="CLACKMANNANSHIRE"&gt;CLACKMANNANSHIRE&lt;/option&gt;
&lt;option value="CLARE"&gt;CLARE&lt;/option&gt;
&lt;option value="CLEVELAND"&gt;CLEVELAND&lt;/option&gt;
&lt;option value="CLWYD"&gt;CLWYD&lt;/option&gt;
&lt;option value="CORK"&gt;CORK&lt;/option&gt;
&lt;option value="CORNWALL"&gt;CORNWALL&lt;/option&gt;
&lt;option value="CUMBERLAND"&gt;CUMBERLAND&lt;/option&gt;
&lt;option value="CUMBRIA"&gt;CUMBRIA&lt;/option&gt;
&lt;option value="DENBIGHSHIRE"&gt;DENBIGHSHIRE&lt;/option&gt;
&lt;option value="DERBYSHIRE"&gt;DERBYSHIRE&lt;/option&gt;
&lt;option value="DEVON"&gt;DEVON&lt;/option&gt;
&lt;option value="DONEGAL"&gt;DONEGAL&lt;/option&gt;
&lt;option value="DORSET"&gt;DORSET&lt;/option&gt;
&lt;option value="DOWN"&gt;DOWN&lt;/option&gt;
&lt;option value="DUBLIN"&gt;DUBLIN&lt;/option&gt;
&lt;option value="DUMFRIES &amp;amp; GALLOWAY"&gt;DUMFRIES &amp;amp; GALLOWAY&lt;/option&gt;
&lt;option value="DUMFRIESSHIRE"&gt;DUMFRIESSHIRE&lt;/option&gt;
&lt;option value="DUNBARTONSHIRE"&gt;DUNBARTONSHIRE&lt;/option&gt;
&lt;option value="DURHAM"&gt;DURHAM&lt;/option&gt;
&lt;option value="DYFED"&gt;DYFED&lt;/option&gt;
&lt;option value="EAST LOTHIAN"&gt;EAST LOTHIAN&lt;/option&gt;
&lt;option value="EAST SUSSEX"&gt;EAST SUSSEX&lt;/option&gt;
&lt;option value="ESSEX"&gt;ESSEX&lt;/option&gt;
&lt;option value="FERMANAGH"&gt;FERMANAGH&lt;/option&gt;
&lt;option value="FIFE"&gt;FIFE&lt;/option&gt;
&lt;option value="FLINTSHIRE"&gt;FLINTSHIRE&lt;/option&gt;
&lt;option value="FORFARSHIRE"&gt;FORFARSHIRE&lt;/option&gt;
&lt;option value="GALWAY"&gt;GALWAY&lt;/option&gt;
&lt;option value="GLAMORGANSHIRE"&gt;GLAMORGANSHIRE&lt;/option&gt;
&lt;option value="GLOUCESTERSHIRE"&gt;GLOUCESTERSHIRE&lt;/option&gt;
&lt;option value="GRAMPIAN"&gt;GRAMPIAN&lt;/option&gt;
&lt;option value="GREATER LONDON"&gt;GREATER LONDON&lt;/option&gt;
&lt;option value="GREATER MANCHESTER"&gt;GREATER MANCHESTER&lt;/option&gt;
&lt;option value="GUERNSEY"&gt;GUERNSEY&lt;/option&gt;
&lt;option value="GWENT"&gt;GWENT&lt;/option&gt;
&lt;option value="GWYNEDD"&gt;GWYNEDD&lt;/option&gt;
&lt;option value="HAMPSHIRE"&gt;HAMPSHIRE&lt;/option&gt;
&lt;option value="HEREFORD"&gt;HEREFORD&lt;/option&gt;
&lt;option value="HEREFORD &amp;amp; WORCESTER"&gt;HEREFORD &amp;amp; WORCESTER&lt;/option&gt;
&lt;option value="HERTFORDSHIRE"&gt;HERTFORDSHIRE&lt;/option&gt;
&lt;option value="HIGHLAND"&gt;HIGHLAND&lt;/option&gt;
&lt;option value="HUMBERSIDE"&gt;HUMBERSIDE&lt;/option&gt;
&lt;option value="HUNTINGDONSHIRE"&gt;HUNTINGDONSHIRE&lt;/option&gt;
&lt;option value="INVERNESS-SHIRE"&gt;INVERNESS-SHIRE&lt;/option&gt;
&lt;option value="ISLE OF ANGLESEY"&gt;ISLE OF ANGLESEY&lt;/option&gt;
&lt;option value="ISLE OF MAN"&gt;ISLE OF MAN&lt;/option&gt;
&lt;option value="ISLE OF WIGHT"&gt;ISLE OF WIGHT&lt;/option&gt;
&lt;option value="ISLES OF SCILLY"&gt;ISLES OF SCILLY&lt;/option&gt;
&lt;option value="JERSEY"&gt;JERSEY&lt;/option&gt;
&lt;option value="KENT"&gt;KENT&lt;/option&gt;
&lt;option value="KERRY"&gt;KERRY&lt;/option&gt;
&lt;option value="KILDARE"&gt;KILDARE&lt;/option&gt;
&lt;option value="KILKENNY"&gt;KILKENNY&lt;/option&gt;
&lt;option value="KINCARDINESHIRE"&gt;KINCARDINESHIRE&lt;/option&gt;
&lt;option value="KINROSS-SHIRE"&gt;KINROSS-SHIRE&lt;/option&gt;
&lt;option value="KIRKCUDBRIGHTSHIRE"&gt;KIRKCUDBRIGHTSHIRE&lt;/option&gt;
&lt;option value="LANARKSHIRE"&gt;LANARKSHIRE&lt;/option&gt;
&lt;option value="LANCASHIRE"&gt;LANCASHIRE&lt;/option&gt;
&lt;option value="LAOIS"&gt;LAOIS&lt;/option&gt;
&lt;option value="LEICESTERSHIRE"&gt;LEICESTERSHIRE&lt;/option&gt;
&lt;option value="LEITRIM"&gt;LEITRIM&lt;/option&gt;
&lt;option value="LIMERICK"&gt;LIMERICK&lt;/option&gt;
&lt;option value="LINCOLNSHIRE"&gt;LINCOLNSHIRE&lt;/option&gt;
&lt;option value="LONDONDERRY"&gt;LONDONDERRY&lt;/option&gt;
&lt;option value="LONGFORD"&gt;LONGFORD&lt;/option&gt;
&lt;option value="LOTHIAN"&gt;LOTHIAN&lt;/option&gt;
&lt;option value="LOUTH"&gt;LOUTH&lt;/option&gt;
&lt;option value="MAYO"&gt;MAYO&lt;/option&gt;
&lt;option value="MEATH"&gt;MEATH&lt;/option&gt;
&lt;option value="MERIONETHSHIRE"&gt;MERIONETHSHIRE&lt;/option&gt;
&lt;option value="MERSEYSIDE"&gt;MERSEYSIDE&lt;/option&gt;
&lt;option value="MIDDLESEX"&gt;MIDDLESEX&lt;/option&gt;
&lt;option value="MID GLAMORGAN"&gt;MID GLAMORGAN&lt;/option&gt;
&lt;option value="MIDLOTHIAN"&gt;MIDLOTHIAN&lt;/option&gt;
&lt;option value="MIDLOTHIAN (IN BORDERS REGION)"&gt;MIDLOTHIAN (IN BORDERS REGION)&lt;/option&gt;
&lt;option value="MIDLOTHIAN (IN LOTHIAN REGION)"&gt;MIDLOTHIAN (IN LOTHIAN REGION)&lt;/option&gt;
&lt;option value="MONAGHAN"&gt;MONAGHAN&lt;/option&gt;
&lt;option value="MONMOUTHSHIRE"&gt;MONMOUTHSHIRE&lt;/option&gt;
&lt;option value="MONTGOMERYSHIRE"&gt;MONTGOMERYSHIRE&lt;/option&gt;
&lt;option value="MORAY"&gt;MORAY&lt;/option&gt;
&lt;option value="MORAY (IN GRAMPIAN REGION)"&gt;MORAY (IN GRAMPIAN REGION)&lt;/option&gt;
&lt;option value="MORAY (IN HIGHLAND REGION)"&gt;MORAY (IN HIGHLAND REGION)&lt;/option&gt;
&lt;option value="NAIRNSHIRE"&gt;NAIRNSHIRE&lt;/option&gt;
&lt;option value="NORFOLK"&gt;NORFOLK&lt;/option&gt;
&lt;option value="NORTHAMPTONSHIRE"&gt;NORTHAMPTONSHIRE&lt;/option&gt;
&lt;option value="NORTHUMBERLAND"&gt;NORTHUMBERLAND&lt;/option&gt;
&lt;option value="NORTH YORKSHIRE"&gt;NORTH YORKSHIRE&lt;/option&gt;
&lt;option value="NOTTINGHAMSHIRE"&gt;NOTTINGHAMSHIRE&lt;/option&gt;
&lt;option value="OFFALY"&gt;OFFALY&lt;/option&gt;
&lt;option value="ORKNEY"&gt;ORKNEY&lt;/option&gt;
&lt;option value="OXFORDSHIRE"&gt;OXFORDSHIRE&lt;/option&gt;
&lt;option value="PEEBLESHIRE"&gt;PEEBLESHIRE&lt;/option&gt;
&lt;option value="PEMBROKESHIRE"&gt;PEMBROKESHIRE&lt;/option&gt;
&lt;option value="PERTHSHIRE"&gt;PERTHSHIRE&lt;/option&gt;
&lt;option value="PERTHSHIRE (IN CENTRAL REGION)"&gt;PERTHSHIRE (IN CENTRAL REGION)&lt;/option&gt;
&lt;option value="PERTHSHIRE (IN TAYSIDE REGION)"&gt;PERTHSHIRE (IN TAYSIDE REGION)&lt;/option&gt;
&lt;option value="POWYS"&gt;POWYS&lt;/option&gt;
&lt;option value="POWYS (NORTH)"&gt;POWYS (NORTH)&lt;/option&gt;
&lt;option value="POWYS (SOUTH)"&gt;POWYS (SOUTH)&lt;/option&gt;
&lt;option value="RADNORSHIRE"&gt;RADNORSHIRE&lt;/option&gt;
&lt;option value="RENFREWSHIRE"&gt;RENFREWSHIRE&lt;/option&gt;
&lt;option value="ROSCOMMON"&gt;ROSCOMMON&lt;/option&gt;
&lt;option value="ROSS &amp;amp; CROMARTY"&gt;ROSS &amp;amp; CROMARTY&lt;/option&gt;
&lt;option value="ROXBURGHSHIRE"&gt;ROXBURGHSHIRE&lt;/option&gt;
&lt;option value="RUTLAND"&gt;RUTLAND&lt;/option&gt;
&lt;option value="SARK"&gt;SARK&lt;/option&gt;
&lt;option value="SELKIRKSHIRE"&gt;SELKIRKSHIRE&lt;/option&gt;
&lt;option value="SHETLAND"&gt;SHETLAND&lt;/option&gt;
&lt;option value="SHROPSHIRE"&gt;SHROPSHIRE&lt;/option&gt;
&lt;option value="SLIGO"&gt;SLIGO&lt;/option&gt;
&lt;option value="SOMERSET"&gt;SOMERSET&lt;/option&gt;
&lt;option value="SOUTH GLAMORGAN"&gt;SOUTH GLAMORGAN&lt;/option&gt;
&lt;option value="SOUTH ORKNEYS"&gt;SOUTH ORKNEYS&lt;/option&gt;
&lt;option value="SOUTH SHETLAND"&gt;SOUTH SHETLAND&lt;/option&gt;
&lt;option value="SOUTH YORKSHIRE"&gt;SOUTH YORKSHIRE&lt;/option&gt;
&lt;option value="STAFFORDSHIRE"&gt;STAFFORDSHIRE&lt;/option&gt;
&lt;option value="STIRLING"&gt;STIRLING&lt;/option&gt;
&lt;option value="STIRLING (IN CENTRAL REGION)"&gt;STIRLING (IN CENTRAL REGION)&lt;/option&gt;
&lt;option value="STIRLING (IN STRATHCLYDE REGION)"&gt;STIRLING (IN STRATHCLYDE REGION)&lt;/option&gt;
&lt;option value="STRATHCLYDE"&gt;STRATHCLYDE&lt;/option&gt;
&lt;option value="SUFFOLK"&gt;SUFFOLK&lt;/option&gt;
&lt;option value="SURREY"&gt;SURREY&lt;/option&gt;
&lt;option value="SUSSEX"&gt;SUSSEX&lt;/option&gt;
&lt;option value="SUTHERLAND"&gt;SUTHERLAND&lt;/option&gt;
&lt;option value="TAYSIDE"&gt;TAYSIDE&lt;/option&gt;
&lt;option value="TIPPERARY"&gt;TIPPERARY&lt;/option&gt;
&lt;option value="TYNE &amp;amp; WEAR"&gt;TYNE &amp;amp; WEAR&lt;/option&gt;
&lt;option value="TYRONE"&gt;TYRONE&lt;/option&gt;
&lt;option value="WARWICKSHIRE"&gt;WARWICKSHIRE&lt;/option&gt;
&lt;option value="WATERFORD"&gt;WATERFORD&lt;/option&gt;
&lt;option value="WESTERN ISLES"&gt;WESTERN ISLES&lt;/option&gt;
&lt;option value="WEST GLAMORGAN"&gt;WEST GLAMORGAN&lt;/option&gt;
&lt;option value="WEST LOTHIAN"&gt;WEST LOTHIAN&lt;/option&gt;
&lt;option value="WEST LOTHIAN (IN CENTRAL REGION)"&gt;WEST LOTHIAN (IN CENTRAL REGION)&lt;/option&gt;
&lt;option value="WEST LOTHIAN (IN LOTHIAN REGION)"&gt;WEST LOTHIAN (IN LOTHIAN REGION)&lt;/option&gt;
&lt;option value="WESTMEATH"&gt;WESTMEATH&lt;/option&gt;
&lt;option value="WEST MIDLANDS"&gt;WEST MIDLANDS&lt;/option&gt;
&lt;option value="WESTMORLAND"&gt;WESTMORLAND&lt;/option&gt;
&lt;option value="WEST SUFFOLK"&gt;WEST SUFFOLK&lt;/option&gt;
&lt;option value="WEST SUSSEX"&gt;WEST SUSSEX&lt;/option&gt;
&lt;option value="WEST YORKSHIRE"&gt;WEST YORKSHIRE&lt;/option&gt;
&lt;option value="WEXFORD"&gt;WEXFORD&lt;/option&gt;
&lt;option value="WICKLOW"&gt;WICKLOW&lt;/option&gt;
&lt;option value="WIGTOWNSHIRE"&gt;WIGTOWNSHIRE&lt;/option&gt;
&lt;option value="WILTSHIRE"&gt;WILTSHIRE&lt;/option&gt;
&lt;option value="WORCESTERSHIRE"&gt;WORCESTERSHIRE&lt;/option&gt;
&lt;option value="YORKSHIRE"&gt;YORKSHIRE&lt;/option&gt;
&lt;/select&gt;&lt;input type="submit" value="Search"&gt; &lt;input type="reset" value="Reset"&gt;
&lt;p&gt;&lt;/p&gt;
Show only stations with &lt;a href="https://catalogue.ceda.ac.uk/uuid/dbd451271eb04662beade68da43546e1" target="_blank" title="Midas-open is the open data version of the Met Office Integrated Data Archive System (MIDAS) for land surface station data"&gt;MIDAS Open data&lt;/a&gt; &lt;input name="opendata" title="Only search for stations which produce MIDAS Open data" type="checkbox" value="y"&gt;
&lt;p&gt;&lt;/p&gt;
Open within year range: &lt;input maxlength="4" name="minyear" size="4" type="text"&gt; to: &lt;input maxlength="4" name="maxyear" size="4" type="text"&gt; &lt;b&gt;Or&lt;/b&gt; show current stations only &lt;input name="current" title="Only search for stations which are still operating" type="checkbox" value="y"&gt;&lt;/td&gt;
&lt;/tr&gt;
&lt;/tbody&gt;
&lt;/table&gt;
&lt;/form&gt;
&lt;h3&gt;Display station details&lt;/h3&gt;
&lt;p&gt;To display details for one or more stations, enter the station source ID (src_id) values in the box below. Use spaces or commas to separate multiple values.&lt;/p&gt;
&lt;form action="https://archive2.ceda.ac.uk/cgi-bin/midas_stations/station_details.cgi.py"&gt;
&lt;table class="table"&gt;
&lt;tbody&gt;
&lt;tr&gt;
&lt;td nowrap="nowrap"&gt;&lt;b&gt;Source IDs: &lt;/b&gt; &lt;input name="idstring" size="30" type="text"&gt; &lt;input type="submit" value="Search"&gt; &lt;input type="reset" value="Reset"&gt;&lt;/td&gt;
&lt;/tr&gt;
&lt;/tbody&gt;
&lt;/table&gt;
&lt;/form&gt;</textarea>
        
    </p>
    
    <p style="display:none;">
        <label for="app-0ea73316-5ef1-434a-8584-1bbeb6c22c54">App:</label><br><input type="hidden" name="app" value="pages" class=" charfield" id="app-0ea73316-5ef1-434a-8584-1bbeb6c22c54">
        
    </p>
    
    <p style="display:none;">
        <label for="model-0ea73316-5ef1-434a-8584-1bbeb6c22c54">Model:</label><br><input type="hidden" name="model" value="richtextpage" class=" charfield" id="model-0ea73316-5ef1-434a-8584-1bbeb6c22c54">
        
    </p>
    
    <p style="display:none;">
        <label for="id-0ea73316-5ef1-434a-8584-1bbeb6c22c54">Id:</label><br><input type="hidden" name="id" value="3" class=" charfield" id="id-0ea73316-5ef1-434a-8584-1bbeb6c22c54">
        
    </p>
    
    <p style="display:none;">
        <label for="fields-0ea73316-5ef1-434a-8584-1bbeb6c22c54">Fields:</label><br><input type="hidden" name="fields" value="content" class=" charfield" id="fields-0ea73316-5ef1-434a-8584-1bbeb6c22c54">
        
    </p>
    
    <input type="submit" value="Save" class="btn btn-primary btn-lg">
    <input type="button" value="Cancel" class="btn btn-default btn-lg">
</form>

<div class="editable-original">
<h1>Search for Met Office MIDAS stations</h1>
<h3>Maps</h3>
<p></p>
<p><a href="https://archive2.ceda.ac.uk/cgi-bin/midas_stations/midas_googlemap.cgi">View stations on interactive map</a> &nbsp; &nbsp; Also available as a <a href="google_earth.html">Google Earth</a> download.</p>
<h3>Search for station name</h3>
<p>Finds all station names contain the given string. The string is matched anywhere within the station name and is not case sensitive.</p>
<form action="https://archive2.ceda.ac.uk/cgi-bin/midas_stations/search_by_name.cgi.py">
<table class="table">
<tbody>
<tr>
<td nowrap="nowrap"><b>Search for: </b><input maxlength="40" name="name" size="25" title="Search for string anywhere in station name (no need to use wildcards)" type="text"> <input type="submit" value="Search"> <input type="reset" value="Reset">
<p></p>
Show only stations with <a href="https://catalogue.ceda.ac.uk/uuid/dbd451271eb04662beade68da43546e1" target="_blank" title="Midas-open is the open data version of the Met Office Integrated Data Archive System (MIDAS) for land surface station data">MIDAS Open data</a> <input name="opendata" title="Only search for stations which produce MIDAS Open data" type="checkbox" value="y">
<p></p>
Open within year range: <input maxlength="4" name="minyear" size="4" type="text"> to: <input maxlength="4" name="maxyear" size="4" type="text"> <b>Or</b> show current stations only <input name="current" title="Only search for stations which are still operating" type="checkbox" value="y"></td>
</tr>
</tbody>
</table>
</form>
<h3>Search for stations by postcode</h3>
<p>Finds all stations with postcodes starting with the given string. Enter up to 5 significant characters. For example, "OX", "OX11" or "OX11 5"). Most stations do not have the full postcode recorded, so adding more characters is unlikely to return any matches. See <a href="https://en.wikipedia.org/wiki/File:British_postcode_areas_map.svg">Postcode area map</a> or <a href="http://en.wikipedia.org/wiki/List_of_postal_areas_in_the_United_Kingdom">List of postal areas</a> for more information on postcodes.</p>
<form action="https://archive2.ceda.ac.uk/cgi-bin/midas_stations/search_by_postcode.cgi.py">
<table class="table">
<tbody>
<tr>
<td nowrap="nowrap"><b>Search for: </b> <input maxlength="9" name="postcode" size="9" type="text"> &nbsp; <input type="submit" value="Search"> <input type="reset" value="Reset">
<p></p>
Show only stations with <a href="https://catalogue.ceda.ac.uk/uuid/dbd451271eb04662beade68da43546e1" target="_blank" title="Midas-open is the open data version of the Met Office Integrated Data Archive System (MIDAS) for land surface station data">MIDAS Open data</a> <input name="opendata" title="Only search for stations which produce MIDAS Open data" type="checkbox" value="y">
<p></p>
Open within year range: <input maxlength="4" name="minyear" size="4" type="text"> to: <input maxlength="4" name="maxyear" size="4" type="text"> <b>Or</b> show current stations only <input name="current" title="Only search for stations which are still operating" type="checkbox" value="y"></td>
</tr>
</tbody>
</table>
</form>
<h3>Search for stations by UK county</h3>
<p>Select a county to display all stations with that county. Please note that the county names are the names used by the Met Office and may not reflect the current county divisions within the UK. <a href="traditional_counties_map">Map of traditional counties</a></p>
<form action="https://archive2.ceda.ac.uk/cgi-bin/midas_stations/search_by_county.cgi.py">
<table class="table">
<tbody>
<tr>
<td nowrap="nowrap"><select name="county">
<option value="ABERDEENSHIRE">ABERDEENSHIRE</option>
<option value="ALDERNEY">ALDERNEY</option>
<option value="ANGUS">ANGUS</option>
<option value="ANTRIM">ANTRIM</option>
<option value="ARGYLL (IN HIGHLAND REGION)">ARGYLL (IN HIGHLAND REGION)</option>
<option value="ARGYLL (IN STRATHCLYDE REGION)">ARGYLL (IN STRATHCLYDE REGION)</option>
<option value="ARGYLLSHIRE">ARGYLLSHIRE</option>
<option value="ARMAGH">ARMAGH</option>
<option value="AVON">AVON</option>
<option value="AYRSHIRE">AYRSHIRE</option>
<option value="BANFFSHIRE">BANFFSHIRE</option>
<option value="BEDFORDSHIRE">BEDFORDSHIRE</option>
<option value="BERKSHIRE">BERKSHIRE</option>
<option value="BERWICKSHIRE">BERWICKSHIRE</option>
<option value="BORDERS">BORDERS</option>
<option value="BRECKNOCKSHIRE">BRECKNOCKSHIRE</option>
<option value="BUCKINGHAMSHIRE">BUCKINGHAMSHIRE</option>
<option value="BUTESHIRE">BUTESHIRE</option>
<option value="CAERNARFONSHIRE">CAERNARFONSHIRE</option>
<option value="CAITHNESS">CAITHNESS</option>
<option value="CAMBRIDGESHIRE">CAMBRIDGESHIRE</option>
<option value="CARDIGANSHIRE">CARDIGANSHIRE</option>
<option value="CARLOW">CARLOW</option>
<option value="CARMARTHENSHIRE">CARMARTHENSHIRE</option>
<option value="CAVAN">CAVAN</option>
<option value="CENTRAL">CENTRAL</option>
<option value="CEREDIGION">CEREDIGION</option>
<option value="CHANNEL ISLANDS">CHANNEL ISLANDS</option>
<option value="CHESHIRE">CHESHIRE</option>
<option value="CLACKMANNANSHIRE">CLACKMANNANSHIRE</option>
<option value="CLARE">CLARE</option>
<option value="CLEVELAND">CLEVELAND</option>
<option value="CLWYD">CLWYD</option>
<option value="CORK">CORK</option>
<option value="CORNWALL">CORNWALL</option>
<option value="CUMBERLAND">CUMBERLAND</option>
<option value="CUMBRIA">CUMBRIA</option>
<option value="DENBIGHSHIRE">DENBIGHSHIRE</option>
<option value="DERBYSHIRE">DERBYSHIRE</option>
<option value="DEVON">DEVON</option>
<option value="DONEGAL">DONEGAL</option>
<option value="DORSET">DORSET</option>
<option value="DOWN">DOWN</option>
<option value="DUBLIN">DUBLIN</option>
<option value="DUMFRIES &amp; GALLOWAY">DUMFRIES &amp; GALLOWAY</option>
<option value="DUMFRIESSHIRE">DUMFRIESSHIRE</option>
<option value="DUNBARTONSHIRE">DUNBARTONSHIRE</option>
<option value="DURHAM">DURHAM</option>
<option value="DYFED">DYFED</option>
<option value="EAST LOTHIAN">EAST LOTHIAN</option>
<option value="EAST SUSSEX">EAST SUSSEX</option>
<option value="ESSEX">ESSEX</option>
<option value="FERMANAGH">FERMANAGH</option>
<option value="FIFE">FIFE</option>
<option value="FLINTSHIRE">FLINTSHIRE</option>
<option value="FORFARSHIRE">FORFARSHIRE</option>
<option value="GALWAY">GALWAY</option>
<option value="GLAMORGANSHIRE">GLAMORGANSHIRE</option>
<option value="GLOUCESTERSHIRE">GLOUCESTERSHIRE</option>
<option value="GRAMPIAN">GRAMPIAN</option>
<option value="GREATER LONDON">GREATER LONDON</option>
<option value="GREATER MANCHESTER">GREATER MANCHESTER</option>
<option value="GUERNSEY">GUERNSEY</option>
<option value="GWENT">GWENT</option>
<option value="GWYNEDD">GWYNEDD</option>
<option value="HAMPSHIRE">HAMPSHIRE</option>
<option value="HEREFORD">HEREFORD</option>
<option value="HEREFORD &amp; WORCESTER">HEREFORD &amp; WORCESTER</option>
<option value="HERTFORDSHIRE">HERTFORDSHIRE</option>
<option value="HIGHLAND">HIGHLAND</option>
<option value="HUMBERSIDE">HUMBERSIDE</option>
<option value="HUNTINGDONSHIRE">HUNTINGDONSHIRE</option>
<option value="INVERNESS-SHIRE">INVERNESS-SHIRE</option>
<option value="ISLE OF ANGLESEY">ISLE OF ANGLESEY</option>
<option value="ISLE OF MAN">ISLE OF MAN</option>
<option value="ISLE OF WIGHT">ISLE OF WIGHT</option>
<option value="ISLES OF SCILLY">ISLES OF SCILLY</option>
<option value="JERSEY">JERSEY</option>
<option value="KENT">KENT</option>
<option value="KERRY">KERRY</option>
<option value="KILDARE">KILDARE</option>
<option value="KILKENNY">KILKENNY</option>
<option value="KINCARDINESHIRE">KINCARDINESHIRE</option>
<option value="KINROSS-SHIRE">KINROSS-SHIRE</option>
<option value="KIRKCUDBRIGHTSHIRE">KIRKCUDBRIGHTSHIRE</option>
<option value="LANARKSHIRE">LANARKSHIRE</option>
<option value="LANCASHIRE">LANCASHIRE</option>
<option value="LAOIS">LAOIS</option>
<option value="LEICESTERSHIRE">LEICESTERSHIRE</option>
<option value="LEITRIM">LEITRIM</option>
<option value="LIMERICK">LIMERICK</option>
<option value="LINCOLNSHIRE">LINCOLNSHIRE</option>
<option value="LONDONDERRY">LONDONDERRY</option>
<option value="LONGFORD">LONGFORD</option>
<option value="LOTHIAN">LOTHIAN</option>
<option value="LOUTH">LOUTH</option>
<option value="MAYO">MAYO</option>
<option value="MEATH">MEATH</option>
<option value="MERIONETHSHIRE">MERIONETHSHIRE</option>
<option value="MERSEYSIDE">MERSEYSIDE</option>
<option value="MIDDLESEX">MIDDLESEX</option>
<option value="MID GLAMORGAN">MID GLAMORGAN</option>
<option value="MIDLOTHIAN">MIDLOTHIAN</option>
<option value="MIDLOTHIAN (IN BORDERS REGION)">MIDLOTHIAN (IN BORDERS REGION)</option>
<option value="MIDLOTHIAN (IN LOTHIAN REGION)">MIDLOTHIAN (IN LOTHIAN REGION)</option>
<option value="MONAGHAN">MONAGHAN</option>
<option value="MONMOUTHSHIRE">MONMOUTHSHIRE</option>
<option value="MONTGOMERYSHIRE">MONTGOMERYSHIRE</option>
<option value="MORAY">MORAY</option>
<option value="MORAY (IN GRAMPIAN REGION)">MORAY (IN GRAMPIAN REGION)</option>
<option value="MORAY (IN HIGHLAND REGION)">MORAY (IN HIGHLAND REGION)</option>
<option value="NAIRNSHIRE">NAIRNSHIRE</option>
<option value="NORFOLK">NORFOLK</option>
<option value="NORTHAMPTONSHIRE">NORTHAMPTONSHIRE</option>
<option value="NORTHUMBERLAND">NORTHUMBERLAND</option>
<option value="NORTH YORKSHIRE">NORTH YORKSHIRE</option>
<option value="NOTTINGHAMSHIRE">NOTTINGHAMSHIRE</option>
<option value="OFFALY">OFFALY</option>
<option value="ORKNEY">ORKNEY</option>
<option value="OXFORDSHIRE">OXFORDSHIRE</option>
<option value="PEEBLESHIRE">PEEBLESHIRE</option>
<option value="PEMBROKESHIRE">PEMBROKESHIRE</option>
<option value="PERTHSHIRE">PERTHSHIRE</option>
<option value="PERTHSHIRE (IN CENTRAL REGION)">PERTHSHIRE (IN CENTRAL REGION)</option>
<option value="PERTHSHIRE (IN TAYSIDE REGION)">PERTHSHIRE (IN TAYSIDE REGION)</option>
<option value="POWYS">POWYS</option>
<option value="POWYS (NORTH)">POWYS (NORTH)</option>
<option value="POWYS (SOUTH)">POWYS (SOUTH)</option>
<option value="RADNORSHIRE">RADNORSHIRE</option>
<option value="RENFREWSHIRE">RENFREWSHIRE</option>
<option value="ROSCOMMON">ROSCOMMON</option>
<option value="ROSS &amp; CROMARTY">ROSS &amp; CROMARTY</option>
<option value="ROXBURGHSHIRE">ROXBURGHSHIRE</option>
<option value="RUTLAND">RUTLAND</option>
<option value="SARK">SARK</option>
<option value="SELKIRKSHIRE">SELKIRKSHIRE</option>
<option value="SHETLAND">SHETLAND</option>
<option value="SHROPSHIRE">SHROPSHIRE</option>
<option value="SLIGO">SLIGO</option>
<option value="SOMERSET">SOMERSET</option>
<option value="SOUTH GLAMORGAN">SOUTH GLAMORGAN</option>
<option value="SOUTH ORKNEYS">SOUTH ORKNEYS</option>
<option value="SOUTH SHETLAND">SOUTH SHETLAND</option>
<option value="SOUTH YORKSHIRE">SOUTH YORKSHIRE</option>
<option value="STAFFORDSHIRE">STAFFORDSHIRE</option>
<option value="STIRLING">STIRLING</option>
<option value="STIRLING (IN CENTRAL REGION)">STIRLING (IN CENTRAL REGION)</option>
<option value="STIRLING (IN STRATHCLYDE REGION)">STIRLING (IN STRATHCLYDE REGION)</option>
<option value="STRATHCLYDE">STRATHCLYDE</option>
<option value="SUFFOLK">SUFFOLK</option>
<option value="SURREY">SURREY</option>
<option value="SUSSEX">SUSSEX</option>
<option value="SUTHERLAND">SUTHERLAND</option>
<option value="TAYSIDE">TAYSIDE</option>
<option value="TIPPERARY">TIPPERARY</option>
<option value="TYNE &amp; WEAR">TYNE &amp; WEAR</option>
<option value="TYRONE">TYRONE</option>
<option value="WARWICKSHIRE">WARWICKSHIRE</option>
<option value="WATERFORD">WATERFORD</option>
<option value="WESTERN ISLES">WESTERN ISLES</option>
<option value="WEST GLAMORGAN">WEST GLAMORGAN</option>
<option value="WEST LOTHIAN">WEST LOTHIAN</option>
<option value="WEST LOTHIAN (IN CENTRAL REGION)">WEST LOTHIAN (IN CENTRAL REGION)</option>
<option value="WEST LOTHIAN (IN LOTHIAN REGION)">WEST LOTHIAN (IN LOTHIAN REGION)</option>
<option value="WESTMEATH">WESTMEATH</option>
<option value="WEST MIDLANDS">WEST MIDLANDS</option>
<option value="WESTMORLAND">WESTMORLAND</option>
<option value="WEST SUFFOLK">WEST SUFFOLK</option>
<option value="WEST SUSSEX">WEST SUSSEX</option>
<option value="WEST YORKSHIRE">WEST YORKSHIRE</option>
<option value="WEXFORD">WEXFORD</option>
<option value="WICKLOW">WICKLOW</option>
<option value="WIGTOWNSHIRE">WIGTOWNSHIRE</option>
<option value="WILTSHIRE">WILTSHIRE</option>
<option value="WORCESTERSHIRE">WORCESTERSHIRE</option>
<option value="YORKSHIRE">YORKSHIRE</option>
</select><input type="submit" value="Search"> <input type="reset" value="Reset">
<p></p>
Show only stations with <a href="https://catalogue.ceda.ac.uk/uuid/dbd451271eb04662beade68da43546e1" target="_blank" title="Midas-open is the open data version of the Met Office Integrated Data Archive System (MIDAS) for land surface station data">MIDAS Open data</a> <input name="opendata" title="Only search for stations which produce MIDAS Open data" type="checkbox" value="y">
<p></p>
Open within year range: <input maxlength="4" name="minyear" size="4" type="text"> to: <input maxlength="4" name="maxyear" size="4" type="text"> <b>Or</b> show current stations only <input name="current" title="Only search for stations which are still operating" type="checkbox" value="y"></td>
</tr>
</tbody>
</table>
</form>
<h3>Display station details</h3>
<p>To display details for one or more stations, enter the station source ID (src_id) values in the box below. Use spaces or commas to separate multiple values.</p>
<form action="/cgi-bin/midas_stations/station_details.cgi.py">
<table class="table">
<tbody>
<tr>
<td nowrap="nowrap"><b>Source IDs: </b> <input name="idstring" size="30" type="text"> <input type="submit" value="Search"> <input type="reset" value="Reset"></td>
</tr>
</tbody>
</table>
</form>
</div>

<a style="visibility:hidden;" class="editable-link" href="#" rel="#0ea73316-5ef1-434a-8584-1bbeb6c22c54">Edit</a>

<div style="visibility:hidden;" class="editable-highlight"></div>

            </div>
        </div>










    </div>
