## AREAALDATA.nenConditiescore_tbl

*Feature dataset: -*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt
* __Geometrie:__ Geen
* __Definitie:__ Een inspectie geeft een momentopname weer hoe een kunswerk er voor staat. De NEN 2767-4 wordt gebruikt voor conditiescores. Het object NEN_Conditiescore is bedoelt om de inspectie resultaten van een bepaalt kunstwerk vast te leggen.

***

|KOLOM                               |TYPE (length, precision, scale)                  |DEFINITIE (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                  |-----    |
|VERWERKINGSSTATUS                   |String(255,0,0)       |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|CONDITIESCORE                       |Integer(0,10,0)       |PNH; Conditiescore conform NEN 2767-4; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |String(255,0,0)       |PNH; Extra opmerking; ; Nullable: True; Default: None; Visible: No|
|KW_ELEMENT_ID                       |String(255,0,0)       |PNH; FK naar kwElement_tbl; ; Nullable: True; Default: None; Visible: No|
|SCHEIDING_OEVERVAK                  |String(255,0,0)       |PNH; FK naar scheidingOevervak_l; ; Nullable: True; Default: None; Visible: Yes|
|BOUWDEEL_ID                         |String(255,0,0)       |PNH; FK naar bouwdeelKunstwerk_tbl; ; Nullable: True; Default: None; Visible: No|
|INSP_ID                             |String(255,0,0)       |PNH; FK naar nenInspectie_tbl; ; Nullable: True; Default: None; Visible: No|
|OEVERVAK_ID                         |String(255,0,0)       |PNH; FK naar oevervak_v; ; Nullable: True; Default: None; Visible: Yes|
|DATALEVERANCIER                     |String(255,0,0)       |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                       |String(255,0,0)       |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|OBJECTID                            |OID(38,0,0)           |PNH; Interne ID ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)      |PNH; Global Unique Identifier; ; Nullable: False; Default: None; Visible: No|
|GISIB_ID                            |Integer(0,10,0)       |PNH; ID beheer openbare ruimte (GISIB); ; Nullable: True; Default: None; Visible: No|
|AD_ID                               |String(255,0,0)       |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; ; Nullable: False; Default: None; Visible: Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)           |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)           |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|CREATED_USER                        |String(255,0,0)       |PNH; Naam van gebruiker die de rij heeft aangemaakt; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)           |PNH; Aanmaakdatum; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)        |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)           |PNH; Datum van de laatste mutatie; ; Nullable: True; Default: None; Visible: No|


***

