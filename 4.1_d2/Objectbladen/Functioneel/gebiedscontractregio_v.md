## AREAALDATA.gebiedscontractregio_v

*Feature dataset: Functioneel*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt, Abstracte indeling
* __SHAPE:__ Vlak
* __Definitie:__ Perceelsindeling t.b.v. de onderhoudsbestekken en contractregio's.


***

|KOLOM                               |TYPE (length, precision, scale)                  |DEFINITIE (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                  |-----    |
|OBJECTID                            |OID(38,0,0)           |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)      |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |String(255,0,0)       |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |Integer(0,10,0)       |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                       |String(255,0,0)       |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |String(255,0,0)       |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)           |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)           |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|REGIO                               |String(255,0,0)       |PNH; Regio naam; keuzelijst [REGIO]; Nullable: True; Default: None; Visible: Yes|
|NUMMER                              |SmallInteger(0,10,0)  |PNH; Noord Holland is opgedeeld in 7 regio's. Hier het nummer van de regio invullen (1 tot en met 7); ; Nullable: False; Default: None; Visible: Yes|
|DATALEVERANCIER                     |String(255,0,0)       |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|OPDRACHTNEMER                       |String(255,0,0)       |PNH; Opdrachtnemer; ; Nullable: True; Default: None; Visible: Yes|
|CONTOPDRACHTNEMER                   |String(30,0,0)        |PNH; Contactpersoon van de opdrachtnemer, naam en telefoonnummer; ; Nullable: True; Default: None; Visible: No|
|CONTBSP                             |String(30,0,0)        |PNH; Contactpersoon bij BSP PNH voor regio, naam en telefooonnummer; ; Nullable: True; Default: None; Visible: No|
|CONTINFRA                           |String(30,0,0)        |PNH; Contactpersoon bij INFRA PNH voor regio, naam en telefoonnummer; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |String(255,0,0)       |PNH; Naam van gebruiker die de rij heeft aangemaakt; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)           |PNH; Aanmaakdatum; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)        |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)           |PNH; Datum van de laatste mutatie; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry              |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                        |Double(0,0,0)         |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld; ; Nullable: False; Default: None; Visible: Yes|
|SHAPE_Area                          |Double(0,0,0)         |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld; ; Nullable: False; Default: None; Visible: Yes|

***
