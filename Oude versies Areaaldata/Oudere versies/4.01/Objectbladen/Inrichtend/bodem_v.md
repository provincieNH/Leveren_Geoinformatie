## AREAALDATA.bodem_v

$ Feature dataset: Inrichtend

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 25 cm
* __SHAPE:__ Vlak
* __Definitie:__ Bodem van een waterdeel, hier worden de gegevens bijgehouden die van belang zijn voor o.a. baggeren


***

|KOLOM                               |TYPE                |DEFINITIE|
|------                              |----                |-----    |
|TYPEBAGGER                          |String(255,0,0)     |Type bagger, keuzelijst [TYPE_BAGGER] - Nullable: True Default: None|
|BOVENKANTSLIB                       |Float(0,25,10)      |Is de diepte van de wateroppervlakte tot de bovenkant van het slib lichaam. - Nullable: True Default: None|
|OMSCHRIJVING                        |String(255,0,0)     |Extra toelichting - Nullable: True Default: None|
|HMBEGIN                             |Float(0,25,10)      |Begin Hectometrering van Waterdeel - Nullable: True|
|HMEIND                              |Float(0,25,10)      |Eind Hectometrering van Waterdeel - Nullable: True|
|LENGTE                              |SmallInteger(0,10,0)|Lengte van het bodemdeel - Nullable: True Default: None|
|PEILJAAR                            |Date(8,0,0)         |Laatste jaar waarin gepeild is - Nullable: True Default: None|
|JAAR_BAGGEREN                       |Date(8,0,0)         |Laatste jaar waarin gebaggerd is - Nullable: True Default: None|
|JAAR_PLAATSING_AANLEG_GESCHAT       |String(1,0,0)       |Jaar plaatsing of aanleg is geschat: Ja/Nee (keuzelijst [jaNee] - Nullable: True Default: N|
|ONDERKANTSLIB                       |Float(0,25,10)      |Is de diepte van de wateroppervlakte tot de onderkant van het slib lichaam.  - Nullable: True Default: None|
|OPMERKING                           |String(3000,0,0)    |Extra toelichting  - Nullable: True Default: None|
|SHAPE                               |Geometry            |Vlak|
|SHAPE_Length                        |Double(0,0,0)       |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Area                          |Double(0,0,0)       |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|VAARWEGDEELTRAJECT                  |String(255,0,0)     |FK naar vaarwegdeeltraject_v  - Nullable: True Default: None|
|IDENTIFICATIE                       |String(255,0,0)    |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecBDM] - Nullable: True Default: None|
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


