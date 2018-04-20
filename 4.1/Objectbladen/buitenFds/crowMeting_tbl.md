## AREAALDATA.crowMeting_tbl

*Feature dataset: -*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt
* __Geometrie:__ Geen
* __Definitie:__ Een inspectie geeft een momentopname weer hoe een PNH wegvakonderdeel er op dat moment bijligt. De CROW norm wordt gebruikt. Het object Meting is bedoelt om de Metingen van een bepaalt wegvakonderdeel vast te leggen. Metingen zijn: langsonvlakheid, stroefheid, zetting, spoorvorming, comfortindex

***

|KOLOM                               |TYPE                |DEFINITIE|
|------                              |----                |-----    |
|VERWERKINGSSTATUS                   |String(255,0,0)     |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|METING_WAARDE                       |Float(0,10,4)       |PNH; Waarde van de Meting; Nullable: True|
|METING_DATUM                        |Date(8,0,0)         |PNH; Datum van de Meting; Nullable: True|
|METING_TYPE                         |String(50,0,0)      |PNH; Soort Meting; Nullable: True; Default: None|
|OPMERKING                           |String(3000,0,0)    |PNH; Opmerking; Nullable: True; Default: None|
|WVO_ID                              |String(255,0,0)     |PNH; FK naar wegdeel_v; Nullable: True; Default: None|
|IDENTIFICATIE                       |String(255,0,0)     |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None|
|OBJECTID                            |OID(38,0,0)         |PNH; Interne ID ArcGIS; Nullable: False|
|DATALEVERANCIER                     |String(255,0,0)     |PNH; Leverancier van de data; Nullable: True; Default: None|
|GLOBALID                            |GlobalID(38,0,0)    |PNH; Global Unique Identifier; Nullable: False|
|GISIB_ID                            |Integer(0,10,0)     |PNH; ID beheer openbare ruimte (GISIB); Nullable: True|
|AD_ID                               |String(255,0,0)     |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; Nullable: False; Default: None|
|OBJECTBEGINTIJD                     |Date(8,0,0)         |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)         |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|CREATED_USER                        |String(255,0,0)     |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)         |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)      |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)         |PNH; Datum van de laatste mutatie; Nullable: True|

***
