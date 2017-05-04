## AREAALDATA.bordScheepvaart_p

$ Feature dataset: Inrichtend

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH/IMGEO
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Een paneel waarop informatie wordt afgebeeld, specifiek bedoelt voor de scheepvaart.

***

|KOLOM                             |TYPE          	|DEFINITIE|
|------                          	|----          	|-----    |
|BGTPLUSTYPE                        |String(50,0,0)       |Beschrijving - keuzelijst [typeBRD] Nullable: False Default: None|
|IDENTIFICATIE                      |String(255,0,0)      |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|STATUS                             |String(10,0,0)       |Beschrijving - keuzelijst [status] Nullable: False Default: :bestaand|
|BRONHOUDER                         |String(5,0,0)        |BGT, De bronhoudercode van het object, keuzelijst [bronhouder] - Nullable: False Default: None|
|INONDERZOEK                        |String(1,0,0)        |BGT, Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N|
|RELATIEVEHOOGTELIGGING             |SmallInteger(0,10,0) |BGT, Aanduiding voor de relatieve hoogte van het object - Nullable: False Default: 0|
|TIJDSTIPREGISTRATIE                |Date(8,0,0)          |Beschrijving - keuzelijst [] Nullable: True Default: None|
|EINDREGISTRATIE                    |Date(8,0,0)          |Beschrijving - keuzelijst [] Nullable: True Default: None|
|LV_PUBLICATIEDATUM                 |Date(8,0,0)          |BGT, Tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening - Nullable: True|
|BERICHT_ID                         |String(128,0,0)      |Beschrijving - keuzelijst [] Nullable: True Default: None|
|SHAPE                              |Geometry(0,0,0)      |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecBRDScheepvaart] - Nullable: True Default: None|
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
|ZIJDE                               |String(255,0,0)     |Zijde, keuzelijst [ZIJDE] - Nullable: True Default: None|
|RVVTYPEBORD                         |String(255,0,0)     |RVV Type Bord - Nullable: True Default: None|
|TEKSTBVBORD                         |String(255,0,0)     |Tekst of beeld op het bovenbord dat aan de (weg)gebruiker wordt getoond - Nullable: True Default: None|
|TEKSTHOOFDBORD                      |String(255,0,0)     |Tekst of beeld op het hoofdbord dat aan de (weg)gebruiker wordt getoond - Nullable: True Default: None|
|TEKSTONDERBORD                      |String(255,0,0)     |Tekst of beeld op het onderbord dat aan de (weg)gebruiker wordt getoond - Nullable: True Default: None|
|BORDFABRIKANT                       |String(255,0,0)     |Bord Fabrikant, keuzelijst [BORD_FABRIKANT] - Nullable: True Default: None|
|BIJZONDERHEID                       |String(255,0,0)     |Bijzonderheden - Nullable: True Default: None|
|DATUMPLAATSING                      |Date(8,0,0)         |Datum plaatsing - Nullable: True|
|OPMERKING                           |String(3000,0,0)    |Opmerking (niet bijzonderheid, dat is een ander veld) - Nullable: True Default: None|
|FOTO                                |String(255,0,0)     |Pad naar de foto TODO - Nullable: True Default: None|
|HECTOMETER                          |String(255,0,0)     |Hectometrering - Nullable: True Default: None||
|HOOGTE                              |SmallInteger(0,10,0)|Hoogte waarop het bord zit(eenheid? TODO) - Nullable: True|
|HOOGTEPALEN                         |Float(0,25,10)      |Hoogte van de paal waarop het bord zit(eenheid? TODO) - Nullable: True|
|LEESZIJDE                           |String(255,0,0)     |TODO - Nullable: True Default: None|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)|Levensverwachting van het bord toen het geplaatst werd(jaren) TODO - Nullable: True|
|PLANJAAR                            |SmallInteger(0,10,0)|Planjaar TODO - Nullable: True|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0)|Verwachte restlevensduur vanaf moment inspect (waar wordt inspectiedatum ingevuld?) TODO - Nullable: True|
|ROTATIEHOEK                         |SmallInteger(0,10,0)|Orientatie van het bord - Nullable: True|
|CEKEUR                              |String(255,0,0)     |CE-Keurmerk aanwezig - Nullable: True Default: None|
|GARANTIECERTIFICAAT                 |String(255,0,0)     |Garantie certificaat aanwezig - Nullable: True Default: None|
|REFLECTIEWAARDE                     |String(255,0,0)     |Gemeten Reflectiewaarde - Nullable: True Default: None|
|REFLECTIEWAARDE_DATUM               |Date(8,0,0)         |Datum reflectiemeting - Nullable: True|
|TRAJECT                             |String(255,0,0)     |FK naar traject_v - Nullable: True Default: None|



***
