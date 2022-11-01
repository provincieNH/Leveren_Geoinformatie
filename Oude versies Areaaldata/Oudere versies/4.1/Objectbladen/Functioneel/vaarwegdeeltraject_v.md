## AREAALDATA.vaarwegdeeltraject_v

*Feature dataset: Functioneel*


* __Areaaldata model versie:__ 4.1
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
|OBJECTID                            |OID(38,0,0)         |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:Yes|
|GLOBALID                            |GlobalID(38,0,0)    |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:Yes|
|AD_ID                               |String(255,0,0)     |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None; Visible:Yes|
|GISIB_ID                            |Integer(0,10,0)     |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|VERWERKINGSSTATUS                   |String(255,0,0)     |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible:Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)         |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True; Visible:Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)         |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True; Visible:Yes|
|BEHEERDER                           |String(255,0,0)     |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible:Yes|
|ONDERHOUDER                         |String(255,0,0)     |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible:No|
|NAAM                                |String(255,0,0)     |PNH; Deeltraject-naam, bijvoorbeeld k20n-d; Nullable: True; Default: None; Visible:Yes|
|DEELTRAJECTNUMMER                   |String(25,0,0)      |PNH; Deeltraject Nr; Nullable: True; Default: None; Visible:Yes|
|OMSCHRIJVING                        |String(255,0,0)     |PNH; Extra toelichting; Nullable: True; Default: None; Visible:Yes|
|BEGINLINKEROEVER                    |String(255,0,0)     |PNH; Begin Linker Oever; Nullable: True; Default: None; Visible:No|
|BEGINRECHTEROEVER                   |String(255,0,0)     |PNH; Begin Rechter Oever; Nullable: True; Default: None; Visible:No|
|EINDLINKEROEVER                     |String(255,0,0)     |PNH; Eind Linker Oever; Nullable: True; Default: None; Visible:No|
|EINDRECHTEROEVER                    |String(255,0,0)     |PNH; Eind Rechter Oever; Nullable: True; Default: None; Visible:No|
|GELDENDEBEPERKING                   |String(255,0,0)     |PNH; Waar een vaarwegdeeltraject niet voldoet aan een streefbeeld worden beperking opgelegd qua gebruik.- Nullable: True; Default: None; Visible:No|
|LENGTELINKEROEVER                   |Float(0,25,10)      |PNH; Lengte linkeroever (m)- Nullable: True; Visible:Yes|
|LENGTERECHTEROEVER                  |Float(0,25,10)      |PNH; Lengte rechteroever (m)- Nullable: True; Visible:Yes|
|BESLUITNUMMER                       |String(255,0,0)     |PNH; Besluitnummer waarde; keuzelijst [BESLUITNUMMER]; Nullable: True; Default: None; Visible:Yes|
|GEWENSTEBAGGERKWAL                  |String(255,0,0)     |PNH; Gewenste baggerkwaliteit; Nullable: True; Default: None; Visible:No|
|DATALEVERANCIER                     |String(255,0,0)     |PNH; Leverancier van de data; Nullable: True; Default: None|
|TRAJECT                             |String(255,0,0)     |PNH; FK naar traject_v; Nullable: True; Default: None; Visible:Yes|
|CREATED_USER                        |String(255,0,0)     |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None; Visible:No|
|CREATED_DATE                        |Date(8,0,0)         |PNH; Aanmaakdatum; Nullable: True; Visible:No|
|LAST_EDITED_USER                    |String(50,0,0)      |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None; Visible:No|
|LAST_EDITED_DATE                    |Date(8,0,0)         |PNH; Datum van de laatste mutatie; Nullable: True; Visible:No|
|SHAPE                               |Geometry            |PNH; Vlak; Visible:Yes|
|SHAPE_Length                        |Double(0,0,0)       |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None; Visible:Yes|
|SHAPE_Area                          |Double(0,0,0)       |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None; Visible:Yes|


***
