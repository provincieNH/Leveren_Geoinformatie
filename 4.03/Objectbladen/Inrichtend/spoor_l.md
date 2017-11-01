## AREAALDATA.spoor_l

$ Feature dataset: Inrichtend

* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ BGT
* __Positionele nauwkeurigheid:__ 
* __SHAPE:__ Lijn
* __Definitie:__ De as van het spoor, dat wil zeggen het midden van twee stalen staven op een onderling vaste afstand, waarover trein, tram, of sneltram rijdt. __LET OP:__ Dit is het officiele BGT objecttype. spoorrail_l is het 'oude' objecttype wat op termijn uitgefaseerd zal worden.

***

|KOLOM                              |TYPE          	      |DEFINITIE|
|------                          	|----          	      |-----    |
|OBJECTID                           |OID(38,0,0)          |Interne ID ArcGIS - Nullable: False|
|FUNCTIE                            |String(50,0,0)       |Beschrijving - keuzelijst [functieSPRLijn] Nullable: False Default: None|
|IDENTIFICATIE                      |String(255,0,0)      |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|STATUS                             |String(10,0,0)       |Beschrijving - keuzelijst [status] Nullable: False Default: :bestaand|
|VERWERKINGSSTATUS                  |String(255,0,0)    |Status van de gegevens, keuzelijst [VERWERKINGSSTATUS] - Nullable: False Default: Nieuw|
|OBJECTBEGINTIJD                    |Date(8,0,0)          |BGT, Datum waarop het object bij de bronhouder is ontstaan - Nullable: False|
|OBJECTEINDTIJD                     |Date(8,0,0)          |BGT, Datum waarop het object bij de bronhouder niet meer geldig is - Nullable: True|
|BRONHOUDER                         |String(5,0,0)        |BGT, De bronhoudercode van het object, keuzelijst [bronhouder] - Nullable: False Default: None|
|INONDERZOEK                        |String(1,0,0)        |BGT, Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N|
|RELATIEVEHOOGTELIGGING             |SmallInteger(0,10,0) |BGT, Aanduiding voor de relatieve hoogte van het object - Nullable: False Default: 0|
|TIJDSTIPREGISTRATIE                |Date(8,0,0)          |Beschrijving - keuzelijst [] Nullable: True Default: None|
|EINDREGISTRATIE                    |Date(8,0,0)          |Beschrijving - keuzelijst [] Nullable: True Default: None|
|LV_PUBLICATIEDATUM                 |Date(8,0,0)          |BGT, Tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening - Nullable: True|
|BERICHT_ID                         |String(128,0,0)      |Beschrijving - keuzelijst [] Nullable: True Default: None|
|GISIB_ID                           |Integer(0,10,0)      |ID beheer openbare ruimte (GISIB) - Nullable: True|
|AD_ID                              |String(255,0,0)      |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]' - Nullable: False Default: None|
|GLOBALID                           |GlobalID(38,0,0)     |Global Unique Identifier - Nullable: False|
|CREATED_USER                       |String(255,0,0)      |Naam van gebruiker die de rij heeft aangemaakt - Nullable: True Default: None|
|CREATED_DATE                       |Date(8,0,0)          |Aanmaakdatum - Nullable: True|
|LAST_EDITED_USER                   |String(50,0,0)       |Naam van gebruiker die de laatste mutatie heeft doorgevoerd - Nullable: True Default: None|
|LAST_EDITED_DATE                   |Date(8,0,0)          |Datum van de laatste mutatie - Nullable: True|
|SHAPE                              |Geometry(0,0,0)      |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Length                       |Double(0,0,0)        |Beschrijving: - keuzelijst [] Nullable: True Default: None|


***
