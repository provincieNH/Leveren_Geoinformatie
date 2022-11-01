## AREAALDATA.vaarwegdeeltraject_v

$ Feature dataset: Functioneel


* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt, Abstracte indeling
* __SHAPE:__ Vlak
* __Definitie:__
Vaarwegdeeltraject is een abstract functioneel gebied waarvan
de afmetingen zijn bepaald aan de hand van het geografisch
bereik van de geldende beperking en de geldende functie
zoals die is aangegeven door de beheerder of vanuit het
beheerplan. Het heeft geen vaste afmetingen maar past
altijd binnen het vaarwegtraject.


***

|KOLOM                               |TYPE              |DEFINITIE|
|------                              |----              |-----    |
|NAAM                                |String(255,0,0)     |Deeltraject-naam, bijvoorbeeld k20n-d - Nullable: True Default: None|
|DEELTRAJECTNUMMER                   |String(25,0,0)      |Deeltraject Nr - Nullable: True Default: None|
|OMSCHRIJVING                        |String(255,0,0)     |Extra toelichting - Nullable: True Default: None||
|BEGINLINKEROEVER                    |String(255,0,0)     |Begin Linker Oever - Nullable: True Default: None|
|BEGINRECHTEROEVER                   |String(255,0,0)     |Begin Rechter Oever - Nullable: True Default: None|
|EINDLINKEROEVER                     |String(255,0,0)     |Eind Linker Oever - Nullable: True Default: None|
|EINDRECHTEROEVER                    |String(255,0,0)     |Eind Rechter Oever - Nullable: True Default: None|
|GELDENDEBEPERKING                   |String(255,0,0)     |Waar een vaarwegdeeltraject niet voldoet aan een streefbeeld worden beperking opgelegd qua gebruik.- Nullable: True Default: None|
|LENGTELINKEROEVER                   |Float(0,25,10)      |Lengte linkeroever (m)- Nullable: True|
|LENGTERECHTEROEVER                  |Float(0,25,10)      |Lengte rechteroever (m)- Nullable: True|
|BESLUITNUMMER                       |String(255,0,0)     |Besluitnummer waarde, keuzelijst [BESLUITNUMMER] - Nullable: True Default: None|
|GEWENSTEBAGGERKWAL                  |String(255,0,0)     |Gewenste baggerkwaliteit - Nullable: True Default: None|
|SHAPE                               |Geometry            |Vlak|
|SHAPE_Length                        |Double(0,0,0)       |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Area                          |Double(0,0,0)       |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|TRAJECT                             |String(255,0,0)     |FK naar traject_v - Nullable: True Default: None|
|IDENTIFICATIE                       |String(255,0,0)    |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
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
|BEHEERDER                           |String(255,0,0)    |Beheerder van het object, keuzelijst [BEHEERDER] - Nullable: True Default: None|
|ONDERHOUDER                         |String(255,0,0)    |Onderhouder van het object, keuzelijst [ONDERHOUDER] - Nullable: True Default: None|
|EIGENAAR                            |String(255,0,0)    |Eigenaar van het object, keuzelijst [INSTANTIE] - Nullable: True Default: None| |DATALEVERANCIER                     |String(255,0,0)    |Leverancier van de data - Nullable: True Default: None|

***
