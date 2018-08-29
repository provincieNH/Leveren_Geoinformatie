## AREAALDATA.bordWegwijzer_p

$ Feature dataset: Inrichtend

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH/IMGEO
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Constructie voorzien van een of meer panelen met informatie ten behoeve van de bewegwijzering
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
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecBRDWegwijzer] - Nullable: True Default: None|
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
|FABRIKANT                           |String(255,0,0)     |Fabrikant - Nullable: True Default: None|
|TYPELAMP                            |String(255,0,0)     |Type Lamp, keuzelijst [TYPE_LAMP] - Nullable: True Default: None|
|REFLECTIEKLASSE                     |String(255,0,0)     |Reflectieklasse, keuzelijst [REFLECTIEKLASSE] - Nullable: True Default: None|
|AFMETINGEN                          |String(255,0,0)     |Maatvoering bord: breedte x hoogte (mm x mm? TODO)- Nullable: True Default: None|
|AFMETINGENONDERBOR                  |String(255,0,0)     |Maatvoering onderbord: breedte x hoogte (mm x mm? TODO)- Nullable: True Default: None|
|ANWBNUMMER                          |String(255,0,0)     |ANWB nummer- Nullable: True Default: None|
|HECTOMETER                          |String(255,0,0)     |Hectometrering- Nullable: True Default: None|
|KLEURSTELLING                       |String(255,0,0)     |Kleurstelling (Richtlijn? TODO)- Nullable: True Default: None|
|KLOKSTAND                           |String(255,0,0)     |De klokstand van de bewegwijzer uitgedrukt in 12 standen- Nullable: True Default: None|
|LETTERHOOGTE                        |String(255,0,0)     |Letterhoogte (Richtlijn? TODO)- Nullable: True Default: None|
|LICHTPUNTHOOGTE                     |SmallInteger(0,10,0)|Lichtpunthoogte- Nullable: True|
|NUMMER                              |String(255,0,0)     |Unieke nummer van wegwijzer- Nullable: True Default: None|
|ONDERKANTBORD                       |String(255,0,0)     |Afstand van onderkant van bord tot maaiveld niveau (cm? TODO)- Nullable: True Default: None|
|ONDERSTEUNINGSCONS                  |String(255,0,0)     |Ondersteuningscontructie - Nullable: True Default: None|
|ONTWERPDATUM                        |Date(8,0,0)         |Ontwerpdatum - Nullable: True|
|TYPEUITHOUDER                       |String(255,0,0)     |TypeUithouder (geen FK? TODO) - Nullable: True Default: None|
|UITVOERING                          |String(255,0,0)     |Uitvoering (TODO) - Nullable: True Default: None|
|VERLICHT                            |String(255,0,0)     |Verlicht: Ja/Nee/Onbekend, keuzelijst [jaNeeOnbekend] Nullable: True Default: O|
|VERVANGINGSKOSTEN                   |SmallInteger(0,10,0)|TODO - Nullable: True|
|VORMGEVING                          |String(255,0,0)     |Vormgeving (Richtlijn? TODO) - Nullable: True Default: None|
|ZIJDE                               |String(255,0,0)     |Zijde, keuzelijst [ZIJDE] - Nullable: True Default: None|
|DATUMPLAATSING                      |Date(8,0,0)         |Datum plaatsing - Nullable: True|
|OMSCHRIJVING                        |String(255,0,0)     |Omschrijving - Nullable: True Default: None|
|FOTO                                |String(255,0,0)     |Pad naar de foto TODO - Nullable: True Default: None|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)|Levensverwachting van het bord toen het geplaatst werd(jaren) TODO - Nullable: True|
|PLANJAAR                            |SmallInteger(0,10,0)|Planjaar TODO - Nullable: True|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0)|Verwachte restlevensduur vanaf moment inspect (waar wordt inspectiedatum ingevuld?) TODO - Nullable: True|


***
