## AREAALDATA.scheidingOevervak_l

$ Feature dataset: Inrichtend


* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ BGT / NEN 2767-4 / PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__  lijn
* __Definitie:__ Een NEN Element is gedefinieerd als 'een samenstel van bouwdelen die tezamen een afzonderlijk herkenbaar 
component van een beheerobject vormen'. __LET OP:__ Dit is het objecttype waar de NEN 2767-4 decompositie van een oevervak in geadministreerd wordt voor de (BGT) types kademuur, damwand en walbescherming.

***

|KOLOM                               |TYPE                |DEFINITIE|
|------                              |----                |-----    |
|OBJECTID                           |OID(38,0,0)            |Interne ID ArcGIS - Nullable: False|
|BGTPLUSTYPE                        |String(50,0,0)         |Beschrijving - keuzelijst [typeSHDLijn] Nullable: False Default: None|
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
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecSHDOevervak] - Nullable: True Default: None|
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
|MATERIAALTYPE                       |String(255,0,0)     |Materiaaltype, keuzelijst [MATERIAALTYPE] Nullable: True Default: None|
|BOUWELEMENTTYPESPE                  |String(255,0,0)     |Bouwelement Type Specificatie - Nullable: True Default: None|
|CONFORMNEN                          |String(1,0,0)       |Is Element conform NEN ja of nee: keuzelijst [jaNee] Nullable: True Default: N|
|OMSCHRIJVING                        |String(255,0,0)     |Extra toelichting - Nullable: True Default: None|
|BOUWELEMENTTYPE                     |String(255,0,0)     |Bouwelement type, keuzelijst [BOUWELEMENT_TYPE] - Nullable: True Default: None|
|OPMERKING                           |String(255,0,0)     |Opmerking - Nullable: True Default: None|
|CONDITIESCORE                       |String(255,0,0)     |Conditiescore conform NEN 2767-4 - Nullable: True Default: None|
|CONDITIESCORE_DATUM                 |String(255,0,0)     |Datum opname Conditiescore - Nullable: True Default: None|
|CONDITIESCORE_OPM                   |String(3000,0,0)    |Opmerking bij conditiescore conform NEN 2767-4 - Nullable: True Default: None|
|AANLEGJAAR                          |SmallInteger(0,10,0)|Aanlegjaar - Nullable: True|
|RENOVATIEJAAR                       |SmallInteger(0,10,0)|Renovatiejaar - Nullable: True|
|KRITISCH                            |String(1,0,0)       |Kritisch (Ja / Nee): keuzelijst [jaNee] Nullable: True Default: N|
|OEVERVAK                            |String(255,0,0)     |FK naar oevervak_v - Nullable: True Default: None|


***


