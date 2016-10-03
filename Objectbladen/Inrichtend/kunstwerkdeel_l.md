## AREAALDATA.kunstwerkdeel_l

$ Feature dataset: Inrichtend

* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ IMGeo BGT 
* __Positionele nauwkeurigheid:__ 5 cm
* __Geometrie:__ Lijn
* __Definitie:__ Onderdeel van een civiel-technisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen.

***

|KOLOM                             |TYPE          	        |DEFINITIE|
|------                            |----          	        |-----    |
|OBJECTID                          |OID(38,0,0)             |Interne ID ArcGIS - Nullable: False|
|BGTPLUSTYPE                       |String(50,0,0)          |Beschrijving - keuzelijst [typeKWDLijn] Nullable: False Default: None|
|IDENTIFICATIE                     |String(255,0,0)         |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|STATUS                            |String(10,0,0)          |Beschrijving - keuzelijst [] Nullable: False Default: None|
|TIJDSTIPREGISTRATIE               |Date(8,0,0)             |Beschrijving - keuzelijst [] Nullable: True Default: None|
|EINDREGISTRATIE                   |Date(8,0,0)             |Beschrijving - keuzelijst [] Nullable: True Default: None|
|BRONHOUDER                        |String(5,0,0)           |BGT, De bronhoudercode van het object, keuzelijst [bronhouder] - Nullable: False Default: None|
|INONDERZOEK                       |String(1,0,0)           |BGT, Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N|
|RELATIEVEHOOGTELIGGING            |SmallInteger(0,10,0)    |BGT, Aanduiding voor de relatieve hoogte van het object - Nullable: False Default: 0|
|LV_PUBLICATIEDATUM                |Date(8,0,0)             |BGT, Tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening - Nullable: True|
|BERICHT_ID                        |String(128,0,0)         |Beschrijving - keuzelijst [] Nullable: True Default: None|
|GLOBALID                          |Guid(38,0,0)            |Global Unique Identifier - Nullable: False|
|SHAPE                             |Geometry(0,0,0)         |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Length                      |Double(0,0,0)           |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecKWDLijn] - Nullable: True Default: None|
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
|BIJZONDERHEID                       |String(255,0,0)     |Extra toelichting - Nullable: True Default: None|
|CONFORMNEN                          |String(1,0,0)       |Indicatie of classificatie conform NEN is, keuzelijst [jaNeeOnbekend] - Nullable: True Default: O|
|OMSCHRIJVING                        |String(255,0,0)     |Extra toelichting - Nullable: True Default: None|
|KILOMETRERING                       |Float(0,25,10)      |Aanduiding Kilometrering ligging kunstwerk - Nullable: True|
|KWBREEDTE                           |Float(0,25,10)      |Breedte kunstwerk - Nullable: True|
|KWHOOGTE                            |Float(0,25,10)      |Hoogte kunstwerk - Nullable: True|
|KWLENGTE                            |Float(0,25,10)      |Totale lengte kunstwerk - Nullable: True|
|PLANJAARPMO                         |SmallInteger(0,10,0)|Planjaar PMO - Nullable: True|
|RENOVATIEJAAR                       |SmallInteger(0,10,0)|Renovatie jaar - Nullable: True|
|DIAMETER                            |SmallInteger(0,10,0)|Diameter (mm) - indien ronde duiker  - Nullable: True|
|HOOGTE                              |Float(0,10,2)       |Hoogte (m, 2 decimalen) - indien rechthoekige duiker - Nullable: True|
|BREEDTE                             |Float(0,10,2)       |Breedte (m, 2 decimalen) - indien rechthoekige duiker - Nullable: True|
|PROFIEL                             |String(255,0,0)     |Vorm doorstroomprofiel van duiker, keuzelijst [PROFIEL] - Nullable: True Default: None|
|BOUWJAAR                            |SmallInteger(0,10,0)|Bouwjaar - Nullable: True|                          
|MATERIAALTYPE                       |String(255,0,0)     |Materiaaltype, keuzelijst [MATERIAALTYPE] Nullable: True Default: None|
|GEMEENTE                            |String(255,0,0)     |Gemeente naam, keuzelijst [GEMEENTE] - Nullable: True Default: None|
|LEVENSCYCLUS                        |String(255,0,0)     |Levenscyclus, keuzelijst [LEVENSCYCLUS] - Nullable: True Default: None|
|NENBEHEEROBJECT                     |String(255,0,0)     |NENBEHEEROBJECT - Nullable: True Default: None|
|REGIO                               |String(255,0,0)     |Regio naam, keuzelijst [REGIO] - Nullable: True Default: None|
|SCHOTBALKAANWEZIG                   |String(1,0,0)       |Schotbalk aanwezig, keuzelijst [jaNeeOnbekend] - Nullable: True Default: O|
|DUIKERBINNENONDERK                  |Float(0,25,10)      |Hoogte t.o.v. NAP van binnen onderkant buis (bij duiker) - Nullable: True|
|DUIKERDOORSTROOMPR                  |String(255,0,0)     |Doorstroomprofiel type(bij duiker) - Nullable: True Default: None|
|GEDEELDBEHEER                       |String(255,0,0)     |Indien van toepassing, tweede beheerder van het object, keuzelijst [GEDEELD_BEHEER] - Nullable: True Default: None|
|XCOORDINAAT                         |Float(0,25,10)      |X coordinaat Middenpunt beheerobject(RD) - Nullable: True|
|YCOORDINAAT                         |Float(0,25,10)      |Y coordinaat Middenpunt beheerobject(RD) - Nullable: True|
|VAARWEG                             |String(255,0,0)     |FK naar vaarweg_l - Nullable: True Default: None|
|WEG                                 |String(255,0,0)     |FK naar weg_l - Nullable: True Default: None|
|TRAJECT                             |String(255,0,0)     |FK naar traject_v - Nullable: True Default: None|

***
