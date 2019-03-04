## AREAALDATA.oeverReparatie_p

*Feature dataset: Functioneel*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__  nvt
* __Definitie:__ Een lokale reparatie aan een oevervak

***


|KOLOM                               |TYPE (length, precision, scale)                 |DEFINITIE (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                 |-----    |
|OBJECTID                            |OID(38,0,0)          |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)     |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: No|
|AD_ID                               |String(255,0,0)      |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |Integer(0,10,0)      |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |String(255,0,0)      |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)          |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)          |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|JAAR                                |SmallInteger(0,10,0) |PNH; Het jaar van de reparatie; ; Nullable: True; Default: None; Visible: No|
|RAPPORT                             |String(255,0,0)      |PNH; Complete pad naar de locatie van het rapport op de s-schijf; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |String(255,0,0)      |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |String(255,0,0)      |PNH; Naam van gebruiker die de rij heeft aangemaakt; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)          |PNH; Aanmaakdatum; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)       |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)          |PNH; Datum van de laatste mutatie; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry(0,0,0)      |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|
|OEVERVAK                            |String(255,0,0)      |PNH; FK naar oevervak_v; ; Nullable: True; Default: None; Visible: Yes|



***


