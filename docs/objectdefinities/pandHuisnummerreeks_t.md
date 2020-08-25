## AREAALDATA.pandHuisnummerreeks_t

*Feature dataset: Opdelend*


* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ BGT
* __Positionele nauwkeurigheid:__ conform BAG
* __Geometrie:__ Annotatie
* __Definitie:__ Bevat de reeks nummeraanduidingen behorend bij het pand ten behoeve van visualisatie.
* __Mapping_BGT:__ pandHuisnummerreeks_t
* __Mapping_Gisib:__ x

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                            |----          	    |-----    |
|OBJECTID                          |OID(0,38,0)         |PNH; Interne ID ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|FEATUREID                         |Integer(0,10,0)     |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|ZORDER                            |Integer(0,10,0)     |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|ANNOTATIONCLASSID                 |Integer(0,10,0)     |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|SYMBOLID                          |Integer(0,10,0)     |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|STATUS                            |String(10,0,0)      |PNH; Beschrijving; keuzelijst [status](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/status.md); Nullable: True; Default: bestaand; Visible: No|
|VERWERKINGSSTATUS                 |String(255,0,0)     |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.md); Nullable: False; Default: Nieuw; Visible: Yes|
|TEXTSTRING                        |String(255,0,0)     |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|FONTNAME                          |String(255,0,0)     |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|FONTSIZE                          |Double(0,10,0)      |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|BOLD                              |SmallInteger(0,5,0) |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|ITALIC                            |SmallInteger(0,5,0) |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|UNDERLINE                         |SmallInteger(0,5,0) |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|VERTICALALIGNMENT                 |SmallInteger(0,5,0) |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|HORIZONTALALIGNMENT               |SmallInteger(0,5,0) |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|XOFFSET                           |Double(0,10,0)      |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|YOFFSET                           |Double(0,10,0)      |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|ANGLE                             |Double(0,10,0)      |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|FONTLEADING                       |Double(0,10,0)      |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|WORDSPACING                       |Double(0,10,0)      |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|CHARACTERWIDTH                    |Double(0,10,0)      |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|CHARACTERSPACING                  |Double(0,10,0)      |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|FLIPANGLE                         |Double(0,10,0)      |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|OVERRIDE                          |Integer(0,10,0)     |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIEBAGVBOLAAGSTEHNR     |String(16,0,0)      |PNH; Beschrijving; ; Nullable: False; Default: None; Visible: No|
|IDENTIFICATIEBAGVBOHOOGSTEHNR     |String(16,0,0)      |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                     |String(255,0,0)     |PNH; Beschrijving; ; Nullable: False; Default: None; Visible: No|
|GLOBALID                          |GlobalID(38,0,0)    |PNH; Global Unique Identifier; ; Nullable: False; Default: None; Visible: No|
|CREATED_USER                      |String(255,0,0)     |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                      |Date(8,0,0)         |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                  |String(50,0,0)      |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                  |Date(8,0,0)         |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                             |Geometry(0,0,0)     |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                      |Double(0,10,0)      |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Area                        |Double(0,10,0)      |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: Yes|
***
