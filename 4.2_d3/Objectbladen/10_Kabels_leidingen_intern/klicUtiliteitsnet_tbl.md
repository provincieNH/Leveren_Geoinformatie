## AREAALDATA.klicUtiliteitsnetaanduiding_tbl

*Feature dataset: -*

* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL (20151.2.1)
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Geen
* __Definitie:__Definitie van het utiliteitsnet waar de objecten waar een EV (eisvoorzorgsmaatregel) op van toepassing is onder vallen. Dit utiliteitsnet wordt omschreven onder het attribuut 'netbeheerderNetAanduiding' met een eigen naam. Deze naam hoeft niet per se te corresponderen met een bestaand utiliteitsnet, maar dient slechts als een van de variabelen, die bepaalt welke prioriteit aan een AanduidigsEisvoorzorgsmaatregelpolygoon dient te worden toegekend. Hierdoor kan bij een orientatie/graaf/calamiteitmelding op een locatie met overlappende AanduidingEisvoorzorgsmaatregelpolygonen, de polygoon met hoogste prioriteit, en het daaraan gekoppelde EV-brief-sjabloon geselecteerd worden. De kenmerken van deze tabel zijn ook kenmerken van de AanduidingEisvoorzorgsmaatregelpolygoon.
* __Mapping_NTA8035:__ bs:InformationObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                    |-----    |
|OBJECTID                            |OID(38,0,0)             |KLIC; Interne ID ArcGIS; ; Nullable: False; Default: None; Visible: No|
|thema                               |String(250,0,0)         |KLIC; IMKL-thema uit waardelijsten 1.2.1. Begint doorgaans met 'http://definities.geostandaarden.nl/imkl2015/id/waarde/Thema/'; keuzelijst [THEMA]; Nullable: True; Default: None; Visible: No|
|netbeheerderNetAanduiding           |String(50,0,0)          |KLIC; Eigen definitie van het utiliteitsnet waar de objecten waar een EV (eisvoorzorgsmaatregel) op van toepassing is; ; Nullable: True; Default: None; Visible: No|
|netbeheerderNetOmschrijving         |String(250,0,0)         |KLIC; Omschrijving van de netbeheerderNetAanduiding; ; Nullable: True; Default: None; Visible: No|