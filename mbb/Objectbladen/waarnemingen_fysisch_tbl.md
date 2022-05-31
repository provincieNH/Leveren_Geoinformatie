## mbb.waarnemingen_fysisch
*Feature dataset: geen*


* __BUDATA model versie:__ nvt
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt
* __SHAPE:__ nvt
* __Definitie:__ ToDo: BESCHRIJVING
* __Inhoudelijke eigenaar:__ Ingenieursdiensten
* __Technische eigenaar:__ Data & informatie

ToDo: BESCHRIJVING
***



|KOLOM                               |Alias                             | TYPE (length, precision, scale)       |DEFINITIE (oorsprong; beschrijving; keuzelijst; nullable; default)|
|------                              |----                              |---------------------------------------|----
|OBJECTID                            |OBJECTID                          | OID(0,10)                             |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None|
|DATUM                               |                                  | DATE                                  |PNH; Datum van de waarneming; ; Nullable: True; Default: None|
|TIJDSTIP                            |                                  | DATE                                  |PNH; Tijstip van de waarneming; ; Nullable: True; Default: None|
|WAARNEMINGSSOORT                    |                                  | GUID                                  |PNH; Verwijzing naar waarnemingssoort; ; Nullable: True; Default: None|
|HOEVEELHEID                         |                                  | TEXT(255)                             |PNH; ; ; Nullable: True; Default: None|
|EENHEID                             |                                  | TEXT(255)                             |PNH; ; ; Nullable: True; Default: None|
|INSTANTIE                           |                                  | GUID                            | PNH; Verwijzing naar instantie; ; Nullable: True; Default: None                                  |
|PERSOON                             |                                  | GUID                            | PNH; Verwijzing naar persoon; ; Nullable: True; Default: None                                    |
|LABORATORIUM                        |                                  | LONG(0,10)                            |PNH; ; ; Nullable: True; Default: None|
|MONSTER_ID                          |monster_id                        | GUID                                  |PNH; Identificatienummer van het monsterpunt; ; Nullable: False; Default: None|
|MONSTERPUNT                         |monsterpunt                       | GUID                                  |PNH; ; ; Nullable: False; Default: None|
***

