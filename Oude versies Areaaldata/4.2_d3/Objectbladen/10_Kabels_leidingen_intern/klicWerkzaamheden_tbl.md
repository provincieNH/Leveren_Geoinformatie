## AREAALDATA.klicWerkzaamhedenaanduiding_tbl

*Feature dataset: -*

* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL (20151.2.1)
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Geen
* __Definitie:__alle mogelijke werkzaamheden en duiding daarvan door de netbeheerder in termen van prioriteit.
* __Mapping_NTA8035:__ bs:InformationObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                    |-----    |
|OBJECTID                            |OID(38,0,0)             |KLIC; Interne ID ArcGIS; ; Nullable: False; Default: None; Visible: No|
|soortWerkzaamheden                  |String(200,0,0)         |KLIC; Binnen IMKL 1.2.1 erkende werkzaamheden; keuzelijst [Werkzaamheden]; Nullable: True; Default: None; Visible: No|
|netbeheerderWerkAanduiding          |String(50,0,0)          |KLIC; Duiding van de werkzaamheden door de netbeheerder in termen van prioriteit; ; Nullable: True; Default: None; Visible: No|