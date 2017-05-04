## AREAALDATA.traject_v

$ Feature dataset: Functioneel


* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt, Abstracte indeling
* __SHAPE:__ Vlak
* __Definitie:__
Een abstract functioneel gebied rondom een weg of vaarweg dat onder de verantwoordelijkheid van de provincie Noord-Holland valt.

Richtlijnen voor omvang van een wegtraject:
    + Een traject start/eindigt bij een eigendoms/beheergrens
    + Een traject start/eindigt bij een aansluiting op een weg van een hogere orde.
    + Een traject start/eindigt op een weg van een gelijke orde.

Richtlijn voor omvang vaarwegtraject:
het gebied dat is gedefinieerd in de vaarwegverordening (breedte) en een
logisch doorvaartraject (lengte).

In BUDATA behoren tot een traject alle (beheer)objecten van de provincie Noord-Holland die binnen de beheergrenzen
van het traject liggen.

***

|KOLOM                               |TYPE                  |DEFINITIE|
|------                              |----                  |-----    |
|CODE                                |String(25,0,0)        |Unieke code ter identificatie van een traject  - Nullable: True Default: None|
|GEBRUIKSFUNCTIE                     |String(255,0,0)       |Gebruiksfunctie, keuzelijst [GEBRUIKSFUNCTIE] - Nullable: True Default: None|
|OMSCHRIJVING                        |String(255,0,0)       |Extra toelichting - Nullable: True Default: None|
|PLANJAAR                            |SmallInteger(0,10,0)  |TODO - Nullable: True|
|RANGORDE                            |SmallInteger(0,10,0)  |TODO - Nullable: True|
|AANLEGJAAR                          |SmallInteger(0,10,0)  |Is het jaar van aanleg van de vaarweg - Nullable: True|
|BEGINLINKEROEVER                    |String(255,0,0)       |Begin Linker Oever - Nullable: True Default: None|
|BEGINRECHTEROEVER                   |String(255,0,0)       |Begin Rechter Oever - Nullable: True Default: None|
|BEPERKING                           |String(255,0,0)       |In het geval waar een vaarwegtraject niet voldoet aan het streefbeeld moet de geldende beperkingen die gelden voor het hele traject aangegeven worden. - Nullable: True Default: None|
|EINDLINKEROEVER                     |String(255,0,0)       |Eind Linker Oever - Nullable: True Default: None|
|EINDRECHTEROEVER                    |String(255,0,0)       |Eind Rechter Oever - Nullable: True Default: None|
|JAARAANLEG                          |SmallInteger(0,10,0)  |Is het jaar van aanleg van de vaarweg - Nullable: True|
|LENGTELINKEROEVER                   |Float(0,25,10)        |Lengte linkeroever (m) - Nullable: True|
|LENGTERECHTEROEVER                  |Float(0,25,10)        |Lengte rechteroever (m) - Nullable: True|
|STREEFBEELD                         |String(255,0,0)       |Een theoretisch omschrijving van de soort vaarwegtraject  - Nullable: True Default: None|
|VOLDOET                             |SmallInteger(0,1,0)   |Geeft aan als de vaarweg voldoet aan het streefbeeld omschrijving. - Nullable: True|
|CEMTKLASSE                          |String(255,0,0)       |CEMTKLASSE object, keuzelijst [CEMT_KLASSE] - Nullable: True Default: None|
|MAATGEVENDSCHIP                     |String(255,0,0)       |MAATGEVENDSCHIP waarde, keuzelijst [MAATGEVEND_SCHIP] - Nullable: True Default: None|
|SHAPE                               |Geometry(0,0,0)       |Vlak|
|SHAPE_Length                        |Double(0,0,0)         |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Area                          |Double(0,0,0)         |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|GEBIEDSCONTRACTREGIO                |String(255,0,0)       |FK naar gebiedscontractregio_v - Nullable: True Default: None|
|IDENTIFICATIE                       |String(255,0,0)    |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecTRA] - Nullable: True Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)    |Status van de gegevens, keuzelijst [VERWERKINGSSTATUS] - Nullable: False Default: Nieuw|
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


***

