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

|KOLOM                               |TYPE                |DEFINITIE|
|------                              |----                |-----    |
|OBJECTID                            |OID(38,0,0)         |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None|
|GLOBALID                            |GlobalID(38,0,0)    |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None|
|AD_ID                               |String(255,0,0)     |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None|
|GISIB_ID                            |Integer(0,10,0)     |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)     |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|OBJECTBEGINTIJD                     |Date(8,0,0)         |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)         |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|BEHEERDER                           |String(255,0,0)     |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None|
|ONDERHOUDER                         |String(255,0,0)     |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None|
|NAAM                                |String(255,0,0)     |PNH; Deeltraject-naam, bijvoorbeeld k20n-d; Nullable: True; Default: None|
|DEELTRAJECTNUMMER                   |String(25,0,0)      |PNH; Deeltraject Nr; Nullable: True; Default: None|
|OMSCHRIJVING                        |String(255,0,0)     |PNH; Extra toelichting; Nullable: True; Default: None|
|BEGINLINKEROEVER                    |String(255,0,0)     |PNH; Begin Linker Oever; Nullable: True; Default: None|
|BEGINRECHTEROEVER                   |String(255,0,0)     |PNH; Begin Rechter Oever; Nullable: True; Default: None|
|EINDLINKEROEVER                     |String(255,0,0)     |PNH; Eind Linker Oever; Nullable: True; Default: None|
|EINDRECHTEROEVER                    |String(255,0,0)     |PNH; Eind Rechter Oever; Nullable: True; Default: None|
|GELDENDEBEPERKING                   |String(255,0,0)     |PNH; Waar een vaarwegdeeltraject niet voldoet aan een streefbeeld worden beperking opgelegd qua gebruik.- Nullable: True; Default: None|
|LENGTELINKEROEVER                   |Float(0,25,10)      |PNH; Lengte linkeroever (m)- Nullable: True|
|LENGTERECHTEROEVER                  |Float(0,25,10)      |PNH; Lengte rechteroever (m)- Nullable: True|
|BESLUITNUMMER                       |String(255,0,0)     |PNH; Besluitnummer waarde; keuzelijst [BESLUITNUMMER]; Nullable: True; Default: None|
|GEWENSTEBAGGERKWAL                  |String(255,0,0)     |PNH; Gewenste baggerkwaliteit; Nullable: True; Default: None|
|DATALEVERANCIER                     |String(255,0,0)     |PNH; Leverancier van de data; Nullable: True; Default: None|
|TRAJECT                             |String(255,0,0)     |PNH; FK naar traject_v; Nullable: True; Default: None|
|CREATED_USER                        |String(255,0,0)     |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)         |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)      |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)         |PNH; Datum van de laatste mutatie; Nullable: True|
|SHAPE                               |Geometry            |PNH; Vlak|
|SHAPE_Length                        |Double(0,0,0)       |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None|
|SHAPE_Area                          |Double(0,0,0)       |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None|


***
