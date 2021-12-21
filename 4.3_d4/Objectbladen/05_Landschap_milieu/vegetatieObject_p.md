## AREAALDATA.vegetatieObject_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Een opgaande beplanting met een stam en boomkroon. Verschijningsvorm: vrijuit groeiend, geknot of in gesnoeide vorm. Hoogte groter dan 1 meter en/of stamdikte groter dan 5 centimeter
* __Mapping_BGT:_ vegetatieObject_p
* __Mapping_Gisib:__ Boom
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                          |__TYPE (length, precision, scale)__            |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                          	|----                                           |-----    |
|OBJECTID                           |OID(38,0,0)                                    |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                           |GlobalID(38,0,0)                               |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                              |TEXT(255,0,0)                                  |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                           |LONG(0,10,0)                                   |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                  |TEXT(255,0,0)                                  |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                    |DATE(8,0,0)                                    |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                     |DATE(8,0,0)                                    |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING             |SHORT(0,5,0)                                   |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                          |TEXT(255,0,0)                                  |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                        |TEXT(255,0,0)                                  |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                           |TEXT(255,0,0)                                  |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                           |TEXT(255,0,0)                                  |PNH; Nadere typering van het object; keuzelijst [typeSpecVGOPunt]; Nullable: True; Default: None; Visible: Yes|
|BGTPLUSTYPE                        |TEXT(50,0,0)                                   |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeVGOPunt]; Nullable: False; Default: None; Visible: No|
|AFSTANDVERHARDING                  |FLOAT(0,25,10)                                 |PNH; Afstand tot de verharding in meters, 2 decimalen; ; Nullable: True; Default: None; Visible: Yes|
|BOOMSITUERING                      |TEXT(255,0,0)                                  |PNH; Situering van de boom; keuzelijst [PLANT_SITUERING]; Nullable: True; Default: None; Visible: Yes|
|BOOMSOORT                          |TEXT(255,0,0)                                  |PNH; Boomsoort; keuzelijst [BOOMSOORT]; Nullable: True; Default: None; Visible: Yes|
|DATUMAANPLANTING                   |DATE(8,0,0)                                    |PNH; Jaar aanplanting; ; Nullable: True; Default: None; Visible: No|
|DATUM_LAATSTE_ONDERH               |DATE(8,0,0)                                    |PNH; Datum laatst onderhoud; ; Nullable: True; Default: None; Visible: No|
|DIAMETER                           |TEXT(50,0,0)                                   |PNH; Diameter in cm; keuzelijst [DIAMETER] ; Nullable: True; Default: None; Visible: Yes|
|STREEFBEELD                        |TEXT(255,0,0)                                  |PNH; Concrete visuele doelstelling; keuzelijst [EINDBEELD] ; Nullable: True; Default: None; Visible: No|
|HECTOMETER                         |TEXT(255,0,0)                                  |PNH; Hectometrering; ; Nullable: True; Default: None; Visible: Yes|
|INSPECTEUR                         |TEXT(255,0,0)                                  |PNH; Naam van de inspecteur die laatste inspectie heeft uitgevoerd; ; Nullable: True; Default: None; Visible: No|
|DATUM_INSPECTIE                    |DATE(8,0,0)                                    |PNH; Datum laatste inspectie; ; Nullable: True; Default: None; Visible: No|
|MONUMENT                           |TEXT(20,0,0)                                   |PNH; Monumentale status; keuzelijst [BOOMMONUMENTSOORT]; Nullable: True; Default: None; Visible: No|
|WORTELDOEK_SCHERM                  |TEXT(20,0,0)                                   |PNH; Aanwezigheid van een worteldoek of wortelscherm; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: Yes|
|OPMERKING                          |TEXT(255,0,0)                                  |PNH; Algemene opmerking voor het object, gebruik voor planter en garantie ja/nee bij bomen tot 4 jaar; ; Nullable: True; Default: None; Visible: Yes|
|PLANJAAR                           |SHORT(0,5,0)                                   |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|GROEIPLAATSINRICHTING              |TEXT(255,0,0)                                  |NIB; Toegepaste constructie en hoofdsamenstelling van de groeiplaats/bodem; keuzelijst [Groeiplaatsinrichting]; Nullable: True; Default: None; Visible: No|
|SNOEIFASE                          |TEXT(255,0,0)                                  |PNH; Snoeifase; keuzelijst [SNOEIFASE]; Nullable: True; Default: None; Visible: Yes|
|TERMIJN_UITVOERING                 |TEXT(255,0,0)                                  |PNH; Termijn waarbinnen de geadviseerde maatregelen uitgevoerd dienen te worden; ; Nullable: True; Default: None; Visible: No|
|ZIJDE                              |TEXT(10,0,0)                                   |PNH; Zijde; keuzelijst [Zijde]; Nullable: True; Default: None; Visible: Yes|
|JAAR_PLAATSING_AANLEG_GESCHAT      |TEXT(1,0,0)                                    |PNH; Jaar plaatsing of aanleg is geschat: Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|TRAJECT                            |TEXT(255,0,0)                                  |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM]; Nullable: True; Default: None; Visible: Yes|
|DATALEVERANCIER                    |TEXT(255,0,0)                                  |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                       |TEXT(255,0,0)                                  |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                       |DATE(8,0,0)                                    |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                   |TEXT(50,0,0)                                   |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                   |DATE(8,0,0)                                    |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                              |Geometry(0,0,0)                                |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|


***
