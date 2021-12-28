## AREAALDATA.crowMeting_tbl

*Feature dataset: -*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Geen
* __Definitie:__ Een inspectie geeft een momentopname weer hoe een PNH wegvakonderdeel er op dat moment bij ligt. De CROW norm wordt gebruikt. Het object Meting is bedoeld om de metingen van een bepaald wegvakonderdeel vast te leggen. Metingen zijn: langsonvlakheid, stroefheid, zetting, spoorvorming, comfortindex
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ x
* __Aanwezig in BeheerApp (onder alias)__: Verharding (CROW Meting)
* __Mapping_NTA8035:__ bs:InformationObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                |-----    |
|VERWERKINGSSTATUS                   |TEXT(255,0,0)       |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.html); Nullable: False; Default: Nieuw; Visible: Yes|
|METING_WAARDE                       |FLOAT(0,10,4)       |PNH; Waarde van de Meting; ; Nullable: True; Default: None; Visible: No|
|METING_DATUM                        |DATE(8,0,0)         |PNH; Datum van de Meting; ; Nullable: True; Default: None; Visible: No|
|METING_TYPE                         |TEXT(50,0,0)        |PNH; Soort Meting; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |TEXT(3000,0,0)      |PNH; Opmerking; ; Nullable: True; Default: None; Visible: No|
|WEGDEEL                             |TEXT(255,0,0)       |PNH; Verwijzende sleutel naar wegdeel_v (simpel); ; Nullable: True; Default: None; Visible: No|
|OBJECTID                            |OID(38,0,0)         |PNH; Interne ID ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|DATALEVERANCIER                     |TEXT(255,0,0)       |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|GLOBALID                            |GlobalID(38,0,0)    |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: No||GISIB_ID                            |LONG(0,10,0)        |PNH; ID beheer openbare ruimte (GISIB); ; Nullable: True; Default: None; Visible: No|
|AD_ID                               |TEXT(255,0,0)       |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; ; Nullable: False; Default: None; Visible: Yes|
|COMFORT                             |TEXT(255,0,0)       |PNH; Meting conform CROW richtlijn, getal met eenheid m/s²(Cv waarde); ; Nullable: True; Default: None; Visible: No|
|COMFORT_DATE                        |DATE(8,0,0)         |PNH; Datum comfort meting; ; Nullable: True; Default: None; Visible: No|
|DEFLECTIE                           |TEXT(255,0,0)       |PNH; Meting conform CROW richtlijn (valgewichtdeflectie); ; Nullable: True; Default: None; Visible: No|
|DEFLECTIE_DATE                      |DATE(8,0,0)         |PNH; Datum deflectie meting; ; Nullable: True; Default: None; Visible: No|
|DWARSONVLAKHEID                     |TEXT(255,0,0)       |PNH; Meting verkanting conform RAW systematiek, getal met eenheid %; ; Nullable: True; Default: None; Visible: No|
|DWARSONVLAKHEID_DATE                |DATE(8,0,0)         |PNH; Datum dwarsonvlakheid meting; ; Nullable: True; Default: None; Visible: No|
|LANGSONVLAKHEID                     |TEXT(255,0,0)       |PNH; Meting conform RAW systematiek, getal met eenheid m/km; ; Nullable: True; Default: None; Visible: No|
|LANGSONVLAKHEID_DATE                |DATE(8,0,0)         |PNH; Datum langsonvlakheid meting; ; Nullable: True; Default: None; Visible: No|
|SPOORVORMING                        |TEXT(20,0,0)        |PNH; Meting conform CROW richtlijn 146 (globale visuele inspectie), getal met eenheid mm; ; Nullable: True; Default: None; Visible: No|
|SPOORVORMING_DATE                   |DATE(8,0,0)         |PNH; Datum spoorvorming meting; ; Nullable: True; Default: None; Visible: No|
|STROEFHEID                          |TEXT(20,0,0)        |PNH; Meting conform RAW systematiek, getal zonder eenheid; ; Nullable: True; Default: None; Visible: No|
|STROEFHEID_DATE                     |DATE(8,0,0)         |PNH; Datum stroefheid meting; ; Nullable: True; Default: None; Visible: No|
|INSPECTEUR                          |TEXT(255,0,0)       |PNH; Inspecterende partij spoorvorming, langsonvlakheid, dwarsonvlakheid.; ; Nullable: True; Default: None; Visible: No|
|OBJECTBEGINTIJD                     |DATE(8,0,0)         |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)         |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|CREATED_USER                        |TEXT(255,0,0)       |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)         |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)        |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)         |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|

***
