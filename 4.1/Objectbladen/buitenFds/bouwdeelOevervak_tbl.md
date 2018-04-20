## AREAALDATA.bouwdeelOevervak_tbl

*Feature dataset: -*

* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ NEN 2767-4 / PNH
* __Positionele nauwkeurigheid:__ nvt
* __Geometrie:__ Geen
* __Definitie:__ Laagste niveau van decompositie van scheidingOevervak_l. Het begrip NEN Bouwdeel is niet gedefinieerd.


***

|KOLOM                               |TYPE                    |DEFINITIE|
|------                              |----                    |-----    |
|NENMATERIAALSOORT                   |String(255,0,0)         |PNH; NENMateriaalsoort; keuzelijst [MATERIAALSOORT]; Nullable: True; Default: None|
|OMSCHRIJVING                        |String(255,0,0)         |PNH; Extra toelichting; Nullable: True; Default: None|
|CONDITIESCORE                       |Integer(0,10,0)         |PNH; Conditiescore conform NEN 2767-4; Nullable: True; Default: None|
|CONDITIESCORE_DATUM                 |Date(8,0,0)             |PNH; Datum opname Conditiescore; Nullable: True; Default: None|
|CONDITIESCORE_OPM                   |String(3000,0,0)        |PNH; Opmerking bij conditiescore conform NEN 2767-4; Nullable: True; Default: None|
|AANLEGJAAR                          |SmallInteger(0,10,0)    |PNH; Aanlegjaar; Nullable: True|
|RENOVATIEJAAR                       |SmallInteger(0,10,0)    |PNH; Renovatiejaar; Nullable: True|
|SCHEIDINGOEVERVAK                   |String(255,0,0)         |PNH; FK naar scheidingOevervak_l; Nullable: True; Default: None|
|TYPESPEC                            |String(255,0,0)         |PNH; Nadere typering van het object; keuzelijst [typeSpecBWD]; Nullable: True; Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)         |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|OBJECTBEGINTIJD                     |Date(8,0,0)             |BGT; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)             |BGT; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|GLOBALID                            |GlobalID(38,0,0)        |PNH; Global Unique Identifier; Nullable: False|
|GISIB_ID                            |Integer(0,10,0)         |PNH; ID beheer openbare ruimte (GISIB); Nullable: True|
|AD_ID                               |String(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; Nullable: False; Default: None|
|CREATED_USER                        |String(255,0,0)         |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)             |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)          |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)             |PNH; Datum van de laatste mutatie; Nullable: True|
|DATALEVERANCIER                     |String(255,0,0)         |PNH; Leverancier van de data; Nullable: True; Default: None|


***

