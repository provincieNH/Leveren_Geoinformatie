## AREAALDATA.ondersteunendWaterdeel_v

$ Feature dataset: Opdelend

* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ BGT/PNH
* __Positionele nauwkeurigheid:__ 25 cm
* __Geometrie:__ Vlak
* __Definitie:__ Object dat in het kader van de waterhuishouding periodiek gedeeltelijk of geheel met water is bedekt. Een vegetatie van voornamelijk riet en andere soorten langs een waterloop. In breedte variabel van 0,50 tot 3,00 meter. 

***

|KOLOM                              |TYPE          	        |DEFINITIE|
|------                          	|----          	        |-----    |
|OBJECTID                           |OID(38,0,0)            |Interne ID ArcGIS - Nullable: False|
|BGTPLUSTYPE                        |String(50,0,0)         |Beschrijving - keuzelijst [typeOWT] Nullable: False Default: None|
|IDENTIFICATIE                      |String(255,0,0)        |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|STATUS                             |String(10,0,0)         |Beschrijving - keuzelijst [status] Nullable: False Default: :bestaand|
|BRONHOUDER                         |String(5,0,0)          |BGT, De bronhoudercode van het object, keuzelijst [bronhouder] - Nullable: False Default: None|
|INONDERZOEK                        |String(1,0,0)          |BGT, Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N|
|RELATIEVEHOOGTELIGGING             |SmallInteger(0,10,0)   |BGT, Aanduiding voor de relatieve hoogte van het object - Nullable: False Default: 0|
|TIJDSTIPREGISTRATIE                |Date(8,0,0)            |Beschrijving - keuzelijst [] Nullable: True Default: None|
|EINDREGISTRATIE                    |Date(8,0,0)            |Beschrijving - keuzelijst [] Nullable: True Default: None|
|LV_PUBLICATIEDATUM                 |Date(8,0,0)            |BGT, Tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening - Nullable: True|
|BERICHT_ID                         |String(128,0,0)        |Beschrijving - keuzelijst [] Nullable: True Default: None|
|CREATED_USER                        |String(255,0,0)       |Naam van gebruiker die de rij heeft aangemaakt - Nullable: True Default: None|
|CREATED_DATE                        |Date(8,0,0)           |Aanmaakdatum - Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)        |Naam van gebruiker die de laatste mutatie heeft doorgevoerd - Nullable: True Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)           |Datum van de laatste mutatie - Nullable: True|
|SHAPE                              |Geometry(0,0,0)        |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Length                       |Double(0,0,0)          |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Area                         |Double(0,0,0)          |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecOWA] - Nullable: True Default: None|
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
|TYPEBEHEER                          |String(255,0,0)       |Type beheer, keuzelijst [TYPE_BEHEER] - Nullable: True Default: None|
|TYPEBODEM                           |String(255,0,0)       |Type bodem, keuzelijst [TYPE_BODEM] - Nullable: True Default: None|
|ACTUEELBEELD                        |String(255,0,0)       |Huidige beeld - Nullable: True Default: None|
|BREEDTE                             |Float(0,25,10)        |Breedte van de plasberm in m, 2 decimalen - Nullable: True Default: None|
|OPPERVLAKTE                         |Float(0,25,2)         |Oppervlakte van de plasberm in m2, 2 decimalen - Nullable: True Default: None|
|DATUMAANPLANTING                    |SmallInteger(0,4,0)        |Datum aanplanting - Nullable: True Default: None|
|JAAR_PLAATSING_AANLEG_GESCHAT       |String(1,0,0)         |Jaar plaatsing of aanleg is geschat: ja of nee : keuzelijst [jaNee] Nullable: True Default: N|
|OMSCHRIJVING                        |String(255,0,0)       |Extra toelichting - Nullable: True Default: None|
|HMBEGIN                             |Float(0,25,10)        |Hectometrering begin plantvak - Nullable: True Default: None|
|HMEIND                              |Float(0,25,10)        |Hectometrering eind plantvak - Nullable: True Default: None|
|HOOGTETOVMAAIVELD                   |Float(0,25,10)        |Hoogte t.o.v. maaiveld in mm - Nullable: True Default: None|
|LENGTE                              |SmallInteger(0,10,0)  |Lengte plantvak in hele meters - Nullable: True Default: None|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)  |Levensverwachting - Nullable: True Default: None|
|MAXWATERDIEPTE                      |Float(0,25,10)        |Maximale waterdiepte van de plasberm in cm - Nullable: True Default: None|
|OPMERKINGMBTONDERH                  |String(255,0,0)       |Opmerking mbt onderhoud - Nullable: True Default: None|
|PLANJAAR                            |SmallInteger(0,10,0)  |Planjaar - Nullable: True Default: None|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0)  |Restlevensduur - Nullable: True Default: None|
|STREEFBEELD                         |String(255,0,0)       |Streefbeeld - Nullable: True Default: None|
|ZIJDE                               |String(255,0,0)       |Zijde, keuzelijst [ZIJDE] - Nullable: True Default: None|
|OEVERVAK                            |String(255,0,0)       |FK naar oevervak_v - Nullable: True Default: None|
|TRAJECT                             |String(255,0,0)       |FK naar traject_v - Nullable: True Default: None|


***
