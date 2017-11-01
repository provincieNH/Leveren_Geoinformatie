## AREAALDATA.bord_p

$ Feature dataset: Inrichtend

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH/IMGEO
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Een paneel waarop informatie wordt afgebeeld. Dit zijn zowel RVV borden als bijvoorbeeld DRIS Panelen (voor OV reizigers) en matrix borden (voor automobilisten) - DRIP panelen zijn in Areaaldata te vinden als matrix borden met een TOPdesk ID
__LET OP:__ Bebording voor scheepvaartverkeer, wegwijzers en zwemwaterbebording worden apart geadministreerd.
* __Mapping_BGT:__ bord_p
* __Mapping_Gisib:__ Bord, Typespec=RvvBord; DRIS Paneel, Typespec=DrisPaneel; Matrix, Typespec=Matrix



***

|KOLOM                             |TYPE          	|DEFINITIE|
|------                          	|----          	|-----    |
|BGTPLUSTYPE                        |String(50,0,0)       |Beschrijving - keuzelijst [typeBRD] Nullable: False Default: None Visible:Yes|
|IDENTIFICATIE                      |String(255,0,0)      |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None Visible:No|
|STATUS                             |String(10,0,0)       |Beschrijving - keuzelijst [status] Nullable: False Default: :bestaand Visible:Yes|
|BRONHOUDER                         |String(5,0,0)        |BGT, De bronhoudercode van het object, keuzelijst [bronhouder] - Nullable: False Default: None Visible:Yes|
|INONDERZOEK                        |String(1,0,0)        |BGT, Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N Visible:No|
|RELATIEVEHOOGTELIGGING             |SmallInteger(0,10,0) |BGT, Aanduiding voor de relatieve hoogte van het object - Nullable: False Default: 0 Visible:Yes|
|TIJDSTIPREGISTRATIE                |Date(8,0,0)          |Beschrijving - keuzelijst [] Nullable: True Default: None Visible:No|
|EINDREGISTRATIE                    |Date(8,0,0)          |Beschrijving - keuzelijst [] Nullable: True Default: None Visible:No|
|LV_PUBLICATIEDATUM                 |Date(8,0,0)          |BGT, Tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening - Nullable: True Visible:No|
|BERICHT_ID                         |String(128,0,0)      |Beschrijving - keuzelijst [] Nullable: True Default: None Visible:No|
|SHAPE                              |Geometry(0,0,0)      |Beschrijving: - keuzelijst [] Nullable: True Default: None Visible:Yes|
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecBRD] - Nullable: True Default: None Visible:Yes|
|VERWERKINGSSTATUS                   |String(255,0,0)    |Status van de gegevens, keuzelijst [VERWERKINGSSTATUS] - Nullable: False Default: Nieuw Visible:No|
|OBJECTID                            |OID(38,0,0)        |Interne ID ArcGIS - Nullable: False Visible:No|
|GLOBALID                            |GlobalID(38,0,0)   |Global Unique Identifier - Nullable: False Visible:No|
|GISIB_ID                            |Integer(0,10,0)    |ID beheer openbare ruimte (GISIB) - Nullable: True Visible:No|
|AD_ID                               |String(255,0,0)    |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]' - Nullable: False Default: None Visible:Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)        |Datum waarop het object bij de bronhouder is ontstaan - Nullable: True Visible:No|
|OBJECTEINDTIJD                      |Date(8,0,0)        |Datum waarop het object bij de bronhouder niet meer geldig is - Nullable: True Visible:No|
|CREATED_USER                        |String(255,0,0)    |Naam van gebruiker die de rij heeft aangemaakt - Nullable: True Default: None Visible:No|
|CREATED_DATE                        |Date(8,0,0)        |Aanmaakdatum - Nullable: True Visible:No|
|LAST_EDITED_USER                    |String(50,0,0)     |Naam van gebruiker die de laatste mutatie heeft doorgevoerd - Nullable: True Default: None Visible:No|
|LAST_EDITED_DATE                    |Date(8,0,0)        |Datum van de laatste mutatie - Nullable: True Visible:No|
|BEHEERDER                           |String(255,0,0)    |Beheerder van het object, keuzelijst [BEHEERDER] - Nullable: True Default: None Visible:Yes|
|ONDERHOUDER                         |String(255,0,0)    |Onderhouder van het object, keuzelijst [ONDERHOUDER] - Nullable: True Default: None Visible:Yes|
|EIGENAAR                            |String(255,0,0)    |Eigenaar van het object, keuzelijst [INSTANTIE] - Nullable: True Default: None Visible:Yes| 
|DATALEVERANCIER                     |String(255,0,0)    |Leverancier van de data - Nullable: True Default: None Visible:No|
|ZIJDE                               |String(255,0,0)     |Zijde, keuzelijst [ZIJDE] - Nullable: True Default: None Visible:Yes|
|MATERIAALTYPE                       |String(255,0,0)     |Materiaalkeuze, keuzelijst [MATERIAALTYPE] - Nullable: True Default: None Visible:Yes|
|REFLECTIEKLASSE                     |String(255,0,0)     |Reflectieklasse, keuzelijst [REFLECTIEKLASSE] - Nullable: True Default: None Visible:Yes|
|RVVTYPEBORD                         |String(255,0,0)     |RVV Type Bord - Nullable: True Default: None Visible:Yes|
|WAARDE                              |String(255,0,0)     |De waarde die op het bord staat aangegeven. (Welk bord? bvn, hfd, onder? Ook invullen indien de tekst een waarde bevat? TODO - Nullable: True Default: None Visible:Yes|
|BEVESTIGINGSWIJZE                   |String(255,0,0)     |BevestigingsWijze, keuzelijst [BEVESTIGINGSWIJZE] - Nullable: True Default: None Visible:Yes|
|BORDFABRIKANT                       |String(255,0,0)     |Bord Fabrikant, keuzelijst [BORD_FABRIKANT] - Nullable: True Default: None Visible:Yes|
|HOOGTE                              |SmallInteger(0,10,0)|Hoogte waarop het bord zit(eenheid? TODO) - Nullable: True Visible:Yes|
|AFMETINGEN                          |String(255,0,0)     |Afmeting klasse opgeven, indien afwijkend in mm - Nullable: True Default: None Visible:Yes|
|TYPELAMP                            |String(255,0,0)     |Type Lamp, keuzelijst [TYPE_LAMP] - Nullable: True Default: None Visible:No|
|AANGELICHT                          |String(1,0,0)       |Aangelicht Ja/Nee/Onbekend, keuzelijst [jaNeeOnbekend] Nullable: True Default: O Visible:No|
|BESLUITNUMMER                       |String(255,0,0)     |BesluitNummer (nummer van een besluit van een wegbeheerder om een bepaald verkeersteken te plaatsen, te wijzigen of in te trekken of een bepaalde fysieke maatregel te treffen), keuzelijst [BESLUITNUMMER] - Nullable: True Default: None Visible:No|
|BESLUITDATUM                        |Date(8,0,0)         |Datum dat het besluit - Nullable: True Visible:No|
|DATUMPLAATSING                      |Date(8,0,0)         |Datum plaatsing - Nullable: True Visible:Yes|
|OMSCHRIJVING                        |String(255,0,0)     |Omschrijving - Nullable: True Default: None Visible:No|
|FOTO                                |String(255,0,0)     |Pad naar de foto TODO - Nullable: True Default: None Visible:No|
|HECTOMETER                          |String(255,0,0)     |Hectometrering - Nullable: True Default: None Visible:No|
|LEESZIJDE                           |String(255,0,0)     |TODO - Nullable: True Default: None Visible:No|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)|Levensverwachting van het bord toen het geplaatst werd(jaren) TODO - Nullable: True Visible:No|
|MAXIMUMSNELHEIDGEM                  |String(1,0,0)       |MaximunSnelheidGemeld: veld om aan te geven als de toegestane max. snelheid is gemeld op het (hectometerings)bord - Ja/Nee/Onbekend, keuzelijst [jaNeeOnbekend] Nullable: True Default: O Visible:No|
|PLANJAAR                            |SmallInteger(0,10,0)|Planjaar TODO - Nullable: True Visible:No|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0)|Verwachte restlevensduur vanaf moment inspect (waar wordt inspectiedatum ingevuld?) TODO - Nullable: True Visible:No|
|ROTATIEHOEK                         |SmallInteger(0,10,0)|Orientatie van het bord - Nullable: True Visible:No|
|CEKEUR                              |String(255,0,0)     |CE-Keurmerk aanwezig - Nullable: True Default: None Visible:No|
|GARANTIECERTIFICAAT                 |String(255,0,0)     |Garantie certificaat aanwezig - Nullable: True Default: None Visible:No|
|REFLECTIEWAARDE                     |String(255,0,0)     |Gemeten Reflectiewaarde - Nullable: True Default: None Visible:No|
|REFLECTIEWAARDE_DATUM               |Date(8,0,0)         |Datum reflectiemeting - Nullable: True Visible:No|
|TRAJECT                             |String(255,0,0)     |FK naar traject_v - Nullable: True Default: None Visible:Yes|
|UITLEGGERPORTAAL                    |String(255,0,0)     |FK naar uitleggerPortaal_l - Nullable: True Default: None Visible:No|
|WEGWIJZER                           |String(255,0,0)     |FK naar bordWegwijzer_p - Nullable: True Default: None Visible:No|
|KRUISPUNT                           |String(255,0,0)     |FK naar kruispunt_p - Nullable: True Default: None Visible:No|
|MAST                                |String(255,0,0)     |FK naar paalDraagconstructie_p - Nullable: True Default: None Visible:No|
|MATRIXTEKST                         |String(255,0,0)     |Tekst op het Matrixbord - Nullable: True Default: None Visible:No|
|DATUMGARANTIE                       |Date(8,0,0)         |Datum garantie - Nullable: True Visible:No|
|JAAR_PLAATSING_AANLEG_GESCHAT       |String(1,0,0)       |Jaar plaatsing of aanleg is geschat: Ja/Nee (keuzelijst [jaNee] - Nullable: True Default: N Visible:No|
|TEKST                               |String(255,0,0)     |Combinatie, Route, Snelheid, Waarschuwing, Overig - Nullable: True Default: None Visible:No|
|FABRIKANTTYPECODE                   |String(255,0,0)     |Fabrikanttypecode, keuzelijst [FABRIKANT_TYPECODE] - Nullable: True Default: None Visible:No|
|TOPDESK_ID                          |String(255,0,0)     |Verwijzing naar ObjectID TOPdesk - Nullable: True Default: None Visible:No|
|HALTE                               |String(255,0,0)     |FK naar halte_v - Nullable: True Default: None Visible:No|


***
