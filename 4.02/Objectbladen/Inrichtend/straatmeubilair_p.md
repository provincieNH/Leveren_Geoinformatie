## AREAALDATA.straatmeubilair_p

$ Feature dataset: Inrichtend

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMGEO
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Een ruimtelijk object ter inrichting van de openbare ruimte. __LET OP:__ in afwijking op de BGT/IMGEO indeling worden abri's als vlak geadministreerd in overigBouwwerk_v en lichtpunten in straatmeubilairLichtpunt_p.

***

|KOLOM                             |TYPE          	|DEFINITIE|
|------                          	|----          	|-----    |
|OBJECTID                            |OID(38,0,0)         |Interne ID ArcGIS - Nullable: False|
|BGTPLUSTYPE                         |String(50,0,0)      |Beschrijving - keuzelijst [typeSTM] Nullable: False Default: None|
|IDENTIFICATIE                       |String(255,0,0)      |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|STATUS                              |String(10,0,0)       |Beschrijving - keuzelijst [status] Nullable: False Default: :bestaand|
|BRONHOUDER                          |String(5,0,0)        |BGT, De bronhoudercode van het object, keuzelijst [bronhouder] - Nullable: False Default: None|
|INONDERZOEK                         |String(1,0,0)        |BGT, Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N|
|RELATIEVEHOOGTELIGGING              |SmallInteger(0,10,0) |BGT, Aanduiding voor de relatieve hoogte van het object - Nullable: False Default: 0|
|TIJDSTIPREGISTRATIE                 |Date(8,0,0)          |Beschrijving - keuzelijst [] Nullable: True Default: None|
|EINDREGISTRATIE                     |Date(8,0,0)          |Beschrijving - keuzelijst [] Nullable: True Default: None|
|LV_PUBLICATIEDATUM                  |Date(8,0,0)          |BGT, Tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening - Nullable: True|
|BERICHT_ID                          |String(128,0,0       |Beschrijving - keuzelijst [] Nullable: True Default: None|
|SHAPE                               |Geometry(0,0,0)      |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecSTM] - Nullable: True Default: None|
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
|EIGENAAR                            |String(255,0,0)    |Eigenaar van het object, keuzelijst [INSTANTIE] - Nullable: True Default: None| 
|DATALEVERANCIER                     |String(255,0,0)    |Leverancier van de data - Nullable: True Default: None|
|HOOGTE                              |SmallInteger(0,10,0)|Hoogte van het lichtpunt (m - Nullable: True|
|MATERIAALTYPE                       |String(255,0,0)     |Materiaalkeuze, keuzelijst [MATERIAALTYPE] - Nullable: True Default: None|
|ZIJDE                               |String(255,0,0)     |Zijde, keuzelijst [ZIJDE] - Nullable: True Default: None|
|HECTOMETER                          |String(255,0,0)     |Hectometrering - Nullable: True Default: None|
|MAXIMALEKRACHT                      |String(255,0,0)     |Maximale toegestaan kracht op de bolder (Newton? TODO) - Nullable: True Default: None|
|TRAJECT                             |String(255,0,0)     |FK naar traject_v - Nullable: True Default: None|
|CONTACTPERSOON                      |String(255,0,0)     |Contactpersoon namens de herdenkers - Nullable: True Default: None|
|DATUMAANLEG                         |Date(8,0,0)         |Datum Aanleg - Nullable: True|
|FOTO                                |String(255,0,0)     |Pad naar de foto TODO - Nullable: True Default: None|
|LOCATIE                             |String(255,0,0)     |Zijweg - Nullable: True Default: None|
|OPMERKING                           |String(3000,0,0)    |Opmerking - Nullable: True Default: None|
|RECREATIEPLEK                       |String(255,0,0)     |FK naar recreatieplek_v - Nullable: True Default: None|
|DATUMGARANTIE                       |Date(8,0,0)          |Datum garantie  - Nullable: True|
|DATUMPLAATSING                      |Date(8,0,0)          |Datum aanleg - Nullable: True Default: None|
|JAAR_PLAATSING_AANLEG_GESCHAT       |String(1,0,0)        |Jaar plaatsing of aanleg is geschat: ja of nee : keuzelijst [jaNee] Nullable: True Default: N|
|OMSCHRIJVING                        |String(255,0,0)      |Extra toelichting - Nullable: True Default: None|
|MATERIAALTYPE                       |String(255,0,0)      |Type materiaal, keuzelijst [MATERIAALTYPE] - Nullable: True Default: None|
|LENGTE                              |SmallInteger(0,10,0) |Lengte van de boom (m) - Nullable: True|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0) |Levensverwachting (jaar TODO) - Nullable: True|
|PLANJAAR                            |SmallInteger(0,10,0) |Planjaar - Nullable: True|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0) |Restlevensduur - Nullable: True|
|FABRIKANTTYPECODE                   |String(255,0,0)      |Fabrikanttypecode, keuzelijst [FABRIKANT_TYPECODE] - Nullable: True Default: None|
|WEG                                 |Guid(38,0,0)         |FK naar weg_l|

***
