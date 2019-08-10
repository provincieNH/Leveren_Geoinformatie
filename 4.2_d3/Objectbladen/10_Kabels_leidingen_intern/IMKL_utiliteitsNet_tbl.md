## AREAALDATA.utiliteitsNet_tbl

*Feature dataset: -*


* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL1.2.1
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Geen
* __Definitie:__ Een verzameling netwerkelementen die tot 1 type IMKL utiliteitsnet behoren. Dit object wordt voorlopig gevuld obv het IMKL-conversie-model. Op termijn kan er voor gekozen worden deze waarden rechtstreeks uit andere objecten af te leiden.

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                    |-----    |
|IDENTIFICATIE                       |String(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: IMKL-ID in format 'nl.imkl-P0027.AD_ID'; ; Nullable: False; Default: None; Visible: No|
|UTILITEITSNETTYPE                   |String(255,0,0)         |PNH; IMKL utilityNetworkType; keuzelijst [UtilityNetworkTypeValue]; Nullable: False; Default: None|
|OBJECTID                            |OID(38,0,0)             |PNH; Interne ID ArcGIS; ; Nullable: False; Default: None; Visible: No|
|GLOBALID                            |GlobalID(38,0,0)        |PNH; Global Unique Identifier; ; Nullable: False; Default: None; Visible: No|
|AD_ID                               |String(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; ; Nullable: False; Default: None; Visible: No|
|OBJECTBEGINTIJD                     |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: False; Default: None; Visible: No|
|OBJECTEINDTIJD                      |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |String(255,0,0)         |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)             |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)          |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)             |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True: Default: None; Visible: No|
|AUTORITEITSROL                      |String(255,0,0)         |PNH; authorityRole; keuzelijst [AUTORITEITSROL]; Nullable: False; Default: None; Visible: No|
|standaardDieptelegging              |Integer(0,10,2)         |PNH; De UOM wordt uitgedrukt in meters middels de volgende OGC URN code 'urn:ogc:def:uom:OGC::m'; ; Nullable: True; Default: None; Visible: No|
|disclaimer                          |String(255,0,0)         |PNH; Dislaimer over de juistheid van de informatie binnen het betreffende utiliteitsnet tbv de grondroerder; ; Nullable: True; Default: None; Visible: No|
|THEMA                               |String(255,0,0)         |PNH; IMKL Thema waar een utiliteitsnet onder valt; keuzelijst [THEMA]; Nullable: False; Default: None; Visible: No|

***
