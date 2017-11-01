## AREAALDATA.vtaInspectie_tbl

$ Feature dataset: -


* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt
* __Geometrie:__ Geen
* __Definitie:__ Wettelijk verplichte inspectie van de veiligheid van bomen

***

|KOLOM                               |TYPE              |DEFINITIE|
|------                              |----              |-----    |
|VERWERKINGSSTATUS                   |String(255,0,0)    |Status van de gegevens, keuzelijst [VERWERKINGSSTATUS] - Nullable: False Default: Nieuw|
|DATUM                               |Date(8,0,0)         |Datum Inspectie - Nullable: True|
|INSPECTEUR                          |String(255,0,0)     |Naam van de Inspecteur - Nullable: True Default: None|
|OPMERKING                           |String(3000,0,0)    |Extra toelichting - Nullable: True Default: None|
|OPMERKING2                          |String(3000,0,0)    |Extra toelichting m.b.t. kroonschade etc - Nullable: True Default: None|
|VTA_GEBREK                          |String(255,0,0)     |Betreft visueel waarneembare kenmerken die (mogelijk) een negatieve invloed hebben op de boomveiligheid - Nullable: True Default: None|
|VTA_HERKEURING                      |String(255,0,0)     |Gewenst moment of termijn van de volgende boomveiligheidscontrole [VTA_HERKEURING] - Nullable: True Default: None|
|VTA_NADER_TECHN_ONDERZOEK           |String(255,0,0)     |Uitvoeren van Nader Technisch Onderzoek door bijv. de inzet van specialistische meetapparatuur of onderzoek op hoogte [VTA_NTO] - Nullable: True Default: None|
|VTA_FLORA                           |String(255,0,0)     |Aanwezigheid nesten, vleermuizen e.d. - Nullable: True Default: None|
|VTA_URGENTIE_NTO                    |String(255,0,0)     |Gewenst moment of termijn van de NTO (e.e.a. houdt verband met de aard en omvang van de geconstateerde gebreken en de standplaats) [VTA_NTO_URGENTIE] - Nullable: True Default: None|
|VTA_RISICO                          |String(255,0,0)     |Klasse van het risico wat een gebrek met zich mee kan brengen  [VTA_RISICO] - Nullable: True Default: None|
|BOOM                                |String(255,0,0)     |FK naar vegetatieObject_p - Nullable: True Default: None|
|IDENTIFICATIE                       |String(255,0,0)      |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|OBJECTID                            |OID(38,0,0)        |Interne ID ArcGIS - Nullable: False|
|GLOBALID                            |GlobalID(38,0,0)   |Global Unique Identifier - Nullable: False|
|GISIB_ID                            |Integer(0,10,0)    |ID beheer openbare ruimte (GISIB) - Nullable: True|
|AD_ID                               |String(255,0,0)    |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]' - Nullable: False Default: None|
|OBJECTBEGINTIJD                     |Date(8,0,0)        |Datum waarop het object bij de bronhouder is ontstaan - Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)        |Datum waarop het object bij de bronhouder niet meer geldig is - Nullable: True|
|CREATED_USER                        |String(255,0,0)    |Naam van gebruiker die de rij heeft aangemaakt - Nullable: True Default: None|
|CREATED_DATE                        |Date(8,0,0)        |Aanmaakdatum - Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)     |Naam van gebruiker die de laatste mutatie heeft doorgevoerd - Nullable: True Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)        |Datum van de laatste mutatie - Nullable: True|

***
