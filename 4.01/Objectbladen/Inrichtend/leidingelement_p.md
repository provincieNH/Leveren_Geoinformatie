## AREAALDATA.leidingelement_p

$ Feature dataset: Inrichtend


* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL
* __Positionele nauwkeurigheid:__ 7,5 cm
* __SHAPE:__ Punt
* __Definitie:__ Een ondergronds object dat bij een leiding of een themakaart hoort. __LET OP:__ dit is het objecttype waar kolken etc. in vastgelegd worden!

***

|KOLOM                               |TYPE              |DEFINITIE|
|------                              |----              |-----    |
|bovengrondsZichtbaar                |String(1,0,0)       |Aangegeven wordt of het leidingelement bovengronds vanaf het maaiveld zichtbaar is, keuzelijst [jaNee] - Nullable: True Default: None|
|DATUMPLAATSING                      |Date(8,0,0)         |Datum Plaatsing - Nullable: True|
|OMSCHRIJVING                        |String(255,0,0)     |Extra toelichting - Nullable: True Default: None|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)|Levensverwachting (jaar TODO) - Nullable: True|
|OPMERKING                           |String(3000,0,0)    |Extra toelichting - Nullable: True Default: None|
|PLANJAAR                            |SmallInteger(0,10,0)|Planjaar - Nullable: True|
|PRODUCT                             |String(255,0,0)     |Het product dat door de leiding vervoerd wordt of kan worden vervoerd - Nullable: True Default: None|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0)|Restlevensduur - Nullable: True|
|VERHOOGDRISICO                      |String(1,0,0)       |Verhoogd risico Ja/Nee/Onbekend, keuzelijst [jaNeeOnbekend] Nullable: True Default: O|
|MATERIAALTYPE                       |String(255,0,0)     |Type materiaal, keuzelijst [MATERIAALTYPE] - Nullable: True Default: None|
|SHAPE                               |Geometry            |Punt|
|IDENTIFICATIE                       |String(255,0,0)    |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecLDE] - Nullable: True Default: None|
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
|CONSTRUCTIEGEGEVEN                  |String(255,0,0)       |Constructiegegevens - Nullable: True Default: None|
|HUIDIGESTATUS                       |String(50,0,0)       |Huidige status, keuzelijst [ConditionOfFacilityValue] - Nullable: False Default: None|
|INNETWERK                           |String(255,0,0)      |FK naar utiliteitsNet_tbl - Nullable: True Default: None|
|GEONAUWKEURIGHEIDXY                 |String(50,0,0)       |Nauwkeurigheid van de liggingsgegevens in het horizontale vlak, keuzelijst [NauwkeurigheidXYvalue] - Nullable: False Default: None|
|DIEPTELEGGING                       |String(255,0,0)      |FK naar diepteTovMaaiveld_p - Nullable: True Default: None|
|VERTICALE_POSITIE                   |Float(0,10,2)        |Verticale positie - Nullable: True Default: None|
|HOOGTE                              |SmallInteger(0,10,2) |Hoogte (m, 2 decimalen)  - Nullable: True Default: None|


***