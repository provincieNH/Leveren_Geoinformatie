## AREAALDATA.mantelbuis_v

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL 2015
* __Positionele nauwkeurigheid:__ 7,5 cm
* __SHAPE:__ Vlak
* __Definitie:__ Een mantelbuis is een buis bestemd voor de doorvoer en bescherming van kabels

***

|KOLOM                               |TYPE                    |DEFINITIE|
|------                              |----                    |-----    |
|OBJECTID                            |OID(38,0,0)             |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None|
|GLOBALID                            |GlobalID(38,0,0)        |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None|
|AD_ID                               |String(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None|
|GISIB_ID                            |Integer(0,10,0)         |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None|
|IDENTIFICATIE                       |String(255,0,0)         |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)         |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|OBJECTBEGINTIJD                     |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|BEHEERDER                           |String(255,0,0)         |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None|
|ONDERHOUDER                         |String(255,0,0)         |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None|
|EIGENAAR                            |String(255,0,0)         |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None|
|TYPESPEC                            |String(255,0,0)         |PNH; Nadere typering van het object; keuzelijst [typeSpecBUI]; Nullable: True; Default: None|
|MATERIAALTYPE                       |String(20,0,0)          |PNH; Materiaaltype; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None|
|LENGTE                              |Float(0,10,2)           |PNH; Lengte van de mantelbuis (m, 2 decimalen); Nullable: True|
|bovengrondsZichtbaar                |String(1,0,0)           |PNH; Aangegeven wordt of de mantelbuis bovengronds vanaf het maaiveld zichtbaar is; keuzelijst [jaNee]; Nullable: True; Default: None|
|DATUMPLAATSING                      |Date(8,0,0)             |PNH; Datum Plaatsing; Nullable: True|
|OMSCHRIJVING                        |String(255,0,0)         |PNH; Extra toelichting; Nullable: True; Default: None|
|DIAMETER                            |SmallInteger(0,10,0)    |PNH; De diameter van de mantelbuis uitgedrukt in cm, afgerond in hele cijfers; Nullable: True; Default: None|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)    |PNH; Levensverwachting; Nullable: True|
|OPMERKING                           |String(255,0,0)         |PNH; Toevoeging van subjectieve informatie met betrekking tot opmerkelijke waarnemingen ; Nullable: True; Default: None|
|PLANJAAR                            |SmallInteger(0,10,0)    |PNH; Het geplande jaar dat het object vervangen wordt; Nullable: True; Default: None|
|PRODUCT                             |String(255,0,0)         |PNH; Het product dat door de leiding vervoerd wordt of kan worden vervoerd, 'Energie', 'Data' of 'Onbekend'; Nullable: True; Default: Onbekend|
|HUIDIGESTATUS                       |String(50,0,0)          |PNH; Huidige status; keuzelijst [ConditionOfFacilityValue]; Nullable: False; Default: None|
|GEONAUWKEURIGHEIDXY                 |String(50,0,0)          |PNH; Nauwkeurigheid van de liggingsgegevens in het horizontale vlak; keuzelijst [NauwkeurigheidXYvalue]; Nullable: False; Default: None|
|AANTALKABELSLEIDINGEN               |Integer(0,10,0)         |PNH; Aantal kabels en leidingen; Nullable: True|
|DIEPTELEGGING                       |String(255,0,0)         |PNH; FK naar diepteTovMaaiveld_p; Nullable: True; Default: None|
|INNETWERK                           |String(255,0,0)         |PNH; FK naar utiliteitsNet_tbl; Nullable: True; Default: None|
|DATALEVERANCIER                     |String(255,0,0)         |PNH; Leverancier van de data; Nullable: True; Default: None|
|CREATED_USER                        |String(255,0,0)         |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)             |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)          |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)             |PNH; Datum van de laatste mutatie; Nullable: True|
|SHAPE                               |Geometry         |PNH; Vlak|
|SHAPE_Length                        |Double(0,0,0)           |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None|
|SHAPE_Area                          |Double(0,0,0)           |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None|

***