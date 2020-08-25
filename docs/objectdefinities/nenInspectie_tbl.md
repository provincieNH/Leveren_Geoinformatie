## AREAALDATA.nenInspectie_tbl

*Feature dataset: -*

* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Geen
* __Definitie:__ Een inspectie geeft een conditiescore voor een kunstwerk. De NEN 2767-4 wordt gebruikt. Het object NEN_Inspectie is bedoelt om de algemene gegevens van een inspectie 'ronde' vast te leggen.

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__(oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----              |-----    |
|VERWERKINGSSTATUS                   |String(255,0,0)   |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.html); Nullable: False; Default: Nieuw; Visible: Yes|
|DATUM                               |Date(8,0,0)       |PNH; Datum inspectie; ; Nullable: True; Default: None; Visible: No|
|BRON                                |String(10,0,0)    |PNH; Wie heeft de inspectie uitgevoerd; ; Nullable: True; Default: None; Visible: No|
|METHODE                             |String(20,0,0)    |PNH; Welke methode is gebruikt; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |String(200,0,0)   |PNH; Extra toelichting; ; Nullable: True; Default: None; Visible: No|
|HYPERLINK                           |String(200,0,0)   |PNH; URL naar extern document; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                       |String(255,0,0)   |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|OBJECTID                            |OID(38,0,0)       |PNH; Interne ID ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)  |PNH; Global Unique Identifier; ; Nullable: False; Default: None; Visible: No|
|DATALEVERANCIER                     |String(255,0,0)   |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|GISIB_ID                            |Integer(0,10,0)   |PNH; ID beheer openbare ruimte (GISIB); ; Nullable: True; Default: None; Visible: No|
|AD_ID                               |String(255,0,0)   |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; ; Nullable: False; Default: None; Visible: Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)       |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)       |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|CREATED_USER                        |String(255,0,0)   |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)       |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)    |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)       |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|

***
