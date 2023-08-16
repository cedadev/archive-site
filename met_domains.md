---
layout: base_ceda
permalink: midas_stations/met_domains
---





{% include breadcrumbs.html %}


Met Office MIDAS data - Message Types
=====================================

It is convenient to distinguish between:

* an observation, a group of one or more meteorological elements, plus some location and time information; other data items are added to an observation before it is encoded into a message.
* a message, meteorological information encoded into a pre-defined format for exchange between meteorological centres
* a report, some form of summary of (meteorological) data.

Data contained in messages and reports are structured to facilitate the extraction of selected data from the archive, the selection being based on location, time and meteorological element (where an element is a single meteorological variable such as wind speed, cloud cover or relative humidity). The tables do not store the incoming reports and data files, just the information held by them. (The tables do hold information on how the data were received i.e. met domain or message type.)

Some reports are automatically and routinely ingested into the database. Others only become available on an intermittent basis and are processed accordingly.

| Message type | Description | Available in MIDAS | Available elsewhere in BADC |
| --- | --- | --- | --- |
| [AWSDLY](http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_8d6e25b0-d732-11e1-b519-00163e251233) | Daily values from non-standard AWS | Yes | -   |
| [AWSHRLY](http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_8d6e25b0-d732-11e1-b519-00163e251233) | Hourly values from non-standard AWS | Yes | -   |
| AWSRADT/[ESAWRADT](http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_cdbabfae-d7c6-11e1-a28c-00163e251233) | Hourly radiation values from AWS/ESAWS | Yes | -   |
| AWSSOIL/[ESAWSOIL](http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_f6aa543e-d734-11e1-979f-00163e251233) | Soil temperatures from AWS/ESAWS | Yes | -   |
| AWSWIND/[ESAWWIND](http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_396aee06-d72f-11e1-b536-00163e251233) | Wind observations from AWS/ESAWS | Yes | -   |
| BATHY | Elements from FM 63-IX BATHY message | -   | -   |
| BUOY | Elements from FM 18-X BUOY message | -   | -   |
| CARLOS | Monthly & annual climatological averages,calculated by NCIC | Yes | -   |
| CARLOSEX | This domain constrains met\_element values in the Carlos Station\_Exceedence table | -   | -   |
| CAWS | Hourly values from non-standard AWS | -   | -   |
| [CHECK](http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_9ee916a6-d732-11e1-b950-00163e251233) | Check readings | -   | -   |
| CLM-UAN | CLIMAT upper air normals | Yes | -   |
| CLMSN | Monthly & annual climatological averages, & check values for sfc CLIMAT messages | Yes | -   |
| CLMSPN | Monthly & annual precipitation averages, & check values for sfc CLIMAT messages | Yes | -   |
| CLMULN | CLIMAT u/a standard isobaric surface check values for a month & stn | Yes | -   |
| CLMUML | Elements from CLIMAT u/a messages at a standard isobaric surface | Yes | -   |
| CLMUMR | Elements from CLIMAT u/a messages at ground level | Yes | -   |
| CLMURN | Long period monthly surface averages for a CLIMAT upper air stn | Yes | -   |
| CLM71 | Monthly & annual climatological averages, & check values for sfc CLIMAT | Yes | -   |
| CLM71-06 | Elements from FM 71-VI CLIMAT message | Yes | -   |
| CLM71-11 | Elements from FM 71-XI CLIMAT message, post 1994 | Yes | -   |
| CLM72SHP | Elements from FM 72-VI CLIMAT SHIP message | -   | -   |
| CLM75TMP | Elements from FM 75/6-VI CLIMAT TEMP/SHIP messages | Yes | -   |
| CURRENT | Directions and speeds of marine currents | -   | -   |
| DLY3208 | Elements from Metform 3208 - Monthly Return of Daily Obs | Yes | -   |
| [DRADR35](http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_9df306be-d7c6-11e1-bc03-00163e251233) | MetO1 Form R35 elements - Dly Totals of Radiation/Sunshine | Yes | -   |
| DRIFTER | Elements from FM 18-X Ext DRIFTER message from drifting buoys. | -   | -   |
| GLBLWXOB | GLBL\_WX\_OB table. 3-hrly synoptic reports from overseas stations. | Yes | -   |
| [HCM](http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_24917ec0-d72d-11e1-be76-00163e251233) | Elements from HCM reports | Yes | -   |
| [HSUN3445](http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_e373db06-d734-11e1-ac07-00163e251233) | Elements from Metform 3445 - Hourly values of Sunshine Duration | -   | -   |
| [HWNDAUTO](http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_02847268-d72f-11e1-b0e6-00163e251233) | Elements from automatic wind recording devices | -   | -   |
| [HWND6910](http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_97a63a6c-d72e-11e1-86de-00163e251233) | Elements from Metform 6910 - Analysis of Anemograms | -   | -   |
| MARCUR | MARINE-CURRENT table. Directions and speeds of marine currents | -   | -   |
| MAROB | MARINE-OB table. Elements from marine messages | -   | -   |
| [METAR](http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_e71e3bf0-d7c2-11e1-b950-00163e251233) | Elements from full FM 15-V METAR message | Yes | -   |
| [MODLERAD](http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_8dbc7f6e-d7c6-11e1-a7d5-00163e251233) | Hourly radiation values from MODLE | Yes | -   |
| MOSFCELM | Monthly climatological values from CLM-71 messages or derived from ob values | -   | -   |
| MOSFCREC | Mo\_Sfc\_Rec table. Header for monthly surface climatological values | -   | -   |
| [NCM](http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_5ffa5202-d732-11e1-b950-00163e251233) | Elements from NCM reports | Yes | -   |
| PLAT | Elements from PLAT marine messages | -   | -   |
| RADTOB | RADT-OB table. Radiation values currently being reported | Yes | -   |
| RIG | Surface weather elements from moveable rigs | -   | -   |
| RNDYOB | RAIN-DRNL-OB table. Daily rainfall values | Yes | -   |
| RNHROB | RAIN-HRLY-OB table. Hourly rainfall observations | Yes | -   |
| RNSHRLY | RAIN-SUBHRLY-OB table. Tip values from automatic rain recorders | Yes | -   |
| RUNWAY | Runway measurements, e.g. visual range | -   | -   |
| SHIP | Marine surface obs, code type is 'FM 13-XI SHIP'. No 8-groups | -   | -   |
| SHIP-AUX | Marine surface obs, abbreviated list of elements, e.g. MARID, from trawlers, etc | -   | -   |
| SHIP-LV | Marine surface obs, from Light Vessel messages | -   | -   |
| SHIP-NVY | Marine surface obs, code type is 'SHIP', 8-groups, from Navy ships | -   | -   |
| SHIP-OWS | Marine surface obs, code type is 'SHIP', 8-groups, from Ocean Weather Ships | -   | -   |
| SOILOB | Daily & hourly soil temperatures at 5, 10, 20, 30, 50 & 100cm | Yes | -   |
| [SREW](http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_b06e4d56-d732-11e1-b7de-00163e251233) | Hourly Rainfall values | Yes | -   |
| [SSER](http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_c21bdf28-d732-11e1-b3c6-00163e251233) | Rainfall values from SSER loggers | -   | -   |
| [SYNOP](http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_92bff898-d72a-11e1-8550-00163e251233) | Elements from full FM 12-VII SYNOP message | Yes | -   |
| TDYOB | TEMP-DRNL-OB table. Daily temperature extremes | Yes | -   |
| TEMPMNSL | Bare soil minimum temperatures | Yes | -   |
| TESAC | Elements from FM 64-IX TESAC message | -   | -   |
| TRACKOB | FM62-VIII TRACKOB. Values of sea temp, salinity, current speed & direction | -   | -   |
| UAPLT | Upper air pilot wind message, e.g. FM 32-PILOT | -   | [Radiosonde](http://badc.nerc.ac.uk/data/radiosglobe/) |
| UAPLTSHP | Upper air pilot wind message from ship, e.g. FM 33-V | -   | [Radiosonde](http://badc.nerc.ac.uk/data/radiosglobe/) |
| PILOT SHIP | -   | -   | [Radiosonde](http://badc.nerc.ac.uk/data/radiosglobe/) |
| UASNDG | UA_SOUNDING table. Non-repeating elements of an u/a ascent, e.g. sonde type | -   | -   |
| UASNDGPT | UA\_SOUNDING\_POINT table. Repeating values of an upper air ascent | -   | -   |
| UATMP | Upper air temp message, e.g. FM 35-V TEMP | -   | [Radiosonde](http://badc.nerc.ac.uk/data/radiosglobe/) |
| UATMPSHP | Upper air temp message from ship, e.g. FM 36-V TEMP SHIP | -   | [Radiosonde](http://badc.nerc.ac.uk/data/radiosglobe/) |
| [WADRAIN](http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_45570aee-d732-11e1-b536-00163e251233) | Daily rainfall values from Water Authorities | Yes | -   |
| [WAHRAIN](http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_d1cbd004-d732-11e1-ac07-00163e251233) | Hourly rainfall values from Water Authorities | Yes | -   |
| [WAMRAIN](http://badc.nerc.ac.uk/view/badc.nerc.ac.uk__ATOM__OBS_754a21fa-d732-11e1-b5aa-00163e251233) | Monthly rainfall values from Water Authorities | Yes | -   |
| WINDMEAN | WIND-MEAN-OB table. Wind parameters measured during one or more hours | Yes | -   |
| WX_EVT | Weather event. Defines the list of weather events for CARLOS | -   | -   |
| WXDYOB | WEATHER-DRNL-OB table. Daily weather values | Yes | -   |
| WXHROB | WEATHER-HRLY-OB table. Hourly weather values | Yes | -   |


