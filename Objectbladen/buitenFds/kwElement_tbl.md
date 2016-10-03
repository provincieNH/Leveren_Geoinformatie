## AREAALDATA.kwElement_tbl

$ Feature dataset: -

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ NEN 2767-4 / PNH
* __Positionele nauwkeurigheid:__ nvt
* __Geometrie:__  nvt
* __Definitie:__ Een NEN Element is gedefinieerd als 'een samenstel van bouwdelen die tezamen een afzonderlijk herkenbaar 
component van een beheerobject vormen'. Een NEN Element kan afhankelijk van het beheerobject waar deze bij hoort
gemodelleerd zijn als ELEMENT of GELUIDWERENDE_CONSTRUCTIE. 

***

|KOLOM                               |TYPE                |DEFINITIE|
|------                              |----                |-----    |
|MATERIAALTYPE                       |String(255,0,0)     |Materiaaltype, keuzelijst [MATERIAALTYPE] Nullable: True Default: None|
|BOUWELEMENTTYPESPE                  |String(255,0,0)     |Bouwelement Type Specificatie - Nullable: True Default: None|
|CONFORMNEN                          |String(1,0,0)       |Is Element conform NEN ja of nee: keuzelijst [jaNee] Nullable: True Default: N|
|OMSCHRIJVING                        |String(255,0,0)     |Extra toelichting - Nullable: True Default: None|
|OPMERKING                           |String(255,0,0)     |Opmerking - Nullable: True Default: None|
|CONDITIESCORE                       |String(255,0,0)     |Conditiescore conform NEN 2767-4 - Nullable: True Default: None|
|CONDITIESCORE_DATUM                 |String(255,0,0)     |Datum opname Conditiescore - Nullable: True Default: None|
|CONDITIESCORE_OPM                   |String(3000,0,0)    |Opmerking bij conditiescore conform NEN 2767-4 - Nullable: True Default: None|
|AANLEGJAAR                          |SmallInteger(0,10,0)|Aanlegjaar - Nullable: True|
|RENOVATIEJAAR                       |SmallInteger(0,10,0)|Renovatiejaar - Nullable: True|
|KRITISCH                            |String(1,0,0)       |Kritisch (Ja / Nee): keuzelijst [jaNee] Nullable: True Default: N|
|KW_VAST                             |String(255,0,0)     |FK naar kunstwerkVast_p - Nullable: True Default: None|
|KW_BEWEEGBAAR                       |String(255,0,0)     |FK naar kunstwerkBeweegbaar_p - Nullable: True Default: None|
|SCHUTSLUIS                          |String(255,0,0)     |FK naar schutsluis_p - Nullable: True Default: None|
|IDENTIFICATIE                       |String(255,0,0)      |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)     |Nadere typering van het object, keuzelijst [typeSpecKWE] - Nullable: True Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)    |Status van de gegevens, keuzelijst [VERWERKINGSSTATUS] - Nullable: False Default: Nieuwl|
|OBJECTID                            |OID(38,0,0)        |Interne ID ArcGIS - Nullable: False|
|GLOBALID                            |GlobalID(38,0,0)   |Global Unique Identifier - Nullable: False|
|GISIB_ID                            |Integer(0,10,0)    |ID beheer openbare ruimte (GISIB) - Nullable: True|
|AD_ID                               |String(255,0,0)    |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]' - Nullable: False Default: None|
|OBJECTBEGINTIJD                     |Date(8,0,0)        |Datum waarop het object bij de bronhouder is ontstaan - Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)        |Datum waarop het object bij de bronhouder niet meer geldig is - Nullable: True|
|CREATED_USER                        |String(255,0,0)    |Naam van gebruiker die de rij heeft aangemaakt - Nullable: True Default: None|
|CREATED_DATE                        |Date(8,0,0)        |Aanmaakdatum - Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)     |Naam van gebruiker die de laatste mutatie heeft doorgevoerd - Nullable: True Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)        |Datum van de laatste mutatie - Nullable: True|
|BEHEERDER                           |String(255,0,0)    |Beheerder van het object, keuzelijst [BEHEERDER] - Nullable: True Default: None|
|ONDERHOUDER                         |String(255,0,0)    |Onderhouder van het object, keuzelijst [ONDERHOUDER] - Nullable: True Default: None|
|EIGENAAR                            |String(255,0,0)    |Eigenaar van het object, keuzelijst [INSTANTIE] - Nullable: True Default: None| 
|DATALEVERANCIER                     |String(255,0,0)    |Leverancier van de data - Nullable: True Default: None|

***


