## AREAALDATA.waterloop_l

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 25 cm
* __Geometrie:__ Lijn
* __Definitie:__ Terrein ingericht voor afvoer en berging van oppervlaktewater. BGT kent alleen vlakken. Dit objecttype zal uitgefaseerd worden.
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ Waterloop


***

|__KOLOM__                           |__TYPE (length, precision, scale)__          	|__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----          	                            |-----    |
|OBJECTID                            |OID(38,0,0)                                   |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)                              |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |String(255,0,0)                               |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |Integer(0,10,0)                               |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                       |String(255,0,0)                               |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|STATUS                              |String(10,0,0)                                |BGT; BGT status van het object; keuzelijst [status](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/status.md); Nullable: False; Default: bestaand; Visible: No|
|OBJECTBEGINTIJD                     |Date(8,0,0)                                   |BGT; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: False; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)                                   |BGT; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|VERWERKINGSSTATUS                   |String(255,0,0)                               |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.md); Nullable: False; Default: Nieuw; Visible: Yes|
|BEHEERDER                           |String(255,0,0)                               |PNH; Beheerder van het object; keuzelijst [BEHEERDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEERDER.md); Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |String(255,0,0)                               |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ONDERHOUDER.md); Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |String(255,0,0)                               |PNH; Eigenaar van het object; keuzelijst [INSTANTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/INSTANTIE.md); Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |String(255,0,0)                               |PNH; Nadere typering van het object; keuzelijst [typeSpecWTL](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecWTL.md); Nullable: True; Default: None; Visible: Yes|
|CAT_WATERLOOP                       |String(255,0,0)                               |PNH; Categorie waterloop; keuzelijst [CAT_WATERLOOP](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/CAT_WATERLOOP.md); Nullable: True; Default: None; Visible: Yes|
|JAAR_PLAATSING_AANLEG_GESCHAT       |String(1,0,0)                                 |PNH; Jaar plaatsing of aanleg is geschat: ja of nee; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.md); Nullable: True; Default: N; Visible: No|
|BODEMHOOGTE                         |Float(0,25,10)                                |PNH; Hoogte t.o.v. NAP; ; Nullable: True; Default: None; Visible: Yes|
|BIJZONDEREWAARDE                    |String(255,0,0)                               |PNH; Indicatie van bijzondere waarde; ; Nullable: True; Default: None; Visible: No|
|OPMERKINGMBTONDERH                  |String(255,0,0)                               |PNH; Opmerking met betrekking tot het onderhoud; ; Nullable: True; Default: None; Visible: No|
|PEILVAST                            |Float(0,25,10)                                |PNH; Vaste peil; ; Nullable: True; Default: None; Visible: No|
|PEILWINTER                          |Float(0,25,10)                                |PNH; Winter peil; ; Nullable: True; Default: None; Visible: No|
|PEILZOMER                           |Float(0,25,10)                                |PNH; Zomer peil; ; Nullable: True; Default: None; Visible: No|
|VERKANTINGTALUD                     |String(255,0,0)                               |PNH; TODO; ; Nullable: True; Default: None; Visible: No|
|WATERBREEDTE                        |Float(0,25,10)                                |PNH; Breedte Natte profiel in meters (2 decimalen); ; Nullable: True; Default: None; Visible: No|
|SLOOTVEGETATIE                      |String(1,0,0)                                 |PNH; Slootvegetatie dient verwerkt te worden: Ja/Nee; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.md); Nullable: True; Default: N; Visible: No|
|WATERDIEPTE                         |Float(0,25,10)                                |PNH; TODO; ; Nullable: True; Default: None; Visible: Yes|
|WATERSCHAP                          |String(30,0,0)                                |PNH; Naam Waterschap; keuzelijst [WATERSCHAP](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/WATERSCHAP.md); Nullable: True; Default: None; Visible: No|
|BERICHT_ID                          |String(128,0,0)                               |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|TRAJECT                             |String(255,0,0)                               |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/TRAJECT_NAAM.md); Nullable: True; Default: None; Visible: Yes|
|DATALEVERANCIER                     |String(255,0,0)                               |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |String(255,0,0)                               |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)                                   |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)                                |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)                                   |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry                                      |PNH; Lijn; ; Nullable: False; Default: None; Visible: Yes|
|SHAPE_Length                        |Double(0,0,0)                                 |PNH; Lengte in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|LENGTE                              |Double(0,0,0)                                 |PNH; Lengte in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|



***
