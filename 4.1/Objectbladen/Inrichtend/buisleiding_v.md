## AREAALDATA.buisleiding_v

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL; TODO: MOET NOG NAAR IMKL2015
* __Positionele nauwkeurigheid:__ 7,5 cm
* __SHAPE:__ Vlak
* __Definitie:__ Buisleidingen zijn leidingen met gevaarlijke inhoud, te weten:
1. aardgasleidingen met een uitwendige diameter van meer dan 50mm en een druk van meer dan 1600KPa
2. buisleidingen voor het vervoer van brandbare vloeistoffen van de categorieën K1, K2 of K3, met een uitwendige diameter van meer dan 100mm
3. buisleidingen voor andere gevaarlijke stoffen dan bedoeld onder 1. en 2., waarvoor het plaatsgebonden risico op een afstand van 5 meter gemeten vanaf het hart van de buisleiding hoger is dan (10)-6 per jaar.

***

|KOLOM                               |TYPE                   |DEFINITIE|
|------                              |----                   |-----    |
|OBJECTID                            |OID(38,0,0)            |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None|
|GLOBALID                            |GlobalID(38,0,0)       |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None|
|AD_ID                               |String(255,0,0)        |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None|
|GISIB_ID                            |Integer(0,10,0)        |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None|
|IDENTIFICATIE                       |String(255,0,0)        |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)        |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|OBJECTBEGINTIJD                     |Date(8,0,0)            |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)            |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|BEHEERDER                           |String(255,0,0)        |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None|
|ONDERHOUDER                         |String(255,0,0)        |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None|
|EIGENAAR                            |String(255,0,0)        |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None|
|TYPESPEC                            |String(255,0,0)        |PNH; Nadere typering van het object; keuzelijst [typeSpecBUI]; Nullable: True; Default: None|
|AANTALBUIZEN                        |SmallInteger(0,10,0)   |PNH; Aantal buizen gerepresenteerd door de SHAPE van dit object. Wordt alleen opgenomen indien het aantal groter is dan 1 en de buizen niet als afzonderlijke lijnen (kunnen) worden weergegeven; Nullable: False|
|AFWIJKENDEDIEPTE                    |String(255,0,0)        |PNH; Afwijking van de gangbare dieptelegging voor een leiding van dit thema. (Eenheid cm? TODO; Nullable: True; Default: None|
|bovengrondsZichtbaar                |String(1,0,0)          |PNH; Aangegeven wordt of de buisleiding bovengronds vanaf het maaiveld zichtbaar is; keuzelijst [jaNee]; Nullable: True; Default: None|
|OMSCHRIJVING                        |String(255,0,0)        |PNH; Extra toelichting; Nullable: True; Default: None|
|DIAMETERCM                          |SmallInteger(0,10,0)   |PNH; Diameter van de buis in cm, afgerond op hele getallen; Nullable: False; Default: None|
|OPMERKING                           |String(255,0,0)        |PNH; Toevoeging van subjectieve informatie met betrekking tot opmerkelijke waarnemingen; Nullable: True; Default: None|
|PRODUCT                             |String(255,0,0)        |PNH; Het product dat door de leiding vervoerd wordt of kan worden vervoerd, 'Energie', 'Data' of 'Onbekend'; Nullable: True; Default: Onbekend|
|VERHOOGDRISICO                      |String(10,0,0)         |PNH; Verhoogd risico Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: O|
|VOORZORGMAATREGEL                   |String(255,0,0)        |PNH; Vermelding of er voorzorgsmaatregelen getroffen dienen te worden. Aangegeven wordt wat de voorzorgsmaatregel is; Nullable: True; Default: None|
|MATERIAALTYPE                       |String(255,0,0)        |PNH; Type materiaal; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None|
|THEMAKAART                          |String(255,0,0)        |PNH; Themakaart; keuzelijst [THEMAKAART]; Nullable: True; Default: None|
|DATALEVERANCIER                     |String(255,0,0)        |PNH; Leverancier van de data; Nullable: True; Default: None|
|CREATED_USER                        |String(255,0,0)        |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)            |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)         |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)            |PNH; Datum van de laatste mutatie; Nullable: True|
|SHAPE                               |Geometry               |PNH; Vlak|
|SHAPE_Length                        |Double(0,0,0)          |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None|
|SHAPE_Area                          |Double(0,0,0)          |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None|

***
