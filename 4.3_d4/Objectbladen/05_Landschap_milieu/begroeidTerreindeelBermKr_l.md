## AREAALDATA.begroeidTerreindeelBermKr_l

*Feature dataset: Opdelend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ BGT
* __Positionele nauwkeurigheid:__ Afgeleid van object waar kruinlijn bij hoort
* __Geometrie:__ Lijn
* __Definitie:__  Lijngeometrie van de hoogstgelegen begrenzing van een kunstmatig aangelegd en onderhouden helling. Let op: Kruinlijnen zijn gerelateerd aan hun respectievelijke objecten middels een relatie op IDENTIFICATIE met IDENTIFICATIE
* __Mapping_BGT:__ begroeidTerreindeelKruin_l
* __Mapping_Gisib:__ x
* __Mapping_NTA8035:__ bs:SpatialRegion

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                          	 |----          	        |-----    |
|IDENTIFICATIE                       |TEXT(255,0,0)             |PNH; Verwijzende sleutel naar begroeidTerreindeelBerm_v (composiet); ;Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry(0,0,0)           |PNH; Lijn; ; Nullable: False; Default: None; Visible: Yes|
|SHAPE_Length                        |DOUBLE(0,0,0)             |PNH; Lengte in meters, 5 decimalen. Dit wordt automatisch gevuld; ; Nullable: False; Default: None; Visible: Yes|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)             |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTID                            |OID(38,0,0)               |PNH; Interne ID ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)          |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)              |PNH; ID beheer openbare ruimte (GISIB); ; Nullable: True; Default: None; Visible: Yes|
|AD_ID                               |TEXT(255,0,0)             |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; ; Nullable: False; Default: None; Visible: Yes|
|OBJECTBEGINTIJD                     |DATE(8,0,0)               |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)               |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|CREATED_USER                        |TEXT(255,0,0)             |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)               |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)              |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)               |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|


***
