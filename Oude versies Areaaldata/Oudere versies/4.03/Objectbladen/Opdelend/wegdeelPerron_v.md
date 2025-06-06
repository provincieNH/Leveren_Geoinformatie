## AREAALDATA.wegdeelPerron_v

$ Feature dataset: Opdelend

* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ BGT
* __Positionele nauwkeurigheid:__ 7,5 cm (NB, groter dan BGT)
* __Geometrie:__ Vlak
* __Definitie:__ Kleinste functioneel onafhankelijk stuk van een NEN 3610 Weg met gelijkblijvende, homogene eigenschappen
en relaties en primair bedoeld voor gebruik door weg-, spoor- en vliegverkeer te land. __LET OP:__ In dit objecttype worden die delen van een BGT Voetpad opgenomen die als perron bij een bushalte in gebruik zijn. 

***

|KOLOM                               |TYPE          	    |DEFINITIE|
|------                              |----          	    |-----    |
|OBJECTID                            |OID(38,0,0)         |Interne ID ArcGIS - Nullable: False|
|FYSIEKVOORKOMEN                     |String(50,0,0)      |Beschrijving - keuzelijst [fysiekVoorkomenWGDP] Nullable: False Default: None|
|FUNCTIE                             |String(50,0,0)      |Beschrijving - keuzelijst [functieWGD] Nullable: False Default: None|
|OPTALUD                             |String(1,0,0)       |Beschrijving - keuzelijst [jaNeeOnbekend] Nullable: True Default: N|
|IDENTIFICATIE                       |String(255,0,0)     |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|STATUS                              |String(10,0,0)      |Beschrijving - keuzelijst [status] Nullable: False Default: :bestaand|
|BRONHOUDER                          |String(5,0,0)       |BGT, De bronhoudercode van het object, keuzelijst [bronhouder] - Nullable: False Default: None|
|INONDERZOEK                         |String(1,0,0)       |BGT, Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N|
|RELATIEVEHOOGTELIGGING              |SmallInteger(0,10,0)|BGT, Aanduiding voor de relatieve hoogte van het object - Nullable: False Default: 0|
|TIJDSTIPREGISTRATIE                 |Date(8,0,0)         |Beschrijving - keuzelijst [] Nullable: True Default: None|
|EINDREGISTRATIE                     |Date(8,0,0)         |Beschrijving - keuzelijst [] Nullable: True Default: None|
|LV_PUBLICATIEDATUM                  |Date(8,0,0)         |BGT, Tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening - Nullable: True|
|BERICHT_ID                          |String(128,0,0)     |Beschrijving - keuzelijst [] Nullable: True Default: None|
|SHAPE                               |Geometry(0,0,0)     |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Length                        |Double(0,0,0)       |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Area                          |Double(0,0,0)       |Beschrijving: - keuzelijst [] Nullable: True Default: None|
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
|PERRONIDENTIFICATIE                 |String(255,0,0)    |Halte identificatie conform NDOV QUAY - Nullable: True Default: None|
|VERLICHTING_AANW                    |String(1,0,0)      |Verlichting aanwezig : Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N|
|TOV                                 |String(1,0,0)      |Voldoet aan richtlijnen TOV : Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N|
|GLADHEIDSBESTRIJDING                |String(1,0,0)      |Gladheidsbestrijding wordt uitgevoerd : Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N|
|GLADHEIDSBESTRIJDING_PARTIJ         |String(255,0,0)    |Naam van de uitvoerende organisatie Gladheidsbestrijding - Nullable: True Default: None|
|VERWARMING_AANW                     |String(1,0,0)      |Verwarming aanwezig : Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N|
|MATERIAAL                           |String(255,0,0)    |Materiaaltpye Perron - Nullable: True Default: None|
|BLINDEGELEIDESTR_AANW               |String(1,0,0)      |Blindegeleidestrook aanwezig : Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N|
|HOOGTE                              |Float(0,10,3)      |Hoogte in Meters, 2 decimalen - Nullable: True|
|LENGTE                              |Float(0,10,3)      |Lengte in Meters, 2 decimalen - Nullable: True|
|BREEDTE                             |Float(0,10,3)      |Breedte in Meters, 2 decimalen - Nullable: True|
|HEKWERK_AANW                        |String(1,0,0)      |Hekwerk aanwezig : Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N|
|HALTEPAAL_AANW                      |String(1,0,0)      |Haltepaal aanwezig : Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N|
|AANPASSING_VISUEEL_BEPERKTEN        |String(1,0,0)      |Aanpassing visueel beperkten : Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N|
|MARKERING_PERRONRAND                |String(1,0,0)      |Markering perronrand : Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N|
|NIVEAU                              |SmallInteger(0,3,0)|ToDo - Nullable: True|
|HALTE                               |String(255,0,0)       |FK naar halte_v - Nullable: True Default: None|
|TRAJECT                             |String(255,0,0)       |FK naar traject_v - Nullable: True Default: None|
|MAST                                |String(255,0,0)     |FK naar mastDraagconstructie_p  - Nullable: True Default: None|

***
