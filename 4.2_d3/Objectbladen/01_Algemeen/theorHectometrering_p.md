## AREAALDATA.theorHectometrering_p

*Feature dataset: Functioneel*


* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Punt
* __Definitie:__  Hectometrering (indexeringspunten) van de wegen, vaarwegen en OV-trajecten in beheer bij de PNH.

***

|__KOLOM__                             |__TYPE (length, precision, scale)__                      |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer; zichtbaar in Toetsviewer)|
|------                              |----               |-----    |
|OBJECTID                            |OID(38,0,0)        |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes; Visible: No|
|GLOBALID                            |GlobalID(38,0,0)   |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes; Visible: No|
|AD_ID                               |String(255,0,0)    |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes; Visible: Yes|
|GISIB_ID                            |Integer(0,10,0)    |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No; Visible: No|
|VERWERKINGSSTATUS                   |String(255,0,0)    |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes; Visible: Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)        |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)        |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes; Visible: Yes|
|WEGZIJDE                            |String(10,0,0)     |PNH; Kant van de weg; keuzelijst [WEGZIJDE]; Nullable: True; Default: None; Visible: Yes; Visible: Yes|
|HECTOMETER                          |String(255,0,0)    |PNH; Hectometer aanduiding; ; Nullable: True; Default: None; Visible: Yes; Visible: Yes|
|WEG_OF_VAARWEGNUMMER                |String(255,0,0)    |PNH; Het nummer van de naastgelegen (vaar)weg of het OV-traject; ; Nullable: True; Default: None; Visible: Yes; Visible: Yes|
|DATALEVERANCIER                     |String(255,0,0)    |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No; Visible: Yes|
|CREATED_USER                        |String(255,0,0)    |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)        |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)     |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)        |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry           |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes; Visible: Yes|
|TRAJECT                             |String(255,0,0)    |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM]; Nullable: True; Default: None; Visible: Yes; Visible: Yes|

***
