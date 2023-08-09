---
layout: base_ceda
permalink: midas_stations/met_domains
---

<div class="container">

<ol class="breadcrumb">
<li class="breadcrumb-item" id="breadcrumb-menu-home"><a href="/">Home</a></li><li class="breadcrumb-item" id="breadcrumb-menu-midas_stations-met_domains">Met Office MIDAS data - Message Types</li>
</ol>


<div class="row">
<div class="col-md-12">



<form style="display:none;" class="editable-form" method="post" action="/edit/" id="d07ad239-2af6-432b-bf3f-a68525bb62eb">
    <input type="hidden" name="csrfmiddlewaretoken" value="fn1GMouZH7BxyTCtMhRaAcJiutPzrWJETksTtSom5Vx5scVHrykKnAMqLk0BoutU">
    
<p>
<label for="content-d07ad239-2af6-432b-bf3f-a68525bb62eb">Content:</label><br>
        
</p>
    
<p style="display:none;">
<label for="app-d07ad239-2af6-432b-bf3f-a68525bb62eb">App:</label><br><input type="hidden" name="app" value="pages" class=" charfield" id="app-d07ad239-2af6-432b-bf3f-a68525bb62eb">
        
</p>
    
<p style="display:none;">
<label for="model-d07ad239-2af6-432b-bf3f-a68525bb62eb">Model:</label><br><input type="hidden" name="model" value="richtextpage" class=" charfield" id="model-d07ad239-2af6-432b-bf3f-a68525bb62eb">
        
</p>
    
<p style="display:none;">
<label for="id-d07ad239-2af6-432b-bf3f-a68525bb62eb">Id:</label><br><input type="hidden" name="id" value="8" class=" charfield" id="id-d07ad239-2af6-432b-bf3f-a68525bb62eb">
        
</p>
    
<p style="display:none;">
<label for="fields-d07ad239-2af6-432b-bf3f-a68525bb62eb">Fields:</label><br><input type="hidden" name="fields" value="content" class=" charfield" id="fields-d07ad239-2af6-432b-bf3f-a68525bb62eb">
        
</p>
    
<input type="submit" value="Save" class="btn btn-primary btn-lg">
<input type="button" value="Cancel" class="btn btn-default btn-lg">
</form>

