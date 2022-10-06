## AREAALDATA.overigBouwwerk_v

$ Feature dataset: Opdelend

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ BGT
* __Positionele nauwkeurigheid:__ 5 cm
* __Geometrie:__ Vlak
* __Definitie:__ Met de aarde verbonden duurzaam bouwwerk, dat niet valt onder de definities van een pand of kunstwerk. __LET OP:__ De vlakgeometrie van Abri wordt in dit objecttype opgenomen en NIET als puntobject in Straatmeubilair. Ondanks dat dit objecttype in de featuredataset Opdelend zit, hoeven deze objecten niet opdelend te zijn.

***

|KOLOM                              |TYPE          	        |DEFINITIE|
|------                          	|----          	        |-----    |
|OBJECTID                           |OID(38,0,0)            |Interne ID ArcGIS - Nullable: False|
|BGTPLUSTYPE                        |String(50,0,0)         |Beschrijving - keuzelijst [typeOBWVlak] Nullable: False Default: None|
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
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecOBWVlak] - Nullable: True Default: None|
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
|FABRIKANT                           |String(255,0,0)       |Naam vd Fabrikant - Nullable: True Default: None|
|AFMETINGEN                          |String(255,0,0)       |ToDo - Nullable: True Default: None|
|LENGTE                              |Float(0,10,3)         |Lengte in Meters, 2 decimalen - Nullable: True|
|BREEDTE                             |Float(0,10,3)         |Breedte in Meters, 2 decimalen - Nullable: True|
|KWALITEITSNIVEAU                    |String(255,0,0)       |Kwaliteitsniveau [ONDERHOUDER] - Nullable: True Default: None|
|RECLAME_GEEXPLOITEERD               |String(1,0,0)         |Ja/Nee : keuzelijst [jaNee] Nullable: True Default: N|
|RECLAME_EXPLOITANT                  |String(255,0,0)       |Naam vd Reclame exploitant - Nullable: True Default: None|
|RECLAME_GEEXPL_ZWARTELIJST          |String(10,0,0)         |Ja/Nee : keuzelijst [jaNee] Nullable: True Default: N|
|RECLAME_HOOGTE                      |String(1,0,0)         |Hoogte in Meters, 2 decimalen - Nullable: True Default: None|
|RECLAME_BREEDTE                     |String(1,0,0)         |Breedte in Meters, 2 decimalen - Nullable: True Default: None|
|RECLAME_VERLICHTING                 |String(1,0,0)         |Ja/Nee : keuzelijst [jaNee] Nullable: True Default: N|
|RECLAME_TYPE                        |String(255,0,0)       |Type reclame - Nullable: True Default: None|
|ZITMEUBILAIR_AANW                   |String(1,0,0)         |Zitmeubilair aanwezig Ja/Nee : keuzelijst [jaNee] Nullable: True Default: N|
|VERLICHTING_AANW                    |String(1,0,0)         |Verlichting aanwezig Ja/Nee : keuzelijst [jaNee] Nullable: True Default: N|
|VERLICHTING_TYPE                    |String(255,0,0)       |Type verlichting (led/../) - Nullable: True Default: None|
|VERLICHTING_FABRIKANT               |String(255,0,0)       |Naam van de verlichtingsfabrikant - Nullable: True Default: None|
|ZONNEPANEEL                         |String(1,0,0)         |Zonnepaneel aanwezig Ja/Nee : keuzelijst [jaNee] Nullable: True Default: N|
|HALTE                               |String(255,0,0)       |FK naar halte_v - Nullable: True Default: None|
|TRAJECT                             |String(255,0,0)       |FK naar traject_v - Nullable: True Default: None|


***
