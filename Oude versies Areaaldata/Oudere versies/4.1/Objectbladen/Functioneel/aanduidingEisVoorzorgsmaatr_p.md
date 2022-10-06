## AREAALDATA.aanduidingEisVoorzorgsmaatr_p

*Feature dataset: Functioneel*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL (2015)
* __Positionele nauwkeurigheid:__ 7,5 cm
* __SHAPE:__ Punt
* __Definitie:__ Een eis voorzorgsmaatregel geeft aan dat de beheerder van een net aangegeven heeft dat er sprake is van voorzorgsmaatregelen die getroffen dienen te worden. Dit betreft alleen de wettelijk geregelde eis voorzorgsmaatregel. (Bron: IMKL 2015)


***

|KOLOM                               |TYPE               |DEFINITIE|
|------                              |----               |-----    |
|OBJECTID                            |OID(38,0,0)        |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:Yes|
|GLOBALID                            |GlobalID(38,0,0)   |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:No|
|AD_ID                               |String(255,0,0)    |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None; Visible:Yes|
|GISIB_ID                            |Integer(0,10,0)    |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|IDENTIFICATIE                       |String(255,0,0)    |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None; Visible:No|
|VERWERKINGSSTATUS                   |String(255,0,0)    |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible:Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)        |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True; Default: None; Visible:Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)        |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True; Visible:Yes|
|EISVOORZORGMAATREGEL                |String(255,0,0)    |PNH; Vermelding of er voorzorgsmaatregelen getroffen dienen te worden. Aangegeven wordt wat de voorzorgsmaatregel is; Nullable: True; Default: None; Visible:No|
|OMSCHRIJVING                        |String(255,0,0)    |PNH; Extra toelichting; Nullable: True; Default: None; Visible:Yes|
|NETRISICOOMSCHRIJVING               |String(50,0,0)     |IMKL; netRisicoOmschrijving; Nullable: False; Default: None; Visible:Yes|
|DATALEVERANCIER                     |String(255,0,0)    |PNH; Leverancier van de data; Nullable: True; Default: None; Visible:No|
|CREATED_USER                        |String(255,0,0)    |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None; Visible:No|
|CREATED_DATE                        |Date(8,0,0)        |PNH; Aanmaakdatum; Nullable: True; Visible:No|
|LAST_EDITED_USER                    |String(50,0,0)     |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None; Visible:No|
|LAST_EDITED_DATE                    |Date(8,0,0)        |PNH; Datum van de laatste mutatie; Nullable: True; Visible:No|
|SHAPE                               |Geometry           |PNH; Punt; Visible:Yes|
|INNETWERK                           |String(255,0,0)    |PNH; FK naar utiliteitsNet_tbl; Nullable: True; Default: None; Visible:No|

***
