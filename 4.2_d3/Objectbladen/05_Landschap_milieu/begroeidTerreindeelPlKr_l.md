## AREAALDATA.begroeidTerreindeelPlKr_l

*Feature dataset: Opdelend*


* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ BGT
* __Positionele nauwkeurigheid:__ Afgeleid van object waar kruinlijn bij hoort
* __Geometrie:__ Lijn
* __Definitie:__  Lijngeometrie van de hoogstgelegen begrenzing van een kunstmatig aangelegd en onderhouden helling. Let op: Kruinlijnen zijn gerelateerd aan hun respectievelijke objecten middels een relatie op IDENTIFICATIE met IDENTIFICATIE
* __Mapping_BGT:__ begroeidTerreindeelKruin_l
* __Mapping_Gisib:__ x


***

|__KOLOM__                          |__TYPE (length, precision, scale)__             |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                          	|----          	                                 |-----    |
|IDENTIFICATIE                      |String(255,0,0)                                 |PNH; Verwijzende sleutel naar begroeidTerreindeelPlantvak_v (composiet); ; Nullable: True; Default: None; Visible: No|
|SHAPE                              |Geometry(0,0,0)                                 |PNH; Lijn; ; Nullable: False; Default: None; Visible: Yes|
|SHAPE_Length                       |Double(0,0,0)                                   |PNH; Lengte in meters, 5 decimalen. Dit wordt automatisch gevuld; ; Nullable: False; Default: None; Visible: Yes|
|VERWERKINGSSTATUS                  |String(255,0,0)                                 |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTID                           |OID(38,0,0)                                     |PNH; Interne ID ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                           |GlobalID(38,0,0)                                |PNH; Global Unique Identifier; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                           |Integer(0,10,0)                                 |PNH; ID beheer openbare ruimte (GISIB); ; Nullable: True; Default: None; Visible: Yes|
|AD_ID                              |String(255,0,0)                                 |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; ; Nullable: False; Default: None; Visible: Yes|
|OBJECTBEGINTIJD                    |Date(8,0,0)                                     |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                     |Date(8,0,0)                                     |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|CREATED_USER                       |String(255,0,0)                                 |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                       |Date(8,0,0)                                     |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                   |String(50,0,0)                                  |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                   |Date(8,0,0)                                     |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|

***
