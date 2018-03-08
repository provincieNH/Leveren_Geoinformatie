## AREAALDATA.beschoeiingInspectie_tbl

$ Feature dataset: -


* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt
* __Geometrie:__ Geen
* __Definitie:__ Inspectieobject met alle inspectiegegevens die ingewonnen zijn m.b.t. beschoeiingen 
(landschap en milieu)


***

|KOLOM                               |TYPE                  |DEFINITIE|
|------                              |----                  |-----    |
|VERWERKINGSSTATUS                   |String(255,0,0)       |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|ADVIES_INSPECTIE                    |String(255,0,0)       |PNH; Onderhoudsadvies n.a.v. inspectie; Nullable: True; Default: None|
|DATUM                               |Date(8,0,0)           |PNH; Datum van inspectie; Nullable: True|
|GESCHATTE_RESTLEVENSDUUR            |SmallInteger(0,10,0)  |PNH; Inschatting van resterende levensduur op het moment van de inspectie; Nullable: True|
|INSPECTEUR                          |String(255,0,0)       |PNH; Naam van inspecteur; Nullable: True; Default: None|
|OPMERKING                           |String(255,0,0)       |PNH; Opmerking m.b.t. onderhoud; Nullable: True; Default: None|
|SCHADE_TYPE1                        |String(255,0,0)       |PNH; Schadebeeld; Nullable: True; Default: None|
|SCHADE_OMVANG1                      |String(255,0,0)       |PNH; Omvang schade; Nullable: True; Default: None|
|INSP_INTENSITEIT1                   |String(255,0,0)       |PNH; Intensiteit van de inspectie; Nullable: True; Default: None|
|SCHADE_TOELICHTING1                 |String(255,0,0)       |PNH; Toelichting schade; Nullable: True; Default: None|
|SCHADE_TYPE2                        |String(255,0,0)       |PNH; Schadebeeld; Nullable: True; Default: None|
|SCHADE_OMVANG2                      |String(255,0,0)       |PNH; Omvang schade; Nullable: True; Default: None|
|INSP_INTENSITEIT2                   |String(255,0,0)       |PNH; Intensiteit van de inspectie; Nullable: True; Default: None|
|SCHADE_TOELICHTING2                 |String(255,0,0)       |PNH; Toelichting schade; Nullable: True; Default: None|
|SCHADE_TYPE3                        |String(255,0,0)       |PNH; Schadebeeld; Nullable: True; Default: None|
|SCHADE_OMVANG3                      |String(255,0,0)       |PNH; Omvang schade; Nullable: True; Default: None|
|INSP_INTENSITEIT3                   |String(255,0,0)       |PNH; Intensiteit van de inspectie; Nullable: True; Default: None|
|SCHADE_TOELICHTING3                 |String(255,0,0)       |PNH; Toelichting schade; Nullable: True; Default: None|
|BESCHOEIING_LM                      |String(255,0,0)       |PNH; FK naar scheiding_l; Nullable: True; Default: None|
|DATALEVERANCIER                     |String(255,0,0)       |PNH; Leverancier van de data; Nullable: True; Default: None|
|IDENTIFICATIE                       |String(255,0,0)       |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None|
|OBJECTID                            |OID(38,0,0)           |PNH; Interne ID ArcGIS; Nullable: False|
|GLOBALID                            |GlobalID(38,0,0)      |PNH; Global Unique Identifier; Nullable: False|
|GISIB_ID                            |Integer(0,10,0)       |PNH; ID beheer openbare ruimte (GISIB); Nullable: True|
|AD_ID                               |String(255,0,0)       |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; Nullable: False; Default: None|
|OBJECTBEGINTIJD                     |Date(8,0,0)           |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)           |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|CREATED_USER                        |String(255,0,0)       |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)           |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)        |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)           |PNH; Datum van de laatste mutatie; Nullable: True|


***

