## AREAALDATA.waterloop_l

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 25 cm
* __Geometrie:__ Lijn
* __Definitie:__ Terrein ingericht voor afvoer en berging van oppervlaktewater.
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ Waterloop
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                           |__TYPE (length, precision, scale)__          	|__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----          	                            |-----    |
|OBJECTID                            |OID(38,0,0)                                   |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)                              |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |TEXT(255,0,0)                                 |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)                                  |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|OBJECTBEGINTIJD                     |DATE(8,0,0)                                   |BGT; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: False; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)                                   |BGT; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)                                 |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|BEHEERDER                           |TEXT(255,0,0)                                 |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)                                 |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |TEXT(255,0,0)                                 |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |TEXT(255,0,0)                                 |PNH; Nadere typering van het object; keuzelijst [typeSpecWTL]; Nullable: True; Default: None; Visible: Yes|
|CAT_WATERLOOP                       |TEXT(255,0,0)                                 |PNH; Categorie waterloop; keuzelijst [CAT_WATERLOOP]; Nullable: True; Default: None; Visible: Yes|
|JAAR_PLAATSING_AANLEG_GESCHAT       |TEXT(1,0,0)                                   |PNH; Jaar plaatsing of aanleg is geschat: ja of nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|BODEMHOOGTE                         |FLOAT(0,25,10)                                |PNH; Hoogte t.o.v. NAP; ; Nullable: True; Default: None; Visible: Yes|
|BIJZONDEREWAARDE                    |TEXT(255,0,0)                                 |PNH; Indicatie van bijzondere waarde; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |TEXT(255,0,0)                                 |PNH; Opmerking met betrekking tot het onderhoud; ; Nullable: True; Default: None; Visible: No|
|PEILVAST                            |FLOAT(0,25,10)                                |PNH; Vaste peil; ; Nullable: True; Default: None; Visible: No|
|PEILWINTER                          |FLOAT(0,25,10)                                |PNH; Winter peil; ; Nullable: True; Default: None; Visible: No|
|PEILZOMER                           |FLOAT(0,25,10)                                |PNH; Zomer peil; ; Nullable: True; Default: None; Visible: No|
|VERKANTINGTALUD                     |TEXT(255,0,0)                                 |PNH; TODO; ; Nullable: True; Default: None; Visible: No|
|WATERBREEDTE                        |FLOAT(0,25,10)                                |PNH; Breedte Natte profiel in meters (2 decimalen); ; Nullable: True; Default: None; Visible: No|
|SLOOTVEGETATIE                      |TEXT(1,0,0)                                   |PNH; Slootvegetatie dient verwerkt te worden: Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|WATERDIEPTE                         |FLOAT(0,25,10)                                |PNH; TODO; ; Nullable: True; Default: None; Visible: Yes|
|WATERSCHAP                          |TEXT(30,0,0)                                  |PNH; Naam Waterschap; keuzelijst [WATERSCHAP]; Nullable: True; Default: None; Visible: No|
|TRAJECT                             |TEXT(255,0,0)                                 |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM]; Nullable: True; Default: None; Visible: Yes|
|DATALEVERANCIER                     |TEXT(255,0,0)                                 |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |TEXT(255,0,0)                                 |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)                                   |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)                                  |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)                                   |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry                                      |PNH; Lijn; ; Nullable: False; Default: None; Visible: Yes|
|SHAPE_Length                        |DOUBLE(0,0,0)                                 |PNH; Lengte in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|LENGTE                              |DOUBLE(0,0,0)                                 |PNH; Lengte in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|



***