<div class="editable-original">
<h1>Met Office MIDAS data - Message Types</h1>
<p><span>It is convenient to distinguish between:</span></p>
<ul>
<li>an observation, a group of one or more meteorological elements, plus some location and time information; other data items are added to an observation before it is encoded into a message.</li>
<li>a message, meteorological information encoded into a pre-defined format for exchange between meteorological centres</li>
<li>a report, some form of summary of (meteorological) data.</li>
</ul>
<p>Data contained in messages and reports are structured to facilitate the extraction of selected data from the archive, the selection being based on location, time and meteorological element (where an element is a single meteorological variable such as wind speed, cloud cover or relative humidity). The tables do not store the incoming reports and data files, just the information held by them. (The tables do hold information on how the data were received i.e. met domain or message type.)</p>
<p>Some reports are automatically and routinely ingested into the database. Others only become available on an intermittent basis and are processed accordingly.</p>
<table border="" cellpadding="5">
<tbody>
<tr>
<th>Message type</th>
<th>Description</th>
<th>Available in MIDAS</th>
<th>Available elsewhere in BADC</th>
</tr>
<tr>
<td><a href="http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_8d6e25b0-d732-11e1-b519-00163e251233">AWSDLY</a></td>
<td>Daily values from non-standard AWS</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td><a href="http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_8d6e25b0-d732-11e1-b519-00163e251233">AWSHRLY</a></td>
<td>Hourly values from non-standard AWS</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>AWSRADT/<a href="http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_cdbabfae-d7c6-11e1-a28c-00163e251233">ESAWRADT</a></td>
<td>Hourly radiation values from AWS/ESAWS</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>AWSSOIL/<a href="http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_f6aa543e-d734-11e1-979f-00163e251233">ESAWSOIL</a></td>
<td>Soil temperatures from AWS/ESAWS</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>AWSWIND/<a href="http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_396aee06-d72f-11e1-b536-00163e251233">ESAWWIND</a></td>
<td>Wind observations from AWS/ESAWS</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>BATHY</td>
<td>Elements from FM 63-IX BATHY message</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>BUOY</td>
<td>Elements from FM 18-X BUOY message</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>CARLOS</td>
<td>Monthly &amp; annual climatological averages,calculated by NCIC</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>CARLOSEX</td>
<td>This domain constrains met_element values in the Carlos Station_Exceedence table</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>CAWS</td>
<td>Hourly values from non-standard AWS</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td><a href="http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_9ee916a6-d732-11e1-b950-00163e251233">CHECK</a></td>
<td>Check readings</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>CLM-UAN</td>
<td>CLIMAT upper air normals</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>CLMSN</td>
<td>Monthly &amp; annual climatological averages, &amp; check values for sfc CLIMAT messages</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>CLMSPN</td>
<td>Monthly &amp; annual precipitation averages, &amp; check values for sfc CLIMAT messages</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>CLMULN</td>
<td>CLIMAT u/a standard isobaric surface check values for a month &amp; stn</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>CLMUML</td>
<td>Elements from CLIMAT u/a messages at a standard isobaric surface</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>CLMUMR</td>
<td>Elements from CLIMAT u/a messages at ground level</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>CLMURN</td>
<td>Long period monthly surface averages for a CLIMAT upper air stn</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>CLM71</td>
<td>Monthly &amp; annual climatological averages, &amp; check values for sfc CLIMAT</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>CLM71-06</td>
<td>Elements from FM 71-VI CLIMAT message</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>CLM71-11</td>
<td>Elements from FM 71-XI CLIMAT message, post 1994</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>CLM72SHP</td>
<td>Elements from FM 72-VI CLIMAT SHIP message</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>CLM75TMP</td>
<td>Elements from FM 75/6-VI CLIMAT TEMP/SHIP messages</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>CURRENT</td>
<td>Directions and speeds of marine currents</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>DLY3208</td>
<td>Elements from Metform 3208 - Monthly Return of Daily Obs</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td><a href="http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_9df306be-d7c6-11e1-bc03-00163e251233">DRADR35</a></td>
<td>MetO1 Form R35 elements - Dly Totals of Radiation/Sunshine</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>DRIFTER</td>
<td>Elements from FM 18-X Ext DRIFTER message from drifting buoys.</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>GLBLWXOB</td>
<td>GLBL_WX_OB table. 3-hrly synoptic reports from overseas stations.</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td><a href="http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_24917ec0-d72d-11e1-be76-00163e251233">HCM</a></td>
<td>Elements from HCM reports</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td><a href="http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_e373db06-d734-11e1-ac07-00163e251233">HSUN3445</a></td>
<td>Elements from Metform 3445 - Hourly values of Sunshine Duration</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td><a href="http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_02847268-d72f-11e1-b0e6-00163e251233">HWNDAUTO</a></td>
<td>Elements from automatic wind recording devices</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td><a href="http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_97a63a6c-d72e-11e1-86de-00163e251233">HWND6910</a></td>
<td>Elements from Metform 6910 - Analysis of Anemograms</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>MARCUR</td>
<td>MARINE-CURRENT table. Directions and speeds of marine currents</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>MAROB</td>
<td>MARINE-OB table. Elements from marine messages</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td><a href="http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_e71e3bf0-d7c2-11e1-b950-00163e251233">METAR</a></td>
<td>Elements from full FM 15-V METAR message</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td><a href="http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_8dbc7f6e-d7c6-11e1-a7d5-00163e251233">MODLERAD</a></td>
<td>Hourly radiation values from MODLE</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>MOSFCELM</td>
<td>Monthly climatological values from CLM-71 messages or derived from ob values</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>MOSFCREC</td>
<td>Mo_Sfc_Rec table. Header for monthly surface climatological values</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td><a href="http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_5ffa5202-d732-11e1-b950-00163e251233">NCM</a></td>
<td>Elements from NCM reports</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>PLAT</td>
<td>Elements from PLAT marine messages</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>RADTOB</td>
<td>RADT-OB table. Radiation values currently being reported</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>RIG</td>
<td>Surface weather elements from moveable rigs</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>RNDYOB</td>
<td>RAIN-DRNL-OB table. Daily rainfall values</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>RNHROB</td>
<td>RAIN-HRLY-OB table. Hourly rainfall observations</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>RNSHRLY</td>
<td>RAIN-SUBHRLY-OB table. Tip values from automatic rain recorders</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>RUNWAY</td>
<td>Runway measurements, e.g. visual range</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>SHIP</td>
<td>Marine surface obs, code type is 'FM 13-XI SHIP'. No 8-groups</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>SHIP-AUX</td>
<td>Marine surface obs, abbreviated list of elements, e.g. MARID, from trawlers, etc</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>SHIP-LV</td>
<td>Marine surface obs, from Light Vessel messages</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>SHIP-NVY</td>
<td>Marine surface obs, code type is 'SHIP', 8-groups, from Navy ships</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>SHIP-OWS</td>
<td>Marine surface obs, code type is 'SHIP', 8-groups, from Ocean Weather Ships</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>SOILOB</td>
<td>Daily &amp; hourly soil temperatures at 5, 10, 20, 30, 50 &amp; 100cm</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td><a href="http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_b06e4d56-d732-11e1-b7de-00163e251233">SREW</a></td>
<td>Hourly Rainfall values</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td><a href="http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_c21bdf28-d732-11e1-b3c6-00163e251233">SSER</a></td>
<td>Rainfall values from SSER loggers</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td><a href="http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_92bff898-d72a-11e1-8550-00163e251233">SYNOP</a></td>
<td>Elements from full FM 12-VII SYNOP message</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>TDYOB</td>
<td>TEMP-DRNL-OB table. Daily temperature extremes</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>TEMPMNSL</td>
<td>Bare soil minimum temperatures</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>TESAC</td>
<td>Elements from FM 64-IX TESAC message</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>TRACKOB</td>
<td>FM62-VIII TRACKOB. Values of sea temp, salinity, current speed &amp; direction</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>UAPLT</td>
<td>Upper air pilot wind message, e.g. FM 32-PILOT</td>
<td>-</td>
<td><a href="http://badc.nerc.ac.uk/data/radiosglobe/">Radiosonde</a></td>
</tr>
<tr>
<td>UAPLTSHP</td>
<td>Upper air pilot wind message from ship, e.g. FM 33-V</td>
<td>-</td>
<td><a href="http://badc.nerc.ac.uk/data/radiosglobe/">Radiosonde</a></td>
</tr>
<tr>
<td>PILOT SHIP</td>
<td>-</td>
<td>-</td>
<td><a href="http://badc.nerc.ac.uk/data/radiosglobe/">Radiosonde</a></td>
</tr>
<tr>
<td>UASNDG</td>
<td>UA_SOUNDING table. Non-repeating elements of an u/a ascent, e.g. sonde type</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>UASNDGPT</td>
<td>UA_SOUNDING_POINT table. Repeating values of an upper air ascent</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>UATMP</td>
<td>Upper air temp message, e.g. FM 35-V TEMP</td>
<td>-</td>
<td><a href="http://badc.nerc.ac.uk/data/radiosglobe/">Radiosonde</a></td>
</tr>
<tr>
<td>UATMPSHP</td>
<td>Upper air temp message from ship, e.g. FM 36-V TEMP SHIP</td>
<td>-</td>
<td><a href="http://badc.nerc.ac.uk/data/radiosglobe/">Radiosonde</a></td>
</tr>
<tr>
<td><a href="http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_45570aee-d732-11e1-b536-00163e251233">WADRAIN</a></td>
<td>Daily rainfall values from Water Authorities</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td><a href="http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_d1cbd004-d732-11e1-ac07-00163e251233">WAHRAIN</a></td>
<td>Hourly rainfall values from Water Authorities</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td><a href="http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_754a21fa-d732-11e1-b5aa-00163e251233">WAMRAIN</a></td>
<td>Monthly rainfall values from Water Authorities</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>WINDMEAN</td>
<td>WIND-MEAN-OB table. Wind parameters measured during one or more hours</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>WX_EVT</td>
<td>Weather event. Defines the list of weather events for CARLOS</td>
<td>-</td>
<td>-</td>
</tr>
<tr>
<td>WXDYOB</td>
<td>WEATHER-DRNL-OB table. Daily weather values</td>
<td>Yes</td>
<td>-</td>
</tr>
<tr>
<td>WXHROB</td>
<td>WEATHER-HRLY-OB table. Hourly weather values</td>
<td>Yes</td>
<td>-</td>
</tr>
</tbody>
</table>
</div>

<a style="visibility:hidden;" class="editable-link" href="#" rel="#d07ad239-2af6-432b-bf3f-a68525bb62eb">Edit</a>

<div style="visibility:hidden;" class="editable-highlight"></div>

</div>


