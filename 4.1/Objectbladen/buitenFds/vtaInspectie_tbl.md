﻿## AREAALDATA.vtaInspectie_tbl

$ Feature dataset: -


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt
* __Geometrie:__ Geen
* __Definitie:__ Wettelijk verplichte inspectie van de veiligheid van bomen

***

|KOLOM                               |TYPE                |DEFINITIE|
|------                              |----                |-----    |
|VERWERKINGSSTATUS                   |String(255,0,0)     |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|DATUM                               |Date(8,0,0)         |PNH; Datum Inspectie; Nullable: True|
|INSPECTEUR                          |String(255,0,0)     |PNH; Naam van de Inspecteur; Nullable: True; Default: None|
|OPMERKING                           |String(3000,0,0)    |PNH; Extra toelichting; Nullable: True; Default: None|
|OPMERKING2                          |String(3000,0,0)    |PNH; Extra toelichting m.b.t. kroonschade etc; Nullable: True; Default: None|
|VTA_GEBREK                          |String(255,0,0)     |PNH; Betreft visueel waarneembare kenmerken die (mogelijk) een negatieve invloed hebben op de boomveiligheid; Nullable: True; Default: None|
|VTA_HERKEURING                      |String(255,0,0)     |PNH; Gewenst moment of termijn van de volgende boomveiligheidscontrole; keuzelijst [VTA_HERKEURING]; Nullable: True; Default: None|
|VTA_NADER_TECHN_ONDERZOEK           |String(255,0,0)     |PNH; Uitvoeren van Nader Technisch Onderzoek door bijv. de inzet van specialistische meetapparatuur of onderzoek op hoogte [VTA_NTO]; Nullable: True; Default: None|
|VTA_FLORA                           |String(255,0,0)     |PNH; Aanwezigheid nesten, vleermuizen e.d.; Nullable: True; Default: None|
|VTA_URGENTIE_NTO                    |String(255,0,0)     |PNH; Gewenst moment of termijn van de NTO (e.e.a. houdt verband met de aard en omvang van de geconstateerde gebreken en de standplaats) [VTA_NTO_URGENTIE]; Nullable: True; Default: None|
|VTA_RISICO                          |String(255,0,0)     |PNH; Klasse van het risico wat een gebrek met zich mee kan brengen; keuzelijst [VTA_RISICO]; Nullable: True; Default: None|
|BOOM                                |String(255,0,0)     |PNH; FK naar vegetatieObject_p; Nullable: True; Default: None|
|IDENTIFICATIE                       |String(255,0,0)     |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None|
|OBJECTID                            |OID(38,0,0)         |PNH; Interne ID ArcGIS; Nullable: False|
|GLOBALID                            |GlobalID(38,0,0)    |PNH; Global Unique Identifier; Nullable: False|
|GISIB_ID                            |Integer(0,10,0)     |PNH; ID beheer openbare ruimte (GISIB); Nullable: True|
|DATALEVERANCIER                     |String(255,0,0)     |PNH; Leverancier van de data; Nullable: True; Default: None|
|AD_ID                               |String(255,0,0)     |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; Nullable: False; Default: None|
|OBJECTBEGINTIJD                     |Date(8,0,0)         |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)         |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|CREATED_USER                        |String(255,0,0)     |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)         |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)      |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)         |PNH; Datum van de laatste mutatie; Nullable: True|

***
