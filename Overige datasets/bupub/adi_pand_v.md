adi_pand_v.md

# bupub.adi_pand_v


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
|identificatiebagpnd              |character varying(255)     |NO      |TODO|
|identificatie                    |character varying(255)     |YES     |TODO|
|status                           |character varying(255)     |NO      |TODO|
|verwerkingsstatus                |character varying(255)     |NO      |TODO|
|objectbegintijd                  |timestamp without time zone|NO      |TODO|
|objecteindtijd                   |timestamp without time zone|YES     |TODO|
|bronhouder                       |character varying(255)     |NO      |TODO|
|inonderzoek                      |character varying(255)     |NO      |TODO|
|relatievehoogteligging           |smallint                   |NO      |TODO|
|tijdstipregistratie              |timestamp without time zone|YES     |TODO|
|eindregistratie                  |timestamp without time zone|YES     |TODO|
|lv_publicatiedatum               |timestamp without time zone|YES     |TODO|
|bericht_id                       |character varying(255)     |YES     |TODO|
|gisib_id                         |integer                    |YES     |TODO|
|ad_id                            |character varying(255)     |NO      |TODO|
|created_user                     |character varying(255)     |YES     |TODO|
|created_date                     |timestamp without time zone|YES     |TODO|
|last_edited_user                 |character varying(50)      |YES     |TODO|
|last_edited_date                 |timestamp without time zone|YES     |TODO|
|traject                          |character varying(255)     |YES     |TODO|
|eigenaar                         |character varying(255)     |YES     |TODO|
|onderhouder                      |character varying(255)     |YES     |TODO|
|dataleverancier                  |character varying(255)     |YES     |TODO|
|beheerder                        |character varying(255)     |YES     |TODO|
|omtrek                           |numeric(38,8)              |YES     |TODO|
|oppervlakte                      |numeric(38,8)              |YES     |TODO|
|opmerking                        |character varying(255)     |YES     |TODO|
|gdb_geomattr_data                |bytea                      |YES     |TODO|
|shape                            |USER-DEFINED               |YES     |TODO|
