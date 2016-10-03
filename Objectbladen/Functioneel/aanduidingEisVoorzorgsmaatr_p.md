## AREAALDATA.aanduidingEisVoorzorgsmaatr_p

$ Feature dataset: Functioneel


* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL (2015)
* __Positionele nauwkeurigheid:__ 7,5 cm
* __SHAPE:__ Punt
* __Definitie:__ Een eis voorzorgsmaatregel geeft aan dat de beheerder van een net aangegeven heeft dat er sprake is van voorzorgsmaatregelen die getroffen dienen te worden. Dit betreft alleen de wettelijk geregelde eis voorzorgsmaatregel. (Bron: IMKL 2015)


***

|KOLOM                               |TYPE              |DEFINITIE|
|------                              |----              |-----    |
|SHAPE                               |Geometry           |Punt|
|IDENTIFICATIE                       |String(255,0,0)    |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
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
|DATALEVERANCIER                     |String(255,0,0)    |Leverancier van de data - Nullable: True Default: None|
|OMSCHRIJVING                        |String(255,0,0)    |Extra toelichting - Nullable: True Default: None|
|EISVOORZORGMAATREGEL                |String(255,0,0)    |Vermelding of er voorzorgsmaatregelen getroffen dienen te worden. Aangegeven wordt wat de voorzorgsmaatregel is - Nullable: True Default: None|
|NETRISICOOMSCHRIJVING               |String(50,0,0)     |IMKL: netRisicoOmschrijving - Nullable: False Default: None|
|INNETWERK                           |String(255,0,0)    |FK naar utiliteitsNet_tbl - Nullable: True Default: None|

***