## AREAALDATA.paalDraagconstructie_p

$ Feature dataset: Inrichtend

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Hoge draagconstructie, vervaardigd van metaal, hout, steen of kunststof dat dient om iets te dragen. __LET OP:__ In dit objecttype worden worden de IMGEO palen geadministreerd die primair een dragende functie hebben, zoals lichtmast, verkeersregelinstallatiepaal, verkeersbordpaal en haltepaal.



***

|KOLOM                               |TYPE          	   |DEFINITIE|
|------                         	 |----          	   |-----    |
|HECTOMETERAANDUIDING                |String(200,0,0)      |Beschrijving - keuzelijst [] Nullable: True Default: None|
|BGTPLUSTYPE                         |String(50,0,0)       |Beschrijving - keuzelijst [typePAL] Nullable: False Default: None|
|IDENTIFICATIE                       |String(255,0,0)      |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|STATUS                              |String(10,0,0)       |Beschrijving - keuzelijst [status] Nullable: False Default: :bestaand|
|BRONHOUDER                          |String(5,0,0)        |BGT, De bronhoudercode van het object, keuzelijst [bronhouder] - Nullable: False Default: None|
|INONDERZOEK                         |String(1,0,0)        |BGT, Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N|
|RELATIEVEHOOGTELIGGING              |SmallInteger(0,10,0) |BGT, Aanduiding voor de relatieve hoogte van het object - Nullable: False Default: 0|
|TIJDSTIPREGISTRATIE                 |Date(8,0,0)          |Beschrijving - keuzelijst [] Nullable: True Default: None|
|EINDREGISTRATIE                     |Date(8,0,0)          |Beschrijving - keuzelijst [] Nullable: True Default: None|
|LV_PUBLICATIEDATUM                  |Date(8,0,0)          |BGT, Tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening - Nullable: True|
|BERICHT_ID                          |String(128,0,0)      |Beschrijving - keuzelijst [] Nullable: True Default: None|
|SHAPE                               |Geometry(0,0,0)      |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)      |Nadere typering van het object, keuzelijst [typeSpecPALDraagconstructie] - Nullable: True Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)      |Status van de gegevens, keuzelijst [VERWERKINGSSTATUS] - Nullable: False Default: Nieuwl|
|OBJECTID                            |OID(38,0,0)          |Interne ID ArcGIS - Nullable: False|
|GLOBALID                            |GlobalID(38,0,0)     |Global Unique Identifier - Nullable: False|
|GISIB_ID                            |Integer(0,10,0)      |ID beheer openbare ruimte (GISIB) - Nullable: True|
|AD_ID                               |String(255,0,0)      |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]' - Nullable: False Default: None|
|OBJECTBEGINTIJD                     |Date(8,0,0)          |Datum waarop het object bij de bronhouder is ontstaan - Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)          |Datum waarop het object bij de bronhouder niet meer geldig is - Nullable: True|
|CREATED_USER                        |String(255,0,0)      |Naam van gebruiker die de rij heeft aangemaakt - Nullable: True Default: None|
|CREATED_DATE                        |Date(8,0,0)          |Aanmaakdatum - Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)       |Naam van gebruiker die de laatste mutatie heeft doorgevoerd - Nullable: True Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)          |Datum van de laatste mutatie - Nullable: True|
|BEHEERDER                           |String(255,0,0)      |Beheerder van het object, keuzelijst [BEHEERDER] - Nullable: True Default: None|
|ONDERHOUDER                         |String(255,0,0)      |Onderhouder van het object, keuzelijst [ONDERHOUDER] - Nullable: True Default: None|
|EIGENAAR                            |String(255,0,0)      |Eigenaar van het object, keuzelijst [INSTANTIE] - Nullable: True Default: None| 
|DATALEVERANCIER                     |String(255,0,0)      |Leverancier van de data - Nullable: True Default: None|
|FABRIKANTTYPECODE                   |String(255,0,0)      |Fabrikanttypecode, keuzelijst [FABRIKANT_TYPECODE] - Nullable: True Default: None|
|MATERIAALTYPE                       |String(255,0,0)      |Type materiaal, keuzelijst [MATERIAALTYPE] - Nullable: True Default: None|
|HECTOMETER                          |String(255,0,0)      |Hectometrering  - Nullable: True Default: None|
|AANTALLUIKEN                        |SmallInteger(0,10,0) |Aantal luiken  - Nullable: True|
|AARDRAADAANWEZIG                    |String(1,0,0)        |Aarddraad aanwezig: Ja/Nee/Onbekend, keuzelijst [jaNeeOnbekend] Nullable: True Default: O|
|CAMERAOPZETSTUK                     |String(1,0,0)        |Camera opzetstuk aanwezig: Ja/Nee/Onbekend, keuzelijst [jaNeeOnbekend] Nullable: True Default: O|
|CONSERVERING                        |String(1,0,0)        |Conservering toegepast: Ja/Nee/Onbekend, keuzelijst [jaNeeOnbekend] Nullable: True Default: O|
|DATUMGARANTIE                       |Date(8,0,0)          |Datum Garantie  - Nullable: True|
|DATUMPLAATSING                      |Date(8,0,0)          |Datum plaatsing  - Nullable: True|
|ELEVATIEHOEK                        |SmallInteger(0,10,0) |Hoek van de uithouder indien aanwezig  - Nullable: True|
|HOOGTE                              |SmallInteger(0,10,0) |Lichtpunt hoogte  - Nullable: True|
|LENGTEUITHOUDER1                    |Float(0,25,10)       |Lengte van de uithouder indien aanwezig  - Nullable: True|
|MASTNUMMER                          |String(255,0,0)      |Mast nummer - Nullable: True Default: None|
|OPMERKING                           |String(3000,0,0)     |Extra toelichting - Nullable: True Default: None|
|RALKLEUR                            |String(255,0,0)      |RAL Kleur - Nullable: True Default: None|
|OMSCHRIJVING                        |String(255,0,0)      |Extra toelichting - Nullable: True Default: None|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0) |Levensverwachting - Nullable: True|
|PLANJAAR                            |SmallInteger(0,10,0) |Planjaar - Nullable: True|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0) |Restlevensduur - Nullable: True|
|VORM                                |String(255,0,0)      |Vorm van de mast - Nullable: True Default: None|
|LENGTEUITHOUDER2                    |Float(0,25,10)       |Lengte van de uithouder indien aanwezig - Nullable: True|
|INNETWERK                           |String(255,0,0)      |FK naar utiliteitsNet_tbl- Nullable: True Default: None|
|TRAJECT                             |String(255,0,0)      |FK naar traject_v - Nullable: True Default: None|
|KRUISPUNT                           |String(255,0,0)      |FK naar kruispunt_p - Nullable: True Default: None|
|UITLEGGERPORTAAL                    |String(255,0,0)      |FK naar uitleggerPortaal_l - als armatuur daarop is gemonteerd - Nullable: True Default: None|

***
