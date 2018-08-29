## AREAALDATA.spoorrail_l

$ Feature dataset: Inrichtend


* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __SHAPE:__ Lijn
* __Definitie:__ Twee stalen staven op een onderling vaste afstand waarover trein, tram, metro of kraan rijden. __LET OP:__ Dit is het 'oude' objecttype wat op termijn uitgefaseerd zal worden. spoor_l is het BGT objecttype.


***

|KOLOM                               |TYPE                |DEFINITIE|
|------                              |----                |-----    |
|OMSCHRIJVING                        |String(255,0,0)     |Extra toelichting - Nullable: True Default: None|
|HECTOMETER                          |String(255,0,0)     |Hectometrering  - Nullable: True Default: None|
|ZIJDE                               |String(255,0,0)     |Zijde, keuzelijst [ZIJDE] - Nullable: True Default: None|
|RELATIEVEHOOGTELIGGING              |SmallInteger(0,0,0) |Beschrijving - [] - Nullable: False Default: 0|
|SHAPE                               |Geometry            |Lijn|
|SHAPE_Length                        |Double(0,0,0)       |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|IDENTIFICATIE                       |String(255,0,0)     |BGT, Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat  - Nullable: True Default: None|
|TRAJECT                             |String(255,0,0)     |FK naar traject_v - Nullable: True Default: None|
|IDENTIFICATIE                       |String(255,0,0)     |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)     |Nadere typering van het object, keuzelijst [typeSpecSPO] - Nullable: True Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)     |Status van de gegevens, keuzelijst [VERWERKINGSSTATUS] - Nullable: False Default: Nieuw|
|OBJECTID                            |OID(38,0,0)         |Interne ID ArcGIS - Nullable: False|
|GLOBALID                            |GlobalID(38,0,0)    |Global Unique Identifier - Nullable: False|
|GISIB_ID                            |Integer(0,10,0)     |ID beheer openbare ruimte (GISIB) - Nullable: True|
|AD_ID                               |String(255,0,0)     |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]' - Nullable: False Default: None|
|OBJECTBEGINTIJD                     |Date(8,0,0)         |Datum waarop het object bij de bronhouder is ontstaan - Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)         |Datum waarop het object bij de bronhouder niet meer geldig is - Nullable: True|
|CREATED_USER                        |String(255,0,0)     |Naam van gebruiker die de rij heeft aangemaakt - Nullable: True Default: None|
|CREATED_DATE                        |Date(8,0,0)         |Aanmaakdatum - Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)      |Naam van gebruiker die de laatste mutatie heeft doorgevoerd - Nullable: True Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)         |Datum van de laatste mutatie - Nullable: True|
|BEHEERDER                           |String(255,0,0)     |Beheerder van het object, keuzelijst [BEHEERDER] - Nullable: True Default: None|
|ONDERHOUDER                         |String(255,0,0)     |Onderhouder van het object, keuzelijst [ONDERHOUDER] - Nullable: True Default: None|
|EIGENAAR                            |String(255,0,0)     |Eigenaar van het object, keuzelijst [INSTANTIE] - Nullable: True Default: None| 
|DATALEVERANCIER                     |String(255,0,0)     |Leverancier van de data - Nullable: True Default: None|


***
