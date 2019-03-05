## AREAALDATA.concessieverlener_tbl

*Feature dataset: -*

* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH/NDOV
* __Positionele nauwkeurigheid:__ nvt
* __Geometrie:__ Geen
* __Definitie:__ Verlener van de [Concessie]


***

|KOLOM                               |TYPE                 |DEFINITIE|
|------                              |----                 |-----    |
|VERWERKINGSSTATUS                   |String(255,0,0)      |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible:Yes|
|IDENTIFICATIE                       |String(255,0,0)      |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None; Visible:No|
|GLOBALID                            |GlobalID(38,0,0)     |PNH; Global Unique Identifier; Nullable: False; Visible:No|
|GISIB_ID                            |Integer(0,10,0)      |PNH; ID beheer openbare ruimte (GISIB); Nullable: True; Visible:No|
|AD_ID                               |String(255,0,0)      |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; Nullable: False; Default: None; Visible:Yes|
|NAAM                                |String(255,0,0)      |PNH; Naam van de Concessieverlener; Nullable: True; Default: None; Visible:Yes|
|DATALEVERANCIER                     |String(255,0,0)      |PNH; Leverancier van de data; Nullable: True; Default: None|

***
