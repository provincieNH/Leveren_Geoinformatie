## AREAALDATA.plaatsbepalingspunt_p

$ Feature dataset: -

* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ BGT
* __Positionele nauwkeurigheid:__ nvt
* __Geometrie:__ Geen
* __Definitie:__ Punt dat is ingemeten en vervolgens gebruikt is bij en onderdeel uitmaakt van de begrenzing van BGT objecten.


***

|KOLOM                              |TYPE          	        |DEFINITIE|
|------                          	|----          	        |-----    |
|OBJECTID                           |OID(38,0,0)            |Interne ID ArcGIS - Nullable: False|
|IDENTIFICATIE                      |String(255,0,0)        |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|NAUWKEURIGHEID                     |Integer(0,0,0)         |Beschrijving - keuzelijst [] Nullable: True Default: None|
|DATUMINWINNING                     |Date(8,0,0)            |Beschrijving - keuzelijst [] Nullable: False Default: None|
|INWINNINGSMETHODE                  |String(50,0,0)         |Beschrijving - keuzelijst [inwinningsmethode] Nullable: False Default: None|
|INWINNENDEINSTANTIE                |String(5,0,0)          |Beschrijving - keuzelijst [] Nullable: True Default: None|
|GLOBALID                           |GlobalID(38,0,0)       |Global Unique Identifier - Nullable: False|
|CREATED_USER                       |String(255,0,0)        |Naam van gebruiker die de rij heeft aangemaakt - Nullable: True Default: None|
|CREATED_DATE                       |Date(8,0,0)            |Aanmaakdatum - Nullable: True|
|LAST_EDITED_USER                   |String(50,0,0)         |Naam van gebruiker die de laatste mutatie heeft doorgevoerd - Nullable: True Default: None|
|LAST_EDITED_DATE                   |Date(8,0,0)            |Datum van de laatste mutatie - Nullable: True|
|SHAPE                              |Geometry(0,0,0)        |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|BEHEERDER                           |String(255,0,0)     |Beheerder van het object, keuzelijst [BEHEERDER] - Nullable: True Default: None|
|ONDERHOUDER                         |String(255,0,0)     |Onderhouder van het object, keuzelijst [ONDERHOUDER] - Nullable: True Default: None|
|EIGENAAR                            |String(255,0,0)     |Eigenaar van het object, keuzelijst [INSTANTIE] - Nullable: True Default: None| 
|DATALEVERANCIER                     |String(255,0,0)     |Leverancier van de data - Nullable: True Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)     |Status van de gegevens, keuzelijst [VERWERKINGSSTATUS] - Nullable: False Default: Nieuw|

***
