## AREAALDATA.lamp_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __SHAPE:__ Punt
* __Definitie:__ component in een lantaarn of armatuur met als functie verlichten.


***

|KOLOM                               |TYPE (length, precision, scale)                   |DEFINITIE (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                   |-----    |
|OBJECTID                            |OID(38,0,0)            |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)       |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: No|
|AD_ID                               |String(255,0,0)        |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |Integer(0,10,0)        |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                       |String(255,0,0)        |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|TYPESPEC                            |String(255,0,0)        |PNH; Nadere typering van het object; keuzelijst [typeSpecLAM]; Nullable: True; Default: None; Visible: Yes|
|VERWERKINGSSTATUS                   |String(255,0,0)        |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)            |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)            |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|BEHEERDER                           |String(255,0,0)        |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |String(255,0,0)        |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |String(255,0,0)        |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|AANTAL                              |SmallInteger(0,10,0)   |PNH; Aantal; ; Nullable: True; Default: None; Visible: No|
|DATUMGARANTIE                       |Date(8,0,0)            |PNH; Datum en jaartal tot wanneer de garantie geldig is; ; Nullable: True; Default: None; Visible: No|
|DATUMPLAATSING                      |Date(8,0,0)            |PNH; Datum Plaatsing; ; Nullable: True; Default: None; Visible: No|
|OMSCHRIJVING                        |String(255,0,0)        |PNH; Extra toelichting; ; Nullable: True; Default: None; Visible: Yes|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)   |PNH; Levensverwachting; ; Nullable: True; Default: None; Visible: No|
|PLANJAAR                            |SmallInteger(0,10,0)   |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|FABRIKANTTYPECODE                   |String(255,0,0)        |PNH; Fabrikanttypecode; keuzelijst [FABRIKANT_TYPECODE]; Nullable: True; Default: None; Visible: Yes|
|ARMATUUR                            |String(255,0,0)        |PNH; FK naar straatmeubilair_p; ; Nullable: True; Default: None; Visible: No|
|LANTAAR                             |String(255,0,0)        |PNH; FK naar lantaarn_p; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |String(255,0,0)        |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry               |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|
|CREATED_USER                        |String(255,0,0)        |PNH; Naam van gebruiker die de rij heeft aangemaakt; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)            |PNH; Aanmaakdatum; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)         |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)            |PNH; Datum van de laatste mutatie; ; Nullable: True; Default: None; Visible: No|

***


