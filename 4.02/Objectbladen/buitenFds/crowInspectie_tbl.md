## AREAALDATA.crowInspectie_tbl

$ Feature dataset: -

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt
* __Geometrie:__ Geen
* __Definitie:__ Een inspectie geeft een momentopname weer hoe een wegvakonderdeel er op dat moment bij ligt; de
CROW-norm wordt gebruikt. Het object Inspectie is bedoelt om de algemene gegevens van een inspectie 'ronde' vast te leggen.

***

|KOLOM                               |TYPE                |DEFINITIE|
|------                              |----                |-----    |
|VERWERKINGSSTATUS                   |String(255,0,0)    |Status van de gegevens, keuzelijst [VERWERKINGSSTATUS] - Nullable: False Default: Nieuw|
|DATUM                               |Date(8,0,0)         |Datum inspectie - Nullable: True|
|BRON                                |String(10,0,0)      |Wie heeft de inspectie uitgevoerd - Nullable: True Default: None|
|METHODE                             |String(20,0,0)      |Gebruikte methode - Nullable: True Default: None|
|OPMERKING                           |String(200,0,0)     |Extra toelichting - Nullable: True Default: None|
|JAARTAL                             |SmallInteger(0,10,0)|TODO - Nullable: True|
|HYPERLINK                           |String(200,0,0)     |URL naar extern document - Nullable: True Default: None|
|IDENTIFICATIE                       |String(255,0,0)      |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
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

