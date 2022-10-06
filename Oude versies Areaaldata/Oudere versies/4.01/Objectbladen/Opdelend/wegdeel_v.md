## AREAALDATA.wegdeel_v

$ Feature dataset: Opdelend

* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ BGT
* __Positionele nauwkeurigheid:__ 7,5 cm (NB, groter dan BGT)
* __Geometrie:__ Vlak
* __Definitie:__ Kleinste functioneel onafhankelijk stuk van een NEN 3610 Weg met gelijkblijvende, homogene eigenschappen
en relaties en primair bedoeld voor gebruik door weg-, spoor- en vliegverkeer te land.


***

|KOLOM                             |TYPE          	        |DEFINITIE|
|------                            |----          	        |-----    |
|FYSIEKVOORKOMEN                   |String(50,0,0)          |Beschrijving - keuzelijst [fysiekVoorkomenWGD] Nullable: False Default: None|
|FUNCTIE                           |String(50,0,0)          |Beschrijving - keuzelijst [functieWGD] Nullable: False Default: None|
|OPTALUD                           |String(1,0,0)           |Beschrijving - keuzelijst [jaNeeOnbekend] Nullable: True Default: N|
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
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecWGD] - Nullable: True Default: None|
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
|BREEDTE                             |Float(0,25,10)       |Breedte van het wegvakonderdeel (m, 2 decimalen) - Nullable: True|
|COMFORT                             |String(255,0,0)     |Comfort waarde - Nullable: True Default: None|
|COMFORT_DATE                        |Date(8,0,0)         |Datum comfort meting - Nullable: True|
|DEFLECTIE                           |String(255,0,0)     |Deflectie waarde - Nullable: True Default: None|
|DEFLECTIE_DATE                      |Date(8,0,0)         |Datum deflectie meting - Nullable: True|
|OMSCHRIJVING                        |String(255,0,0)     |Extra toelichting - Nullable: True Default: None|
|KOMGRENS                            |String(255,0,0)     |Komgrens  - Nullable: True Default: None|
|WEGTYPE                             |String(255,0,0)     |Wegtype, keuzelijst [WEGTYPE] - Nullable: True Default: None|
|WEGINDELING                         |String(255,0,0)     |Wegindeling, keuzelijst [WEGINDELING] - Nullable: True Default: None|
|JAARAANLEG                          |SmallInteger(0,10,0)|Jaar aanleg van de weg - Nullable: True|
|JAARCONSERVEREN                     |SmallInteger(0,10,0)|Jaar van conservering - Nullable: True|
|JAARDEKLAAG                         |SmallInteger(0,10,0)|Jaar deklaag gelegd - Nullable: True|
|JAARHERSTRATEN                      |SmallInteger(0,10,0)|Jaar Herbestrating gelegd - Nullable: True|
|JAARVERNIEUWEN                      |SmallInteger(0,10,0)|TODO - Nullable: True|
|LANGSONVLAKHEID                     |String(255,0,0)     |Langsonvlakheid meting - Nullable: True Default: None|
|LANGSONVLAKHEID_DATE                |Date(8,0,0)         |Datum langsonvlakheid meting - Nullable: True|
|LENGTE                              |SmallInteger(0,10,0)|Lengte van het wegvakonderdeel (hele meters) - Nullable: True|
|LENGTEVOEGEN                        |SmallInteger(0,10,0)|Lengte van de voegen (m) - Nullable: True|
|OPPERVLAKTE                         |Float(,25,10)       |Oppervlakte van het wegvakonderdeel (m2, 2 decimalen) - Nullable: True|
|SPOORVORMING                        |String(255,0,0)     |Spoorvorming meting - Nullable: True Default: None|
|SPOORVORMING_DATE                   |Date(8,0,0)         |Datum spoorvorming meting - Nullable: True|
|GEBRUIKSFUNCTIE                     |String(255,0,0)     |Gebruiksfunctie conform CROW, keuzelijst [GEBRUIKSFUNCTIE] - Nullable: True Default: None|
|SITUERING                           |String(255,0,0)     |Situering conform CROW, keuzelijst [SITUERING] - Nullable: True Default: None|
|STROEFHEID                          |String(255,0,0)     |Stroefheid meting - Nullable: True Default: None|
|STROEFHEID_DATE                     |Date(8,0,0)         |Datum stroefheid meting - Nullable: True|
|VERHARDING                          |String(255,0,0)     |Verharding object conform CROW, keuzelijst [VERHARDING] - Nullable: True Default: None|
|VERHARDINGCATEGORIE                 |String(255,0,0)     |Verharding categorie conform CROW, keuzelijst [VERHARDING_CATEGORIE] - Nullable: True Default: None|
|WGV_AFSTANDTOT                      |Float(0,25,10)      |Wegvak, Aanduiding bij welk wegindexeringspaal (hectometerpaal) het inspectievak eindigt  - Nullable: True|
|WGV_AFSTANDVAN                      |Float(0,25,10)      |Wegvak, Aanduiding bij welk wegindexeringspaal (hectometerpaal) het inspectievak begint  - Nullable: True|
|WGV_NUMMER                          |SmallInteger(0,10,0)|Wegvak, Wegvak nummer, uniek per weg - Nullable: True|
|HALTE                               |String(255,0,0)     |FK naar halte_v - Nullable: True Default: None|
|WEGVAK                              |String(255,0,0)     |FK naar wegvak_v - Nullable: True Default: None|
|TRAJECT                             |String(255,0,0)     |FK naar traject_v - Nullable: True Default: None|
|BESTEMMING                          |String(255,0,0)           |Bestemming - Nullable: True Default: None|
|BRUG                                |String(255,0,0)           |Brug TODO - Nullable: True Default: None|
|CONSTRUCTIE                         |String(255,0,0)           |Constructie TODO - Nullable: True Default: None|
|HOOGTEBOVENNAP                      |Float(0,25,10)            |HoogteBoven NAP (cm?) TODO - Nullable: True|
|LOOPDEK                             |String(255,0,0)           |Loopdek Ja/Nee, keuzelijst [jaNeeOnbekend] Nullable: True Default: O|
|VERLICHT                            |String(255,0,0)           |VerlichtJa/Nee, keuzelijst [jaNeeOnbekend] Nullable: True Default: O|
|BESTEK                              |String(255,0,0)           |Bestek, keuzelijst [BESTEK] - Nullable: True Default: None|
|HECTOMETER                          |String(255,0,0)           |Hectometrering  - Nullable: True Default: None|

***
