## AREAALDATA.waterdeel_v

$ Feature dataset: Opdelend

* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ BGT
* __Positionele nauwkeurigheid:__ 25 cm
* __Geometrie:__ Vlak
* __Definitie:__ Kleinste functioneel onafhankelijk stukje water met gelijkblijvende, homogene eigenschappen en relaties dat er binnen het objecttype Water van NEN 3610 wordt onderscheiden en dat permanent met water bedekt is. 

***

|KOLOM                             |TYPE          	        |DEFINITIE|
|------                            |----          	        |-----    |
|BGTPLUSTYPE                       |String(50,0,0)          |Beschrijving - keuzelijst [typeWTD] Nullable: False Default: None|
|IDENTIFICATIE                     |String(255,0,0)         |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|STATUS                            |String(10,0,0)          |Beschrijving - keuzelijst [status] Nullable: False Default: :bestaand|
|BRONHOUDER                        |String(5,0,0)           |BGT, De bronhoudercode van het object, keuzelijst [bronhouder] - Nullable: False Default: None|
|INONDERZOEK                       |String(1,0,0)           |BGT, Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N|
|RELATIEVEHOOGTELIGGING            |SmallInteger(0,10,0)    |BGT, Aanduiding voor de relatieve hoogte van het object - Nullable: False Default: 0|
|TIJDSTIPREGISTRATIE               |Date(8,0,0)             |Beschrijving - keuzelijst [] Nullable: True Default: None|
|EINDREGISTRATIE                   |Date(8,0,0)             |Beschrijving - keuzelijst [] Nullable: True Default: None|
|LV_PUBLICATIEDATUM                |Date(8,0,0)             |BGT, Tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening - Nullable: True|
|BERICHT_ID                        |String(128,0,0)         |Beschrijving - keuzelijst [] Nullable: True Default: None|
|SHAPE                             |Geometry(0,0,0)         |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Length                      |Double(0,0,0)           |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Area                        |Double(0,0,0)           |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecWTD] - Nullable: True Default: None|
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
|OPMERKING                           |String(3000,0,0)      |Extra toelichting - Nullable: True Default: None|
|BREEDTEINSTEKEN                     |String(255,0,0)       |Breedte tussen de twee kanten daar waar er een knik is tussen land en slootkant in meters (< 6 m of > 6 m), keuzelijst [BREEDTE_INSTEKEN] - Nullable: True Default: None|
|ZIJDE                               |String(255,0,0)       |Zijde van kanaal, keuzelijst [ZIJDE] - Nullable: True Default: None|
|AANLEGJAAR                          |SmallInteger(0,10,0)  |Aanlegjaar - Nullable: True|
|BREEDTENATPROFIEL                   |Float(0,25,10)        |Breedte tussen de twee kanten van het water in centimeters - Nullable: True|
|OMSCHRIJVING                        |String(255,0,0)       |Extra toelichting - Nullable: True Default: None|
|GEWENSTEDIEPTE                      |Float(0,25,10)        |Gewenste diepte van de waterloop in centimeters - Nullable: True|
|HMBEGIN                             |Float(0,25,10)        |Begin Hectometrering - Nullable: True|
|HMEIND                              |Float(0,25,10)        |Eind Hectometrering - Nullable: True|
|HYDRAULISCHPROFIEL                  |String(255,0,0)       |Verwijzing naar het Hydraulisch profiel - Nullable: True Default: None|
|KEURMAAT                            |Float(0,25,10)        |Minimale breedte volgens het Waterschap in centimeters - Nullable: True|
|LENGTE                              |SmallInteger(0,10,0)  |Lengte - Nullable: True|
|NAUTISCHPROFIEL                     |String(255,0,0)       |Verwijzing naar het Nautisch profiel - Nullable: True Default: None|
|ONDERHOUDTWEEKANTE                  |String(255,0,0)       |Indicatie of alleen de eigen kant van de waterloop onderhouden moet worden of ook de overkant (veelal in ander eigendom) - Nullable: True Default: None|
|VAARWEGDEELTRAJECT                  |String(255,0,0)       |FK naar vaarwegdeeltraject_v - Nullable: True Default: None|
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
