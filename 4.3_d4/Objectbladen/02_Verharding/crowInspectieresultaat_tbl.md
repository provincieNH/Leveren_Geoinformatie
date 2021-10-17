## AREAALDATA.crowInspectieresultaat_tbl

*Feature dataset: -*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Geen
* __Definitie:__ Een inspectie geeft een momentopname weer hoe een PNH wegvakonderdeel er op dat moment bijligt. De
CROW norm wordt gebruikt. Het object Inspectieresultaat is bedoelt om de inspectie resultaten van een bepaalt
wegvakonderdeel vast te leggen.
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ x
* __Aanwezig in BeheerApp (onder alias)__: Verharding (CROW Inspectieresultaat)
* __Mapping_NTA8035:__ bs:InformationObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__(oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                  |-----    |
|VERWERKINGSSTATUS                   |TEXT(255,0,0)         |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|SCHADESOORT                         |TEXT(10,0,0)          |PNH; Soort schade opname; ; Nullable: True; Default: None; Visible: No|
|SCHADEWAARDE                        |TEXT(10,0,0)          |PNH; numerieke waarde, indien van toepassing; ; Nullable: True; Default: None; Visible: No|
|SCHADECODE                          |TEXT(10,0,0)          |PNH; alfanumerieke waarde, indien van toepassing; ; Nullable: True; Default: None; Visible: Yes|
|OPMERKING                           |TEXT(10,0,0)          |PNH; Extra toelichting; ; Nullable: True; Default: None; Visible: No|
|WEGDEEL                             |TEXT(255,0,0)         |PNH; Verwijzende sleutel naar wegdeel_v (simpel); ; Nullable: True; Default: None; Visible: No|
|INSP_ID                             |TEXT(255,0,0)         |PNH; Verwijzende sleutel naar crowInspectie_tbl (simpel); ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |TEXT(255,0,0)         |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|OBJECTID                            |OID(38,0,0)           |PNH; Interne ID ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)      |PNH; Global Unique Identifier; ; Nullable: False; Default: None; Visible: No|
|GISIB_ID                            |LONG(0,10,0)          |PNH; ID beheer openbare ruimte (GISIB); ; Nullable: True; Default: None; Visible: No|
|AD_ID                               |TEXT(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; ; Nullable: False; Default: None; Visible: Yes|
|OBJECTBEGINTIJD                     |DATE(8,0,0)           |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)           |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|CREATED_USER                        |TEXT(255,0,0)         |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)           |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)          |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)           |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|


***

