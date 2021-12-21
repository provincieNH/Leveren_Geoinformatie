## AREAALDATA.pandHuisnummerreeks_t

*Feature dataset: Opdelend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ BGT
* __Positionele nauwkeurigheid:__ conform BAG
* __Geometrie:__ Annotatie
* __Definitie:__ Bevat de reeks nummeraanduidingen behorend bij het pand ten behoeve van visualisatie.
* __Mapping_BGT:__ pandHuisnummerreeks_t
* __Mapping_Gisib:__ x
* __Mapping_NTA8035:__ bs:SpatialRegion

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                            |----          	    |-----    |
|OBJECTID                          |OID(0,38,0)         |PNH; Interne ID ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|FEATUREID                         |LONG(0,10,0)        |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|ZORDER                            |LONG(0,10,0)        |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|ANNOTATIONCLASSID                 |LONG(0,10,0)        |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|SYMBOLID                          |LONG(0,10,0)        |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|STATUS                            |TEXT(10,0,0)        |PNH; Beschrijving; keuzelijst [AnnotationStatus]; Nullable: True; Default: bestaand; Visible: No|
|TEXTSTRING                        |TEXT(255,0,0)       |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|FONTNAME                          |TEXT(255,0,0)       |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|FONTSIZE                          |DOUBLE(0,10,0)      |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|BOLD                              |SHORT(0,5,0)        |PNH; Beschrijving; keuzelijst [BooleanSymbolValue]; Nullable: True; Default: None; Visible: No|
|ITALIC                            |SHORT(0,5,0)        |PNH; Beschrijving; keuzelijst [BooleanSymbolValue]; Nullable: True; Default: None; Visible: No|
|UNDERLINE                         |SHORT(0,5,0)        |PNH; Beschrijving; keuzelijst [BooleanSymbolValue]; Nullable: True; Default: None; Visible: No|
|VERTICALALIGNMENT                 |SHORT(0,5,0)        |PNH; Beschrijving; keuzelijst [VerticalAlignment]; Nullable: True; Default: None; Visible: No|
|HORIZONTALALIGNMENT               |SHORT(0,5,0)        |PNH; Beschrijving; keuzelijst [HorizontalAlignment]; Nullable: True; Default: None; Visible: No|
|XOFFSET                           |DOUBLE(0,10,0)      |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|YOFFSET                           |DOUBLE(0,10,0)      |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|ANGLE                             |DOUBLE(0,10,0)      |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|FONTLEADING                       |DOUBLE(0,10,0)      |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|WORDSPACING                       |DOUBLE(0,10,0)      |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|CHARACTERWIDTH                    |DOUBLE(0,10,0)      |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|CHARACTERSPACING                  |DOUBLE(0,10,0)      |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|FLIPANGLE                         |DOUBLE(0,10,0)      |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|OVERRIDE                          |LONG(0,10,0)        |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIEBAGVBOLAAGSTEHNR     |TEXT(16,0,0)        |PNH; Beschrijving; ; Nullable: False; Default: None; Visible: No|
|IDENTIFICATIEBAGVBOHOOGSTEHNR     |TEXT(16,0,0)        |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                     |TEXT(255,0,0)       |PNH; Beschrijving; ; Nullable: False; Default: None; Visible: No|
|GLOBALID_1                        |GlobalID(38,0,0)    |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: Yes|
|CREATED_USER                      |TEXT(255,0,0)       |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                      |DATE(8,0,0)         |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                  |TEXT(50,0,0)        |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                  |DATE(8,0,0)         |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                             |Geometry(0,0,0)     |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                      |DOUBLE(0,10,0)      |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Area                        |DOUBLE(0,10,0)      |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: Yes|
***
