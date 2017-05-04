## AREAALDATA.halte_v

$ Feature dataset: Functioneel


* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH/NDOV
* __Positionele nauwkeurigheid:__ nvt
* __SHAPE:__ Vlak
* __Definitie:__ Het geheel van objecten behorende bij een stopplaats van een autobus. (Integraal Gegevens Model Ideaal Areaal 1.2). STOPPLACE in NDOV terminologie


***

|KOLOM                               |TYPE              |DEFINITIE|
|------                              |----              |-----    |
|NAAM                                |String(255,0,0)     |Naam vd Halte - Nullable: True Default: None|
|WEGNAAM                             |String(255,0,0)     |Naam vd Weg - Nullable: True Default: None|
|WEGNUMMER                           |String(255,0,0)     |Nummer vd Weg - Nullable: True Default: None|
|GEMEENTE                            |String(255,0,0)     |Gemeentenaam, keuzelijst [GEMEENTE] - Nullable: True Default: None|
|HALTENUMMER                         |String(255,0,0)     |Identificatienummer van de Halte. Let op: Het landelijk unieke nummer van NDOV staat bij Perron! - Nullable: True Default: None|
|PROJECT                             |String(1,0,0)       |Ja/Nee/Onbekend, keuzelijst [jaNeeOnbekend] Nullable: True Default: O|
|SUBSIDIEPROJECT                     |String(255,0,0)     |Naam van het subsidieproject voor aanleg - Nullable: True Default: None|
|HALTEKOM                            |String(1,0,0)       |Ja/Nee/Onbekend, keuzelijst [jaNeeOnbekend] Nullable: False Default: O|
|ONDERHOUDSOVEREENKOMST              |String(255,0,0)     |Verwijzing naar de Onderhoud overeenkomst (documentnr, locatie e.d.)- Nullable: True Default: None|
|FOTO                                |String(255,0,0)     |Verwijzing naar naam/locatie van een foto vd Halte - Nullable: True Default: None|
|ELEKTROTECHN_TEKENING               |String(255,0,0)     |Verwijzing naar naam/locatie van een elektrotechnische tekening vd Halte - Nullable: True Default: None|
|WOONPLAATS                          |String(255,0,0)     |ToDo - Nullable: True Default: None|
|WINDROOSRICHTING                    |SmallInteger(0,3,0) |ToDo - Nullable: True|
|VERWERKINGSSTATUS_HALTE             |String(255,0,0)     |ToDo - Nullable: True Default: None|
|SHAPE                               |Geometry            |Vlak|
|SHAPE_Length                        |Double(0,0,0)       |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Area                          |Double(0,0,0)       |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|CONCESSIEVERL_GEBRUIK               |String(255,0,0)    |FK naar concessieverlener_tbl - voor het gebruik - Nullable: True Default: None|
|CONCESSIEVERL_PLAATSING             |String(255,0,0)     |FK naar concessieverlener_tbl - voor de plaatsing - Nullable: True Default: None|
|TRAJECT                             |String(255,0,0)     |FK naar traject_v - Nullable: True Default: None|
|IDENTIFICATIE                       |String(255,0,0)      |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)     |Nadere typering van het object, keuzelijst [typeSpecHLT] - Nullable: True Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)     |Status van de gegevens, keuzelijst [VERWERKINGSSTATUS] - Nullable: False Default: Nieuwl|
|OBJECTID                            |OID(38,0,0)         |Interne ID ArcGIS - Nullable: False|
|GLOBALID                            |GlobalID(38,0,0)    |Global Unique Identifier - Nullable: False|
|GISIB_ID                            |Integer(0,10,0)     |ID beheer openbare ruimte (GISIB) - Nullable: True|
|AD_ID                               |String(255,0,0)    |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]' - Nullable: False Default: None|
|OBJECTBEGINTIJD                     |Date(8,0,0)         |Datum waarop het object bij de bronhouder is ontstaan - Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)         |Datum waarop het object bij de bronhouder niet meer geldig is - Nullable: True|
|CREATED_USER                        |String(255,0,0)     |Naam van gebruiker die de rij heeft aangemaakt - Nullable: True Default: None|
|CREATED_DATE                        |Date(8,0,0)         |Aanmaakdatum - Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)      |Naam van gebruiker die de laatste mutatie heeft doorgevoerd - Nullable: True Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)         |Datum van de laatste mutatie - Nullable: True|
|BEHEERDER                           |String(255,0,0)     |Beheerder van het object, keuzelijst [BEHEERDER] - Nullable: True Default: None|
|ONDERHOUDER                         |String(255,0,0)     |Onderhouder van het object, keuzelijst [ONDERHOUDER] - Nullable: True Default: None|
|EIGENAAR                            |String(255,0,0)     |Eigenaar van het object, keuzelijst [INSTANTIE] - Nullable: True Default: None|
|DATALEVERANCIER                     |String(255,0,0)    |Leverancier van de data - Nullable: True Default: None| 

***
