## AREAALDATA.oeverReparatie_p

$ Feature dataset: Functioneel

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__  nvt
* __Definitie:__ Een lokale reparatie aan een oevervak

***


|KOLOM                               |TYPE              |DEFINITIE|
|------                              |----              |-----    |
|VERWERKINGSSTATUS                   |String(255,0,0)     |Status van de gegevens, keuzelijst [VERWERKINGSSTATUS] - Nullable: False Default: Nieuwl|
|JAAR                                |SmallInteger(0,10,0)|Aanlegjaar - Nullable: True|
|RAPPORT                             |String(255,0,0)     |Pad naar rapport - Nullable: True Default: None||
|SHAPE                               |Geometry(0,0,0)     |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|OBJECTID                            |OID(38,0,0)         |Interne ID ArcGIS - Nullable: False|
|GLOBALID                            |GlobalID(38,0,0)    |Global Unique Identifier - Nullable: False|
|GISIB_ID                            |Integer(0,10,0)     |ID beheer openbare ruimte (GISIB) - Nullable: True|
|AD_ID                               |String(255,0,0)     |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]' - Nullable: False Default: None|
|OBJECTBEGINTIJD                     |Date(8,0,0)         |Datum waarop het object bij de bronhouder is ontstaan - Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)         |Datum waarop het object bij de bronhouder niet meer geldig is - Nullable: True|
|CREATED_USER                        |String(255,0,0)     |Naam van gebruiker die de rij heeft aangemaakt - Nullable: True Default: None|
|CREATED_DATE                        |Date(8,0,0)         |Aanmaakdatum - Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)      |Naam van gebruiker die de laatste mutatie heeft doorgevoerd - Nullable: True Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)         |Datum van de laatste mutatie - Nullable: True|
|OEVERVAK                            |String(255,0,0)     |FK naar oevervak_v - Nullable: True Default: None|



***


