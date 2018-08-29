## AREAALDATA.ondersteunendWegdeel_v

$ Feature dataset: Opdelend

* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ Bij FysiekVoorkomen: gesloten verharding en open verharding 7,5 cm (NB, groter dan BGT) Bij FysiekVoorkomen: onverhard, half verhard en groenvoorziening 25 cm (NB, groter dan BGT)
* __Geometrie:__ Vlak
* __Definitie:__ Een deel van de weg dat niet primair bedoeld is voor gebruik door het verkeer. Dit omvat o.a. verkeerseiland en berm daar waar de berm onderdeel uitmaakt van de constructie van de weg.

***

|KOLOM                              |TYPE          	        |DEFINITIE|
|------                          	|----          	        |-----    |
|FYSIEKVOORKOMEN                    |String(50,0,0)         |Beschrijving - keuzelijst [fysiekVoorkomenOWG] Nullable: False Default: None|
|FUNCTIE                            |String(50,0,0)         |Beschrijving - keuzelijst [functieOWG] Nullable: False Default: None|
|OPTALUD                            |String(1,0,0)          |Beschrijving - keuzelijst [jaNeeOnbekend] Nullable: True Default: N|
|IDENTIFICATIE                      |String(255,0,0)        |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|STATUS                             |String(10,0,0)         |Beschrijving - keuzelijst [status] Nullable: False Default: :bestaand|
|BRONHOUDER                         |String(5,0,0)          |BGT, De bronhoudercode van het object, keuzelijst [bronhouder] - Nullable: False Default: None|
|INONDERZOEK                        |String(1,0,0)          |BGT, Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N|
|RELATIEVEHOOGTELIGGING             |SmallInteger(0,10,0)   |BGT, Aanduiding voor de relatieve hoogte van het object - Nullable: False Default: 0|
|TIJDSTIPREGISTRATIE                |Date(8,0,0)            |Beschrijving - keuzelijst [] Nullable: True Default: None|
|EINDREGISTRATIE                    |Date(8,0,0)            |Beschrijving - keuzelijst [] Nullable: True Default: None|
|LV_PUBLICATIEDATUM                 |Date(8,0,0)            |BGT, Tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening - Nullable: True|
|BERICHT_ID                         |String(128,0,0)        |Beschrijving - keuzelijst [] Nullable: True Default: None|
|SHAPE                              |Geometry(0,0,0)        |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Length                       |Double(0,0,0)          |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Area                         |Double(0,0,0)          |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecOWE] - Nullable: True Default: None|
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
|TYPEBEHEER                          |String(255,0,0)       |Type beheer (maaien, klepelen, uitzuigen etc), keuzelijst, [TYPE_BEHEER] - Nullable: True Default: None|
|TYPEPLAAGSOORT                      |String(255,0,0)       |Type plaagsoort, keuzelijst [TYPE_PLAAGSOORT] - Nullable: True Default: None|
|ZIJDE                               |String(255,0,0)       |Zijde (vd weg), keuzelijst [ZIJDE] - Nullable: True Default: None|
|ACTUEELBEELD                        |String(255,0,0)       |Huidig beeld van begroeiing - Nullable: True Default: None|
|BIJZONDEREWAARDE                    |String(255,0,0)       |Indicatie van bijzondere waarde - Nullable: True Default: None|
|BOLGEWAS                            |String(255,0,0)       |Welk bolgewas er aanwezig is - Nullable: True Default: None|
|DATUMAANPLANTING                    |Date(8,0,0)           |Datum aanplanting - Nullable: True|
|OMSCHRIJVING                        |String(255,0,0)       |Extra toelichting - Nullable: True Default: None|
|HMBEGIN                             |Float(,25,10)         |Hectometrering begin berm - Nullable: True|
|HMEIND                              |Float(,25,10)         |Hectometrering eind berm - Nullable: True|
|LENGTE                              |SmallInteger(0,10,0)  |Lengte - Nullable: True|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)  |Levensverwachting - Nullable: True|
|OPMERKINGMBTONDERH                  |String(255,0,0)       |Opmerking mbt onderhoud - Nullable: True Default: None|
|PLANJAAR                            |SmallInteger(0,10,0)  |Planjaar - Nullable: True|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0)  |Restlevensduur - Nullable: True|
|STREEFBEELD                         |String(255,0,0)       |Streefbeeld begroeiing - Nullable: True Default: None|
|TALUD                               |String(255,0,0)       |Of berm op Talud ligt - Nullable: True Default: None|
|TALUDVERHOUDING                     |String(255,0,0)       |Talud verhouding - Nullable: True Default: None|
|BERMFUNCTIE                         |String(255,0,0)       |Berm functie, keuzelijst [BERM_FUNCTIE] - Nullable: True Default: None|
|GRONDSOORT                          |String(255,0,0)       |Grondsoort, keuzelijst [GRONDSOORT] - Nullable: True Default: None|
|ZAADMENGSEL                         |String(255,0,0)       |Zaadmengsel, keuzelijst [ZAADMENGSEL] - Nullable: True Default: None|
|DATUMAANPLANTINGGESCHAT             |String(255,0,0)       |Indicatie of datum aanplanting geschat is - Nullable: True Default: None|
|OEVERVAK                            |String(255,0,0)       |FK naar oevervak_v - (als berm langs vaarweg ligt) - Nullable: True Default: None|
|TRAJECT                             |String(255,0,0)       |FK naar traject_v - Nullable: True Default: None - Nullable: True Default: None|
|SITUERING                           |String(255,0,0)       |Situering conform CROW, keuzelijst [SITUERING] - Nullable: True Default: None|
|JAARAANLEG                          |SmallInteger(0,10,0)  |Jaar aanleg van de weg - Nullable: True|
|VERHARDINGCATEGORIE                 |String(255,0,0)       |Verharding categorie conform CROW, keuzelijst [VERHARDING_CATEGORIE] - Nullable: True Default: None|
|VERHARDING                          |String(255,0,0)       |Verharding object conform CROW, keuzelijst [VERHARDING] - Nullable: True Default: None|
|GEBRUIKSFUNCTIE                     |String(255,0,0)       |Gebruiksfunctie conform CROW, keuzelijst [GEBRUIKSFUNCTIE] - Nullable: True Default: None|
|OPPERVLAKTE                         |Float(,25,10)         |Oppervlakte van het wegvakonderdeel (m2, 2 decimalen) - Nullable: True|
|WEGVAK                              |String(255,0,0)       |FK naar wegvak_v - Nullable: True Default: None|

***
