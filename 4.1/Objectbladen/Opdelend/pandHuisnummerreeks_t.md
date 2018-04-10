## AREAALDATA.pandHuisnummerreeks_t

$ Feature dataset: Opdelend


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ BGT
* __Positionele nauwkeurigheid:__ conform BAG
* __Geometrie:__ Annotatie
* __Definitie:__ Bevat de reeks nummeraanduidingen behorend bij het pand ten behoeve van visualisatie.


***

|KOLOM                             |TYPE          	    |DEFINITIE|
|------                            |----          	    |-----    |
|OBJECTID                          |OID(0,38,0)         |PNH; Interne ID ArcGIS; Nullable: False|
|FEATUREID                         |Integer(0,10,0)     |PNH; Beschrijving; Nullable: True; Default: None|
|ZORDER                            |Integer(0,10,0)     |PNH; Beschrijving; Nullable: True; Default: None|
|ANNOTATIONCLASSID                 |Integer(0,10,0)     |PNH; Beschrijving; Nullable: True; Default: None|
|ELEMENT                           |Blob(0,0,0)         |PNH; Beschrijving; Nullable: True; Default: None|
|SYMBOLID                          |Integer(0,10,0)     |PNH; Beschrijving; Nullable: True; Default: None|
|STATUS                            |String(10,0,0)      |PNH; Beschrijving; Nullable: True; Default: 0|
|VERWERKINGSSTATUS                 |String(255,0,0)     |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|TEXTSTRING                        |String(255,0,0)     |PNH; Beschrijving; Nullable: True; Default: None|
|FONTNAME                          |String(255,0,0)     |PNH; Beschrijving; Nullable: True; Default: None|
|FONTSIZE                          |Double(0,10,0)      |PNH; Beschrijving; Nullable: True; Default: None|
|BOLD                              |SmallInteger(0,10,0)|PNH; Beschrijving; Nullable: True; Default: None|
|ITALIC                            |SmallInteger(0,10,0)|PNH; Beschrijving; Nullable: True; Default: None|
|UNDERLINE                         |SmallInteger(0,10,0)|PNH; Beschrijving; Nullable: True; Default: None|
|VERTICALALIGNMENT                 |SmallInteger(0,10,0)|PNH; Beschrijving; Nullable: True; Default: None|
|HORIZONTALALIGNMENT               |SmallInteger(0,10,0)|PNH; Beschrijving; Nullable: True; Default: None|
|XOFFSET                           |Double(0,10,0)      |PNH; Beschrijving; Nullable: True; Default: None|
|YOFFSET                           |Double(0,10,0)      |PNH; Beschrijving; Nullable: True; Default: None|
|ANGLE                             |Double(0,10,0)      |PNH; Beschrijving; Nullable: True; Default: None|
|FONTLEADING                       |Double(0,10,0)      |PNH; Beschrijving; Nullable: True; Default: None|
|WORDSPACING                       |Double(0,10,0)      |PNH; Beschrijving; Nullable: True; Default: None|
|CHARACTERWIDTH                    |Double(0,10,0)      |PNH; Beschrijving; Nullable: True; Default: None|
|CHARACTERSPACING                  |Double(0,10,0)      |PNH; Beschrijving; Nullable: True; Default: None|
|FLIPANGLE                         |Double(0,10,0)      |PNH; Beschrijving; Nullable: True; Default: None|
|OVERRIDE                          |Integer(0,10,0)     |PNH; Beschrijving; Nullable: True; Default: None|
|IDENTIFICATIEBAGVBOLAAGSTEHNR     |String(16,0,0)      |PNH; Beschrijving; Nullable: False; Default: None|
|IDENTIFICATIEBAGVBOHOOGSTEHNR     |String(16,0,0)      |PNH; Beschrijving; Nullable: True; Default: None|
|IDENTIFICATIE                     |String(255,0,0)     |PNH; Beschrijving; Nullable: False; Default: None|
|GLOBALID                          |GlobalID(38,0,0)    |PNH; Global Unique Identifier; Nullable: False|
|CREATED_USER                      |String(255,0,0)     |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                      |Date(8,0,0)         |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                  |String(50,0,0)      |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                  |Date(8,0,0)         |PNH; Datum van de laatste mutatie; Nullable: True|
|SHAPE                             |Geometry(0,0,0)     |PNH; Beschrijving; Nullable: True; Default: None|
|SHAPE_Length                      |Double(0,10,0)      |PNH; Beschrijving; Nullable: True; Default: None|
|SHAPE_Area                        |Double(0,10,0)      |PNH; Beschrijving; Nullable: True; Default: None|
***
