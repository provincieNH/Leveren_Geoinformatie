## AREAALDATA.begroeidTerreindeelPlantvak_v

$ Feature dataset: Opdelend

* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 25 cm
* __Geometrie:__ Vlak
* __Definitie:__ Terreindeel met aangelegde beplanting, meestal gras, heesters of struiken. BGT Begroeid Terreindeel, verbijzonderd naar fysiek voorkomen groenvoorziening. 

***

|KOLOM                             |TYPE          	    |DEFINITIE|
|------                            |----          	    |-----    |
|FYSIEKVOORKOMEN                   |String(50,0,0)      |Beschrijving - keuzelijst [fysiekVoorkomenBTDP] Nullable: False Default: groenvoorziening|
|OPTALUD                           |String(1,0,0)       |Beschrijving - keuzelijst [jaNeeOnbekend] Nullable: True Default: N|
|IDENTIFICATIE                     |String(255,0,0)     |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|STATUS                            |String(10,0,0)      |Beschrijving - keuzelijst [status] Nullable: False Default: :bestaand|
|BRONHOUDER                        |String(5,0,0)       |BGT, De bronhoudercode van het object, keuzelijst [bronhouder] - Nullable: False Default: None|
|INONDERZOEK                       |String(1,0,0)       |BGT, Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N|
|RELATIEVEHOOGTELIGGING            |SmallInteger(0,10,0)|BGT, Aanduiding voor de relatieve hoogte van het object - Nullable: False Default: 0|
|TIJDSTIPREGISTRATIE               |Date(8,0,0)         |Beschrijving - keuzelijst [] Nullable: True Default: None|
|EINDREGISTRATIE                   |Date(8,0,0)         |Beschrijving - keuzelijst [] Nullable: True Default: None|
|LV_PUBLICATIEDATUM                |Date(8,0,0)         |BGT, Tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening - Nullable: True|
|BERICHT_ID                        |String(128,0,0)     |Beschrijving - keuzelijst [] Nullable: True Default: None|
|SHAPE                             |Geometry(0,0,0)     |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Length                      |Double(0,0,0)       |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Area                        |Double(0,0,0)       |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecBTDPlantvak] - Nullable: True Default: None|
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
|FIETSOVERSTEEKPLAA                  |String(255,0,0)     |Indicatie of er een Fietsoversteekplaats is - Nullable: True Default: None|
|EINDBEELD                           |String(255,0,0)     |Eindbeeld voor plantvak - Nullable: True Default: None|
|OPPERVLAKTE                         |Float(0,25,10)      |Oppervlakte m2, 2 decimalen - Nullable: True|
|GRONDSOORT                          |String(255,0,0)     |Grondsoort, keuzelijst [GRONDSOORT] - Nullable: True Default: None|
|HMBEGIN                             |Float(0,25,10)      |Hectometrering begin heg - Nullable: True|
|HMEIND                              |Float(0,25,10)      |Hectometrering eind heg  - Nullable: True|
|ACTUEELBEELD                        |String(255,0,0)     |Huidige beeld - Nullable: True Default: None|
|BOLGEWAS                            |String(255,0,0)     |Welk bolgewas er aanwezig is - Nullable: True Default: None|
|STREEFBEELD                         |String(255,0,0)     |Streefbeeld - Nullable: True Default: None|
|LENGTE                              |SmallInteger(0,10,0)|Lengte vd heg in hele meters - Nullable: True|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)|Levensverwachting - Nullable: True|
|OPMERKINGMBTONDERH                  |String(255,0,0)     |Opmerking mbt onderhoud - Nullable: True Default: None|
|PLANJAAR                            |SmallInteger(0,10,0)|Planjaar - Nullable: True|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0)|Restlevensduur - Nullable: True|
|DATUMAANPLANTING                    |SmallInteger(0,4,0)      |Jaar aanplanting  - Nullable: True|
|OMSCHRIJVING                        |String(255,0,0)     |Extra toelichting  - Nullable: True Default: None|
|JAAR_PLAATSING_AANLEG_GESCHAT       |String(1,0,0)       |Jaar plaatsing of aanleg is geschat: Ja/Nee - keuzelijst [jaNee] - Nullable: True Default: N|
|HOOGTETOVMAAIVELD                   |Float(0,25,10)      |Hoogte tov Maaiveld - Nullable: True|
|WIJZEVANINWINNING                   |String(255,0,0)     |Wijze van inwinning gegevens  - Nullable: True Default: None|
|AFSTANDVERHARDING                   |Float(0,25,10)      |Afstand tot de verharding in meters, 2 decimalen - Nullable: True|
|OEVERVAK                            |String(255,0,0)     |FK naar oevervak_v - (als plantvak aan een vaarweg ligt) - Nullable: True Default: None|

***
