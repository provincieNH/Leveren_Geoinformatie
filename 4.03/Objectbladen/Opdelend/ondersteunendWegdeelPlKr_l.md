## AREAALDATA.ondersteunendWegdeelPlKr_l

$ Feature dataset: Opdelend

* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ BGT
* __Positionele nauwkeurigheid:__ afgeleid van object waar kruinlijn bij hoort
* __Geometrie:__ Lijn
* __Definitie:__  Lijngeometrie van de hoogstgelegen begrenzing van een kunstmatig aangelegd en onderhouden helling. Let op: Kruinlijnen zijn gerelateerd aan hun respectievelijke objecten middels een relatie op IDENTIFICATIE met IDENTIFICATIE.

***

|KOLOM                              |TYPE          	        |DEFINITIE|
|------                          	|----          	        |-----    |
|IDENTIFICATIE                      |String(255,0,0)        |FK naar ondersteunendWegdeelPlantvak_v - Nullable: True Default: None|
|SHAPE                              |Geometry(0,0,0)        |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Length                       |Double(0,0,0)          |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)       |Status van de gegevens, keuzelijst [VERWERKINGSSTATUS] - Nullable: False Default: Nieuw|
|OBJECTID                            |OID(38,0,0)           |Interne ID ArcGIS - Nullable: False|
|GLOBALID                            |GlobalID(38,0,0)      |Global Unique Identifier - Nullable: False|
|GISIB_ID                            |Integer(0,10,0)       |ID beheer openbare ruimte (GISIB) - Nullable: True|
|AD_ID                               |String(255,0,0)       |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]' - Nullable: False Default: None|
|OBJECTBEGINTIJD                     |Date(8,0,0)           |Datum waarop het object bij de bronhouder is ontstaan - Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)           |Datum waarop het object bij de bronhouder niet meer geldig is - Nullable: True|
|CREATED_USER                        |String(255,0,0)       |Naam van gebruiker die de rij heeft aangemaakt - Nullable: True Default: None|
|CREATED_DATE                        |Date(8,0,0)           |Aanmaakdatum - Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)        |Naam van gebruiker die de laatste mutatie heeft doorgevoerd - Nullable: True Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)           |Datum van de laatste mutatie - Nullable: True|


***
