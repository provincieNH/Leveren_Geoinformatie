adi_traject_v.md

# bupub.adi_traject_v


* Brondata: 
* Herkomst definitie: 
* Definitie: 
* Geometrie: Vlak
* Inhoudelijke eigenaar: 
* Technische eigenaar: PNH/BU/ID/DI (Provincie Noord-Holland, Directie Beheer & Uitvoering, Sector Ingenieursdiensten, Unit Data & Informatie)

[plaatje]


|KOLOM                            |TYPE                       |NULLABLE|DEFINITIE|
|------                           |----                       |-----   |-----    |
|objectid                         |integer                    |NO      |TODO|
|code                             |character varying(25)      |YES     |TODO|
|gebruiksfunctie                  |character varying(255)     |YES     |TODO|
|planjaar                         |smallint                   |YES     |TODO|
|rangorde                         |smallint                   |YES     |TODO|
|aanlegjaar                       |smallint                   |YES     |TODO|
|beginlinkeroever                 |character varying(255)     |YES     |TODO|
|beginrechteroever                |character varying(255)     |YES     |TODO|
|beperking                        |character varying(255)     |YES     |TODO|
|eindlinkeroever                  |character varying(255)     |YES     |TODO|
|eindrechteroever                 |character varying(255)     |YES     |TODO|
|jaaraanleg                       |smallint                   |YES     |TODO|
|lengtelinkeroever                |numeric(38,8)              |YES     |TODO|
|lengterechteroever               |numeric(38,8)              |YES     |TODO|
|streefbeeld                      |character varying(255)     |YES     |TODO|
|voldoet                          |smallint                   |YES     |TODO|
|cemtklasse                       |character varying(255)     |YES     |TODO|
|maatgevendschip                  |character varying(255)     |YES     |TODO|
|gebiedscontractregio             |character varying(255)     |YES     |TODO|
|typespec                         |character varying(255)     |YES     |TODO|
|verwerkingsstatus                |character varying(255)     |NO      |TODO|
|gisib_id                         |integer                    |YES     |TODO|
|ad_id                            |character varying(255)     |NO      |TODO|
|objectbegintijd                  |timestamp without time zone|YES     |TODO|
|objecteindtijd                   |timestamp without time zone|YES     |TODO|
|created_user                     |character varying(255)     |YES     |TODO|
|created_date                     |timestamp without time zone|YES     |TODO|
|last_edited_user                 |character varying(50)      |YES     |TODO|
|last_edited_date                 |timestamp without time zone|YES     |TODO|
|dataleverancier                  |character varying(255)     |YES     |TODO|
|opmerking                        |character varying(255)     |YES     |TODO|
|omtrek                           |numeric(38,8)              |YES     |TODO|
|oppervlakte                      |numeric(38,8)              |YES     |TODO|
|beheerder                        |character varying(255)     |YES     |TODO|
|gdb_geomattr_data                |bytea                      |YES     |TODO|
|shape                            |USER-DEFINED               |YES     |TODO|
