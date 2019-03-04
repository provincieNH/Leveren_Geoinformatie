## AREAALDATA.utiliteitsNet_tbl

*Feature dataset: -*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL (2015)
* __Positionele nauwkeurigheid:__ n.v.t.
* __SHAPE:__ Geen
* __Definitie:__ Een verzameling netwerkelementen die tot ��n type nutsvoorzieningennet behoren. (Bron: INSPIRE)

***

|KOLOM                               |TYPE (length, precision, scale)                    |DEFINITIE (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                    |-----    |
|IDENTIFICATIE                       |String(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|TYPESPEC                            |String(255,0,0)         |PNH; Nadere typering van het object, uit INSPIRE:UtilityNetworkTypeValue; keuzelijst [TypeSpecUTN]; Nullable: True; Default: onbekend; Visible: No|
|VERWERKINGSSTATUS                   |String(255,0,0)         |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: No|
|OBJECTID                            |OID(38,0,0)             |PNH; Interne ID ArcGIS; ; Nullable: False; Default: None; Visible: No|
|GLOBALID                            |GlobalID(38,0,0)        |PNH; Global Unique Identifier; ; Nullable: False; Default: None; Visible: No|
|GISIB_ID                            |Integer(0,10,0)         |PNH; ID beheer openbare ruimte (GISIB); ; Nullable: True; Default: None; Visible: No|
|AD_ID                               |String(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; ; Nullable: False; Default: None; Visible: No|
|OBJECTBEGINTIJD                     |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: No|
|OBJECTEINDTIJD                      |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |String(255,0,0)         |PNH; Naam van gebruiker die de rij heeft aangemaakt; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)             |PNH; Aanmaakdatum; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)          |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)             |PNH; Datum van de laatste mutatie; ; Nullable: True; Default: None; Visible: No|
|DATUMPLAATSING                      |Date(8,0,0)             |PNH; Datum plaatsing installatie; ; Nullable: True; Default: None; Visible: No|
|OMSCHRIJVING                        |String(255,0,0)         |PNH; Extra toelichting; ; Nullable: True; Default: None; Visible: No|
|INSTALLATIENUMMER                   |Integer(0,10,0)         |PNH; Bestaande uit 4 cijfers: de eerste drie het nummerdeel van het wegnummer (N201 -> 201), de laatste een volgnummer van ��n positie (1 t/m 9); ; Nullable: True; Default: None; Visible: No|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)    |PNH; TODO; ; Nullable: True; Default: None; Visible: No|
|PLANJAAR                            |SmallInteger(0,10,0)    |PNH; TODO; ; Nullable: True; Default: None; Visible: No|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0)    |PNH; Restlevensduur; ; Nullable: True; Default: None; Visible: No|
|BEHEERDER                           |String(255,0,0)         |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: No|
|ONDERHOUDER                         |String(255,0,0)         |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: No|
|EIGENAAR                            |String(255,0,0)         |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |String(255,0,0)         |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|TRAJECT                             |String(255,0,0)         |PNH; FK naar traject_v; keuzelijst [TRAJECT_NAAM] ; Nullable: True; Default: None; Visible: No|
|KRUISPUNT                           |String(255,0,0)         |PNH; FK naar kruispunt_p; ; Nullable: True; Default: None; Visible: No|
|HUIDIGESTATUS                       |String(50,0,0)          |PNH; Huidige status; keuzelijst [ConditionOfFacilityValue]; Nullable: False; Default: None; Visible: No|
|STANDAARDDIEPTELEGGING              |String(255,0,0)         |PNH; FK naar diepteTovMaaiveld_p; ; Nullable: False; Default: None; Visible: No|
|VERTICALE_POSITIE                   |Float(0,10,2)           |PNH; Verticale positie; ; Nullable: True; Default: None; Visible: No|
|NAAM_CONTACTPERSOON                 |String(255,0,0)         |PNH; Naam contactpersoon; ; Nullable: True; Default: None; Visible: No|
|TELNR_CONTACTPERSOON                |String(255,0,0)         |PNH; Telefoonnummer contactpersoon; ; Nullable: True; Default: None; Visible: No|
|EMAIL_CONTACTPERSOON                |String(255,0,0)         |PNH; E-mail contactpersoon; ; Nullable: True; Default: None; Visible: No|
|AUTORITEITSROL                      |String(255,0,0)         |INSPIRE; authorityRole; ; Nullable: True; Default: None; Visible: No|
|THEMA                               |String(255,0,0)         |PNH; Themakaart; keuzelijst [THEMA]; Nullable: True; Default: None; Visible: No|

***
