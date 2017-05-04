## AREAALDATA.uithouder_p

$ Feature dataset: Inrichtend


* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15cm
* __SHAPE:__ Punt
* __Definitie:__ Een uithouder bevestigd aan een verlichtingsmast maakt het mogelijk om een daarvoor geschikt armatuur excentrisch van de mast te plaatsen zodat er een optimale lichtopbrengst gehaald wordt.(http://www.wegenwiki.nl/Uithouder) __NB:__ Een uithouder wordt alleen geregistreerd bij bijv. een portaal. Als het een enkelvoudige lichtmast betreft worden de uithouder gegevens bij de draagconstructie vastgelegd.


***

|KOLOM                              |TYPE                 |DEFINITIE|
|------                             |----                 |-----    |
|DATUMGARANTIE                      |Date(8,0,0)          |Datum garantie - Nullable: True|
|DATUMPLAATSING                     |Date(8,0,0)          |Datum plaatsing  - Nullable: True|
|OMSCHRIJVING                       |String(255,0,0)      |Extra toelichting - Nullable: True Default: None|
|ELEVHOEK                           |SmallInteger(0,10,0) |Elevatie hoek tov horizontaal  - Nullable: True|
|LENGTE                             |SmallInteger(0,10,0) |Lengte (m) - Nullable: True|
|SHAPE                              |Geometry             |Punt|
|TRAJECT                            |Guid(38,0,0)         |FK naar traject_v - Nullable: True Default: None|
|MAST                               |Guid(38,0,0)         |FK naar mastDraagconstructie_p - Nullable: True Default: None|
|IDENTIFICATIE                       |String(255,0,0)      |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecUIT] - Nullable: True Default: None|
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

***

