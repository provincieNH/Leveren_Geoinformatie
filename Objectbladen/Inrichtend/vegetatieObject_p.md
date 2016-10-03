## AREAALDATA.vegetatieObject_p

$ Feature dataset: Inrichtend

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Een opgaande beplanting met een stam en boomkroon. Verschijningsvorm: vrijuit groeiend, geknot of in gesnoeide vorm. Hoogte groter dan 1 meter en/of stamdikte groter dan 5 centimeter

***

|KOLOM                             |TYPE          	|DEFINITIE|
|------                          	|----          	|-----    |
|BGTPLUSTYPE                        |String(50,0,0)      |Beschrijving - keuzelijst [typeVGOPunt] Nullable: False Default: None|
|IDENTIFICATIE                      |String(255,0,0)     |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|STATUS                             |String(10,0,0)      |Beschrijving - keuzelijst [status] Nullable: False Default: :bestaand|
|BRONHOUDER                         |String(5,0,0)       |BGT, De bronhoudercode van het object, keuzelijst [bronhouder] - Nullable: False Default: None|
|INONDERZOEK                        |String(1,0,0)       |BGT, Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N|
|RELATIEVEHOOGTELIGGING             |SmallInteger(0,10,0)|BGT, Aanduiding voor de relatieve hoogte van het object - Nullable: False Default: 0|
|TIJDSTIPREGISTRATIE                |Date(8,0,0)         |Beschrijving - keuzelijst [] Nullable: True Default: None|
|EINDREGISTRATIE                    |Date(8,0,0)         |Beschrijving - keuzelijst [] Nullable: True Default: None|
|LV_PUBLICATIEDATUM                 |Date(8,0,0)         |BGT, Tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening - Nullable: True|
|BERICHT_ID                         |String(128,0,0)     |Beschrijving - keuzelijst [] Nullable: True Default: None|
|SHAPE                              |Geometry(0,0,0)     |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecVGOPunt] - Nullable: True Default: None|
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
|AFSTANDVERHARDING                   |Float(0,25,10)      |Afstand tot de verharding in meters, 2 decimalen - Nullable: True|
|BEREIKBAARMETHOOGW                  |String(1,0,0)       |Is de boom bereikbaar met een hoogwerker -  Ja/Nee, keuzelijst [jaNee] Nullable: True Default: N|
|BIJZONDERHEID                       |String(255,0,0)     |TODO - Nullable: True Default: None|
|BOOMSITUERING                       |String(255,0,0)     |Situering van de boom, keuzelijst [PLANT_SITUERING] - Nullable: True Default: None|
|BOOMPAAL                            |String(1,0,0)       |Boompaal aanwezig Ja/Nee, keuzelijst [jaNee] Nullable: True Default: N|
|BOOMSOORT                           |String(255,0,0)     |Boomsoort, keuzelijst [BOOMSOORT] - Nullable: True Default: None|
|DATUMAANPLANTING                    |SmallInteger(0,4,0)      |Jaar aanplanting - Nullable: True|
|DATUM_LAATSTE_ONDERH                |Date(8,0,0)         |Datum laatst onderhoud - Nullable: True|
|DIAMETER                            |SmallInteger(0,10,0)|Diameter op 1.30m - Nullable: True|
|EINDBEELD                           |String(255,0,0)     |Eindbeeld - Nullable: True Default: None|
|HECTOMETER                          |String(255,0,0)     |Hectometrering - Nullable: True Default: None|
|HOOGTEKLASSE                        |String(255,0,0)     |Hoogtekklasse, keuzelijst [HOOGTEKLASSE] - Nullable: True Default: None|
|ANTIMAAISCHADE_PAALTJES             |String(1,0,0) 	  |Aanwezigheid anti-maaischade paaltjes: Ja/Nee, keuzelijst [jaNee] Nullable: True Default: N|
|INSPECTEUR                          |String(255,0,0)     |Naam van de inspecteur die laatste inspectie heeft uitgevoerd - Nullable: True Default: None|
|DATUM_INSPECTIE                     |Date(8,0,0)         |Datum laatste inspectie - Nullable: True|
|MONUMENT                            |String(255,0,0)     |Monumentale boom, keuzelijst [MONUMENT] - Nullable: True Default: None|
|OMSCHRIJVING                        |String(255,0,0)     |Extra toelichting - Nullable: True Default: None|
|PLANJAAR                            |SmallInteger(0,10,0)|Planjaar van de boom - attribuut bestemd voor onderhoudsplanning - Nullable: True|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0)|Restlevensduur - Nullable: True|
|SNOEIFASE                           |String(255,0,0)     |Snoeifase, keuzelijst [SNOEIFASE] - Nullable: True Default: None|
|TERMIJN_UITVOERING                  |String(255,0,0)     |Termijn waarbinnen de geadviseerde maatregelen uitgevoerd dienen te worden. - Nullable: True Default: None|
|ZIJDE                               |String(255,0,0)     |Zijde, keuzelijst [ZIJDE] - Nullable: True Default: None|
|WIJZEVANINWINNING                   |String(255,0,0)     |Wijze van inwinning gegevens - Nullable: True Default: None|
|VRIJETAKVALMOGELIJ                  |String(1,0,0)       |Is vrije takval bij snoeien mogelijk -  Ja/Nee, keuzelijst [jaNee] Nullable: True Default: N|
|JAAR_PLAATSING_AANLEG_GESCHAT       |String(1,0,0)       |Jaar plaatsing of aanleg is geschat: Ja/Nee - keuzelijst [jaNee] - Nullable: True Default: N|
|TRAJECT                             |String(255,0,0)     |FK naar traject_v - Nullable: True Default: None|

***
