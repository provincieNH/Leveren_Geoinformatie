## AREAALDATA.kwElement_tbl

$ Feature dataset: -

* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ NEN 2767-4 / PNH
* __Positionele nauwkeurigheid:__ nvt
* __Geometrie:__  nvt
* __Definitie:__ Een NEN Element is gedefinieerd als 'een samenstel van bouwdelen die tezamen een afzonderlijk herkenbaar 
component van een beheerobject vormen'. Een NEN Element kan afhankelijk van het beheerobject waar deze bij hoort
gemodelleerd zijn als ELEMENT of GELUIDWERENDE_CONSTRUCTIE. 

***

|KOLOM                               |TYPE                    |DEFINITIE|
|------                              |----                    |-----    |
|MATERIAALTYPE                       |String(255,0,0)         |PNH; Materiaaltype; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None|
|BOUWELEMENTTYPESPE                  |String(255,0,0)         |PNH; Bouwelement Type Specificatie; Nullable: True; Default: None|
|CONFORMNEN                          |String(1,0,0)           |PNH; Is Element conform NEN (Ja/Nee); keuzelijst [jaNee]; Nullable: True; Default: N|
|OMSCHRIJVING                        |String(255,0,0)         |PNH; Extra toelichting; Nullable: True; Default: None|
|OPMERKING                           |String(255,0,0)         |PNH; Opmerking; Nullable: True; Default: None|
|CONDITIESCORE                       |Integer(0,10,0)         |PNH; Conditiescore conform NEN 2767-4; Nullable: True; Default: None|
|CONDITIESCORE_DATUM                 |Date(8,0,0)             |PNH; Datum opname Conditiescore; Nullable: True; Default: None|
|CONDITIESCORE_OPM                   |String(3000,0,0)        |PNH; Opmerking bij conditiescore conform NEN 2767-4; Nullable: True; Default: None|
|KRITISCH                            |String(1,0,0)           |PNH; Kritisch (Ja/Nee); keuzelijst [jaNee]; Nullable: True; Default: N|
|KW_VAST                             |String(255,0,0)         |PNH; FK naar kunstwerkVast_p; Nullable: True; Default: None|
|KW_BEWEEGBAAR                       |String(255,0,0)         |PNH; FK naar kunstwerkBeweegbaar_p; Nullable: True; Default: None|
|SCHUTSLUIS                          |String(255,0,0)         |PNH; FK naar schutsluis_p; Nullable: True; Default: None|
|IDENTIFICATIE                       |String(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None|
|TYPESPEC                            |String(255,0,0)         |PNH; Nadere typering van het object; keuzelijst [typeSpecKWE]; Nullable: True; Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)         |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|OBJECTID                            |OID(38,0,0)             |PNH; Interne ID ArcGIS; Nullable: False|
|GLOBALID                            |GlobalID(38,0,0)        |PNH; Global Unique Identifier; Nullable: False|
|GISIB_ID                            |Integer(0,10,0)         |PNH; ID beheer openbare ruimte (GISIB); Nullable: True|
|AD_ID                               |String(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; Nullable: False; Default: None|
|OBJECTBEGINTIJD                     |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|CREATED_USER                        |String(255,0,0)         |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)             |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)          |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)             |PNH; Datum van de laatste mutatie; Nullable: True|
|BEHEERDER                           |String(255,0,0)         |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None|
|ONDERHOUDER                         |String(255,0,0)         |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None|
|EIGENAAR                            |String(255,0,0)         |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None|
|DATALEVERANCIER                     |String(255,0,0)         |PNH; Leverancier van de data; Nullable: True; Default: None|

***


