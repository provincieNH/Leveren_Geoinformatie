## AREAALDATA.kunstwerkdeel_v

$ Feature dataset: Opdelend

* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ IMGeo BGT 
* __Positionele nauwkeurigheid:__ 5 cm
* __Geometrie:__ Vlak
* __Definitie:__ Onderdeel van een civiel-technisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen. 

***

|KOLOM                             |TYPE          	        |DEFINITIE|
|------                            |----          	        |-----    |
|BGTPLUSTYPE                       |String(50,0,0)          |Beschrijving - keuzelijst [typeKWDVlakBGT] Nullable: False Default: None|
|IDENTIFICATIE                     |String(255,0,0)         |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|STATUS                            |String(10,0,0)          |Beschrijving - keuzelijst [] Nullable: False Default: None|
|VERWERKINGSSTATUS                 |String(255,0,0)         |Status van de gegevens, keuzelijst [VERWERKINGSSTATUS] - Nullable: False Default: Nieuwl|
|TIJDSTIPREGISTRATIE               |Date(8,0,0)             |Beschrijving - keuzelijst [] Nullable: True Default: None|
|EINDREGISTRATIE                   |Date(8,0,0)             |Beschrijving - keuzelijst [] Nullable: True Default: None|
|BRONHOUDER                        |String(5,0,0)           |BGT, De bronhoudercode van het object, keuzelijst [bronhouder] - Nullable: False Default: None|
|INONDERZOEK                       |String(1,0,0)           |BGT, Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N|
|RELATIEVEHOOGTELIGGING            |SmallInteger(0,10,0)    |BGT, Aanduiding voor de relatieve hoogte van het object - Nullable: False Default: 0|
|LV_PUBLICATIEDATUM                |Date(8,0,0)             |BGT, Tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening - Nullable: True|
|BERICHT_ID                        |String(128,0,0)         |Beschrijving - keuzelijst [] Nullable: True Default: None|
|SHAPE                             |Geometry(0,0,0)         |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Length                      |Double(0,0,0)           |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Area                        |Double(0,0,0)           |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecKWD] - Nullable: True Default: None|
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
|AANLEGJAAR                          |SmallInteger(0,4,0)      |Aanlegjaar - Nullable: True|
|OMSCHRIJVING                        |String(255,0,0)           |Extra toelichting - Nullable: True Default: None|
|FOTO                                |String(255,0,0)           |Verwijzing naar Foto - Nullable: True Default: None|
|HECTOMETER                          |String(255,0,0)           |Hectometrering - Nullable: True Default: None|
|HOOGTETOVMAAIVELD                   |Float(0,25,10)            |Hoogte tov Maaiveld - Nullable: True|
|KERENDEHOOGTE                       |Float(0,25,10)            |Bovenkant van de constructie tov NAP - Nullable: True|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)      |Levensverwachting - Nullable: True|
|OPMERKINGMBTONDERH                  |String(255,0,0)           |Opmerking mbt onderhoud - Nullable: True Default: None|
|PLANJAAR                            |SmallInteger(0,10,0)      |Planjaar - Nullable: True|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0)      |Restlevensduur - Nullable: True|
|VASTOFBEWEEGBAAR                    |String(255,0,0)           |Vaste of Beweegbare stuw - Nullable: True Default: None|
|WERKENDEBREEDTE                     |Float(0,25,10)            |Werkende Breedte - Nullable: True|
|MATERIAALTYPE                       |String(255,0,0)           |Type materiaal, keuzelijst [MATERIAALTYPE] - Nullable: True Default: None|
|WATERSCHAP                          |String(255,0,0)           |Waterschap naam, keuzelijst, [WATERSCHAP] - Nullable: True Default: None|
|ZIJDE                               |String(255,0,0)           |Zijde (vd weg), keuzelijst [ZIJDE] - Nullable: True Default: None|
|TRAJECT                             |String(255,0,0)           |FK naar traject_v  - Nullable: True Default: None|
|BESTEMMING                          |String(255,0,0)           |Bestemming - Nullable: True Default: None|
|BRUG                                |String(255,0,0)           |Brug TODO - Nullable: True Default: None|
|CONSTRUCTIE                         |String(255,0,0)           |Constructie TODO - Nullable: True Default: None|
|HOOGTEBOVENNAP                      |Float(0,25,10)            |HoogteBoven NAP (cm?) TODO - Nullable: True|
|LOOPDEK                             |String(255,0,0)           |Loopdek Ja/Nee, keuzelijst [jaNeeOnbekend] Nullable: True Default: O|
|VERLICHT                            |String(255,0,0)           |VerlichtJa/Nee, keuzelijst [jaNeeOnbekend] Nullable: True Default: O|
|BESTEK                              |String(255,0,0)           |Bestek, keuzelijst [BESTEK] - Nullable: True Default: None|
|FUNCTIE                             |String(255,0,0)           |Functie, keuzelijst [FUNCTIE] - Nullable: True Default: None|


***
