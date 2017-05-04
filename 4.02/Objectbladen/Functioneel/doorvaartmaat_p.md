## AREAALDATA.doorvaartmaat_p

$ Feature dataset: Functioneel

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __SHAPE:__ Punt
* __Definitie:__ Aanduiding van Doorvaarthoogte bij bijv. Kunstwerken

***

|KOLOM                               |TYPE              |DEFINITIE|
|------                              |----              |-----    |
|DOORVAARTHOOGTEAFG                  |String(255,0,0)       |Doorvaarthoogte afgelezen [] - Nullable: True Default: None|
|GEMEENTE                            |String(255,0,0)       |Gemeente naam, keuzelijst [GEMEENTE] - Nullable: True Default: None|
|OMSCHRIJVING                        |String(255,0,0)       |Extra toelichting - Nullable: True Default: None|
|OBJECTNAAM                          |String(255,0,0)       |Object naam - Nullable: True Default: None|
|OPMERKING                           |String(3000,0,0)      |extra opmerking- Nullable: True Default: None|
|VOLGNUMMER                          |SmallInteger(0,10,0)  |Volgnummer - Nullable: False|
|SHAPE                               |Geometry              |Punt|
|BEHEEROBJECT                        |String(255,0,0)       |FK naar kunstwerkVast_p - Nullable: True Default: None|
|VAARWEG                             |String(255,0,0)       |FK naar vaarweg_l - Nullable: True Default: None|
|VAARWEGDEELTRAJECT                  |String(255,0,0)       |FK naar vaarwegdeeltraject_v - Nullable: True Default: None|
|IDENTIFICATIE                       |String(255,0,0)    |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
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

***


