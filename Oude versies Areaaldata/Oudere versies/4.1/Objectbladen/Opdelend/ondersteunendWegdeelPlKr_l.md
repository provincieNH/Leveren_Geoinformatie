## AREAALDATA.ondersteunendWegdeelPlKr_l

*Feature dataset: Opdelend*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ BGT
* __Positionele nauwkeurigheid:__ afgeleid van object waar kruinlijn bij hoort
* __Geometrie:__ Lijn
* __Definitie:__  Lijngeometrie van de hoogstgelegen begrenzing van een kunstmatig aangelegd en onderhouden helling. Let op: Kruinlijnen zijn gerelateerd aan hun respectievelijke objecten middels een relatie op IDENTIFICATIE met IDENTIFICATIE.

***

|KOLOM                              |TYPE          	       |DEFINITIE|
|------                          	|----          	       |-----    |
|IDENTIFICATIE                      |String(255,0,0)       |PNH; FK naar ondersteunendWegdeelPlantvak_v; Nullable: True; Default: None|
|SHAPE                              |Geometry(0,0,0)       |PNH; Lijn|
|SHAPE_Length                       |Double(0,0,0)         |PNH; Lengte in meters, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None|
|VERWERKINGSSTATUS                  |String(255,0,0)       |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|OBJECTID                           |OID(38,0,0)           |PNH; Interne ID ArcGIS; Nullable: False|
|GLOBALID                           |GlobalID(38,0,0)      |PNH; Global Unique Identifier; Nullable: False|
|GISIB_ID                           |Integer(0,10,0)       |PNH; ID beheer openbare ruimte (GISIB); Nullable: True|
|AD_ID                              |String(255,0,0)       |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; Nullable: False; Default: None|
|OBJECTBEGINTIJD                    |Date(8,0,0)           |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                     |Date(8,0,0)           |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|CREATED_USER                       |String(255,0,0)       |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                       |Date(8,0,0)           |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                   |String(50,0,0)        |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                   |Date(8,0,0)           |PNH; Datum van de laatste mutatie; Nullable: True|

***
