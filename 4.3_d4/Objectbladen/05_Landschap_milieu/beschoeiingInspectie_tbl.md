## AREAALDATA.beschoeiingInspectie_tbl

*Feature dataset: -*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Geen
* __Definitie:__ Inspectieobject met alle inspectiegegevens die ingewonnen zijn m.b.t. beschoeiingen 
(landschap en milieu)
* __Mapping_NTA8035:__ bs:InformationObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                  |-----    |
|VERWERKINGSSTATUS                   |TEXT(255,0,0)         |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|ADVIES_INSPECTIE                    |TEXT(255,0,0)         |PNH; Onderhoudsadvies n.a.v. inspectie; ; Nullable: True; Default: None; Visible: No|
|DATUM                               |DATE(8,0,0)           |PNH; Datum van inspectie; ; Nullable: True; Default: None; Visible: No|
|GESCHATTE_RESTLEVENSDUUR            |SHORT(0,5,0)          |PNH; Inschatting van resterende levensduur op het moment van de inspectie; ; Nullable: True; Default: None; Visible: No|
|INSPECTEUR                          |TEXT(255,0,0)         |PNH; Naam van inspecteur; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |TEXT(255,0,0)         |PNH; Opmerking m.b.t. onderhoud; ; Nullable: True; Default: None; Visible: No|
|SCHADE_TYPE1                        |TEXT(255,0,0)         |PNH; Schadebeeld; ; Nullable: True; Default: None; Visible: No|
|SCHADE_OMVANG1                      |TEXT(255,0,0)         |PNH; Omvang schade; ; Nullable: True; Default: None; Visible: No|
|INSP_INTENSITEIT1                   |TEXT(255,0,0)         |PNH; Intensiteit van de inspectie; ; Nullable: True; Default: None; Visible: No|
|SCHADE_TOELICHTING1                 |TEXT(255,0,0)         |PNH; Toelichting schade; ; Nullable: True; Default: None; Visible: No|
|SCHADE_TYPE2                        |TEXT(255,0,0)         |PNH; Schadebeeld; ; Nullable: True; Default: None; Visible: No|
|SCHADE_OMVANG2                      |TEXT(255,0,0)         |PNH; Omvang schade; ; Nullable: True; Default: None; Visible: No|
|INSP_INTENSITEIT2                   |TEXT(255,0,0)         |PNH; Intensiteit van de inspectie; ; Nullable: True; Default: None; Visible: No|
|SCHADE_TOELICHTING2                 |TEXT(255,0,0)         |PNH; Toelichting schade; ; Nullable: True; Default: None; Visible: No|
|SCHADE_TYPE3                        |TEXT(255,0,0)         |PNH; Schadebeeld; ; Nullable: True; Default: None; Visible: No|
|SCHADE_OMVANG3                      |TEXT(255,0,0)         |PNH; Omvang schade; ; Nullable: True; Default: None; Visible: No|
|INSP_INTENSITEIT3                   |TEXT(255,0,0)         |PNH; Intensiteit van de inspectie; ; Nullable: True; Default: None; Visible: No|
|SCHADE_TOELICHTING3                 |TEXT(255,0,0)         |PNH; Toelichting schade; ; Nullable: True; Default: None; Visible: No|
|BESCHOEIING_LM                      |TEXT(255,0,0)         |PNH; Verwijzende sleutel naar scheidingWater_l (simpel); ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |TEXT(255,0,0)         |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                       |TEXT(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|OBJECTID                            |OID(38,0,0)           |PNH; Interne ID ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)      |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)          |PNH; ID beheer openbare ruimte (GISIB); ; Nullable: True; Default: None; Visible: No|
|AD_ID                               |TEXT(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; ; Nullable: False; Default: None; Visible: Yes|
|OBJECTBEGINTIJD                     |DATE(8,0,0)           |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)           |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|CREATED_USER                        |TEXT(255,0,0)         |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)           |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)          |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)           |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|


***

