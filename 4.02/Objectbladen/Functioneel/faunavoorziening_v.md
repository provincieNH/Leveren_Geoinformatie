## AREAALDATA.faunavoorziening_v

$ Feature dataset: Functioneel

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt
* __SHAPE:__ Vlak
* __Definitie:__ Een faunavoorziening is een voorziening die het passeren door dieren van infrastructuur geleidt, bevordert of juist voorkomt (bron: Leidraad Faunavoorzieningen bij Infrastructuur).
[Leidraad faunavoorzieningen](http://www.mjpo.nl/publicaties/leidraad_faunavoorzieningen_bij_infrastructuur/?page=leidraad)


***

|KOLOM                               |TYPE              |DEFINITIE|
|------                              |----              |-----    |
|FAUNASOORT                          |String(255,0,0)      |Doelsoorten - Nullable: True Default: None|
|FAUNADOELGROEP                      |String(255,0,0)      |Faunadoelgroep, keuzelijst [FAUNA_DOELGROEP] - Nullable: True Default: None|
|AANLEGJAAR                          |Integer(0,10,0)      |Aanlegjaar - Nullable: True|
|JAAR_PLAATSING_AANLEG_GESCHAT       |String(1,0,0)        |Jaar plaatsing of aanleg is geschat: Ja/Nee (keuzelijst [jaNee] - Nullable: True Default: N|
|OMSCHRIJVING                        |String(255,0,0)      |Extra toelichting - Nullable: True Default: None|
|FOTO                                |String(255,0,0)      |Verwijzing naar Foto - Nullable: True Default: None|
|HECTOMETER                          |String(255,0,0)      |Aanduiding Hectometrering - Nullable: True Default: None|
|LEVENSVERWACHTING                   |Integer(0,10,0)      |Levensverwachting - Nullable: True|
|OPMERKING                           |String(3000,0,0)     |Extra toelichting - Nullable: True Default: None|
|PLANJAAR                            |Integer(0,10,0)      |Planjaar - Nullable: True|
|RESTLEVENSDUUR                      |Integer(0,10,0)      |Restlevensduur - Nullable: True|
|ZIJDE                               |String(255,0,0)      |Zijde, keuzelijst [ZIJDE] - Nullable: True Default: None|
|RELATIEVEHOOGTELIGGING              |Integer(0,10,0)      |Beschrijving - [] - Nullable: False Default: 0|
|IDENTIFICATIE                       |String(255,0,0)      |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|SHAPE                               |Geometry             |Vlak|
|SHAPE_Length                        |Double(0,0,0)        |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Area                          |Double(0,0,0)        |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|TRAJECT                             |String(255,0,0)      |FK naar traject_v - Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecFNV] - Nullable: True Default: None|
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

***