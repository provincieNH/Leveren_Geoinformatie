## AREAALDATA.traject_v

*Feature dataset: Functioneel*


* __Areaaldata model versie:__ 4.1
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

In Areaaldata behoren tot een traject alle (beheer)objecten van de provincie Noord-Holland die binnen de beheergrenzen
van het traject liggen.

***

|KOLOM                               |TYPE                  |DEFINITIE|
|------                              |----                  |-----    |
|OBJECTID                            |OID(38,0,0)           |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:Yes|
|GLOBALID                            |GlobalID(38,0,0)      |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:Yes|
|AD_ID                               |String(255,0,0)       |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None; Visible:Yes|
|GISIB_ID                            |Integer(0,10,0)       |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|VERWERKINGSSTATUS                   |String(255,0,0)       |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible:Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)           |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True; Visible:Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)           |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True; Visible:Yes|
|TYPESPEC                            |String(255,0,0)       |PNH; Nadere typering van het object; keuzelijst [typeSpecTRA]; Nullable: True; Default: None; Visible:Yes|
|CODE                                |String(25,0,0)        |PNH; Unieke code ter identificatie van een traject; Nullable: True; Default: None; Visible:Yes|
|GEBRUIKSFUNCTIE                     |String(255,0,0)       |PNH; Gebruiksfunctie; keuzelijst [GEBRUIKSFUNCTIE]; Nullable: True; Default: None; Visible:Yes|
|OMSCHRIJVING                        |String(255,0,0)       |PNH; Extra toelichting; Nullable: True; Default: None; Visible:Yes|
|PLANJAAR                            |SmallInteger(0,10,0)  |PNH; Het geplande jaar dat het object vervangen wordt; Nullable: True; Default: None; Visible:No|
|RANGORDE                            |SmallInteger(0,10,0)  |PNH; TODO; Nullable: True; Visible:No|
|AANLEGJAAR                          |SmallInteger(0,10,0)  |PNH; Is het jaar van aanleg van de vaarweg; Nullable: True; Visible:No|
|BEGINLINKEROEVER                    |String(255,0,0)       |PNH; Begin Linker Oever; Nullable: True; Default: None; Visible:No|
|BEGINRECHTEROEVER                   |String(255,0,0)       |PNH; Begin Rechter Oever; Nullable: True; Default: None; Visible:No|
|BEPERKING                           |String(255,0,0)       |PNH; In het geval waar een vaarwegtraject niet voldoet aan het streefbeeld moet de geldende beperkingen die gelden voor het hele traject aangegeven worden; Nullable: True; Default: None; Visible:No|
|EINDLINKEROEVER                     |String(255,0,0)       |PNH; Eind Linker Oever; Nullable: True; Default: None; Visible:No|
|EINDRECHTEROEVER                    |String(255,0,0)       |PNH; Eind Rechter Oever; Nullable: True; Default: None; Visible:No|
|JAARAANLEG                          |SmallInteger(0,10,0)  |PNH; Is het jaar van aanleg van de vaarweg; Nullable: True; Visible:No|
|LENGTELINKEROEVER                   |Float(0,25,10)        |PNH; Lengte linkeroever (m); Nullable: True; Visible:Yes|
|LENGTERECHTEROEVER                  |Float(0,25,10)        |PNH; Lengte rechteroever (m); Nullable: True; Visible:Yes|
|STREEFBEELD                         |String(255,0,0)       |PNH; Concrete visuele doelstelling; Nullable: True; Default: None; Visible:No|
|VOLDOET                             |SmallInteger(0,1,0)   |PNH; Geeft aan als de vaarweg voldoet aan het streefbeeld omschrijving; Nullable: True; Visible:No|
|CEMTKLASSE                          |String(255,0,0)       |PNH; CEMTKLASSE object; keuzelijst [CEMT_KLASSE]; Nullable: True; Default: None; Visible:No|
|MAATGEVENDSCHIP                     |String(255,0,0)       |PNH; MAATGEVENDSCHIP waarde; keuzelijst [MAATGEVEND_SCHIP]; Nullable: True; Default: None; Visible:No|
|DATALEVERANCIER                     |String(255,0,0)       |PNH; Leverancier van de data; Nullable: True; Default: None|
|CREATED_USER                        |String(255,0,0)       |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None; Visible:No|
|CREATED_DATE                        |Date(8,0,0)           |PNH; Aanmaakdatum; Nullable: True; Visible:No|
|LAST_EDITED_USER                    |String(50,0,0)        |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None; Visible:No|
|LAST_EDITED_DATE                    |Date(8,0,0)           |PNH; Datum van de laatste mutatie; Nullable: True; Visible:No|
|SHAPE                               |Geometry              |PNH; Vlak; Visible:Yes|
|SHAPE_Length                        |Double(0,0,0)         |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None; Visible:Yes|
|SHAPE_Area                          |Double(0,0,0)         |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None; Visible:Yes|
|GEBIEDSCONTRACTREGIO                |String(255,0,0)       |PNH; FK naar gebiedscontractregio_v; Nullable: True; Default: None; Visible:Yes|

***

