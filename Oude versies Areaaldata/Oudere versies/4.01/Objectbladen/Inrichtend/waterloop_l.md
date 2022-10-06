## AREAALDATA.waterloop_l

$ Feature dataset: Inrichtend

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 25 cm
* __Geometrie:__ Lijn
* __Definitie:__ Terrein ingericht voor afvoer en berging van oppervlaktewater. BGT kent alleen vlakken. Dit objecttype zal uitgefaseerd worden.

***

|KOLOM                             |TYPE          	        |DEFINITIE|
|------                            |----          	        |-----    |
|OBJECTID                          |OID(38,0,0)             |Interne ID ArcGIS - Nullable: False|
|IDENTIFICATIE                     |String(255,0,0)         |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|STATUS                            |String(10,0,0)          |Beschrijving - keuzelijst [status] Nullable: False Default: :bestaand|
|OBJECTBEGINTIJD                   |Date(8,0,0)             |BGT, Datum waarop het object bij de bronhouder is ontstaan - Nullable: False|
|OBJECTEINDTIJD                    |Date(8,0,0)             |BGT, Datum waarop het object bij de bronhouder niet meer geldig is - Nullable: True|
|BERICHT_ID                        |String(128,0,0)         |Beschrijving - keuzelijst [] Nullable: True Default: None|
|SHAPE                             |Geometry(0,0,0)         |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Length                      |Double(0,0,0)           |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Area                        |Double(0,0,0)           |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecWTL] - Nullable: True Default: None|
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
|CAT_WATERLOOP                       |String(255,0,0)       |Categorie waterloop, keuzelijst [CAT_WATERLOOP] - Nullable: True Default: None|
|JAAR_PLAATSING_AANLEG_GESCHAT       |String(1,0,0)         |Jaar plaatsing of aanleg is geschat: ja of nee : keuzelijst [jaNee] Nullable: True Default: N|
|BODEMHOOGTE                         |Float(0,25,10)        |Hoogte t.o.v. NAP - Nullable: True|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)  |Levensverwachting - Nullable: True|
|BIJZONDEREWAARDE                    |String(255,0,0)       |Indicatie van bijzondere waarde - Nullable: True Default: None|
|OPMERKINGMBTONDERH                  |String(255,0,0)       |Opmerking mbt onderhoud - Nullable: True Default: None|
|PEILVAST                            |Float(0,25,10)        |Vaste peil - Nullable: True|
|PEILWINTER                          |Float(0,25,10)        |Winter peil - Nullable: True|
|PEILZOMER                           |Float(0,25,10)        |Zomer peil - Nullable: True|
|PLANJAAR                            |SmallInteger(0,10,0)  |Planjaar - Nullable: True|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0)  |Restlevensduur - Nullable: True|
|VERKANTINGTALUD                     |String(255,0,0)       |TODO - Nullable: True Default: None|
|WATERBREEDTE                        |Float(0,25,10)        |Breedte Natte profiel in meters (2 decimalen)- Nullable: True|
|SLOOTVEGETATIE                      |String(1,0,0)         |Slootvegetatie dient verwerkt te worden: Ja/Nee. : keuzelijst [jaNee] Nullable: True Default: N|
|WATERDIEPTE                         |Float(0,25,10)        |TODO - Nullable: True|
|WATERSCHAP                          |String(255,0,0)       |Naam Waterschap, keuzelijst [WATERSCHAP] - Nullable: True Default: None|
|OPPERVLAKTE                         |Float(0,25,10)        |Oppervlakte van de waterloop (m2, 2 decimalen) - Nullable: True|
|TRAJECT                             |String(255,0,0)          |FK naar traject_v - Nullable: True Default: None|


***
