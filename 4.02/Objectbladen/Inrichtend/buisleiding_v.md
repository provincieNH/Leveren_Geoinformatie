## AREAALDATA.buisleiding_v

$ Feature dataset: Inrichtend

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL - TODO: MOET NOG NAAR IMKL2015
* __Positionele nauwkeurigheid:__ 7,5 cm
* __SHAPE:__ Vlak
* __Definitie:__ Buisleidingen zijn leidingen met gevaarlijke inhoud, te weten:
1. aardgasleidingen met een uitwendige diameter van meer dan 50mm en een druk van meer dan 1600KPa
2. buisleidingen voor het vervoer van brandbare vloeistoffen van de categorieën K1, K2 of K3, met een uitwendige diameter van meer dan 100mm
3. buisleidingen voor andere gevaarlijke stoffen dan bedoeld onder 1. en 2., waarvoor het plaatsgebonden risico op een afstand van 5 meter gemeten vanaf het hart van de buisleiding hoger is dan (10)-6 per jaar.

***

|KOLOM                               |TYPE              |DEFINITIE|
|------                              |----              |-----    |
|AANTALBUIZEN                        |SmallInteger(0,10,0) |Aantal buizen gerepresenteerd door de SHAPE van dit object. Wordt alleen opgenomen indien het aantal groter is dan 1 en de buizen niet als afzonderlijke lijnen (kunnen) worden weergegeven - Nullable: False|
|AFWIJKENDEDIEPTE                    |String(255,0,0)      |Afwijking van de gangbare dieptelegging voor een leiding van dit thema. (Eenheid cm? TODO) [] - Nullable: True Default: None|
|bovengrondsZichtbaar                |String(1,0,0)        |Aangegeven wordt of de buisleiding bovengronds vanaf het maaiveld zichtbaar is, keuzelijst [jaNee] - Nullable: True Default: None|
|OMSCHRIJVING                        |String(255,0,0)      |Extra toelichting - Nullable: True Default: None|
|DIAMETERCM                          |SmallInteger(0,10,0) |Diameter van de buis in cm - Nullable: False|
|OPMERKING                           |String(3000,0,0)     |Opmerking - Nullable: True Default: None|
|PRODUCT                             |String(255,0,0)      |Het product dat door de leiding vervoerd wordt of kan worden vervoerd [] - Nullable: True Default: None|
|VERHOOGDRISICO                      |String(1,0,0)        |Verhoogd risico: Ja/Nee, keuzelijst [jaNee] Nullable: True Default: N|
|VOORZORGMAATREGEL                   |String(255,0,0)      |Vermelding of er voorzorgsmaatregelen getroffen dienen te worden. Aangegeven wordt wat de voorzorgsmaatregel is. [] - Nullable: True Default: None|
|MATERIAALTYPE                       |String(255,0,0)      |Type materiaal, keuzelijst [MATERIAALTYPE] - Nullable: True Default: None|
|THEMAKAART                          |String(255,0,0)      |Themakaart, keuzelijst [THEMAKAART] - Nullable: True Default: None|
|SHAPE                               |Geometry             |Lijn|
|SHAPE_Length                        |Double(0,0,0)        |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|TRAJECT                             |Guid(38,0,0)         |FK naar traject_v - Nullable: True Default: None|
|IDENTIFICATIE                       |String(255,0,0)      |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecBUI] - Nullable: True Default: None|
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
