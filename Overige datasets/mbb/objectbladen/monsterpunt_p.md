## mbb.monsterpunt_p

* __MBB model versie:__ 1.0
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 5 cm
* __SHAPE:__ Punt
* __Definitie:__ ToDo: BESCHRIJVING
* __Inhoudelijke eigenaar:__ Ingenieursdiensten
* __Technische eigenaar:__ Data & informatie

***


|KOLOM                               |Alias*                             |TYPE (length, precision, scale)               |DEFINITIE (oorsprong; beschrijving; keuzelijst; nullable; default)|
|------                              |----                              |-----                                          |----
|OBJECTID                            |                                  |OID(0,10)                                      |PNH; Intern ArcGIS Identificatienummer; ; Nullable: False; Default: None|
|SHAPE                               |                                  |GEOMETRY                                       |PNH; Geometrie; ; Nullable: True; Default: None|
|WEGNR                               |wegnr                             |TEXT(255)                                      |PNH; Wegnummer; ; Nullable: True; Default: None|
|HMNR                                |hmnr                              |LONG(0,10)                                     |PNH; ; ; Nullable: True; Default: None|
|WEGZIJDE                            |wegzijde                          |TEXT(255)                                      |PNH; ; ; Nullable: True; Default: None|
|GEBIEDSCONTRACTREGIO                |gebiedscontractregio (ad_id)      |TEXT(255)                                      |PNH; AD id van de gebiedscontractregio; ; Nullable: True; Default: None|
|MONSTERPUNT_ID                      |                                  |GUID                                           |PNH; Identificatienummer van het monsterpunt; ; Nullable: False; Default: None|
***

