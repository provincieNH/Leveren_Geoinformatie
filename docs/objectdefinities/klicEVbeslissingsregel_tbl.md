## AREAALDATA.klicVoorzorgsmaatregelbeslissingsregel_tbl

*Feature dataset: -*

* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL (20151.2.1)
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Geen
* __Definitie:__Daadwerkelijke EV-prioriteittabel. De prioriteit die in deze tabel wordt opgegeven (let op: 1 = hoogste) is bepalend voor het EV-briefsjabloon dat wordt uitgestuurd. De waarden uit de kenmerken uit deze tabel zijn ook als placeholder te gebruiken in het te selecteren EV-sjabloon.
* __Mapping_NTA8035:__ bs:InformationObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                    |-----    |
|OBJECTID                            |OID(38,0,0)             |KLIC; Interne ID ArcGIS; ; Nullable: False; Default: None; Visible: No|
|thema                               |String(250,0,0)         |KLIC; IMKL-thema uit waardelijsten 1.2.1. Begint doorgaans met 'http://definities.geostandaarden.nl/imkl2015/id/waarde/Thema/'; keuzelijst [THEMA](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/THEMA.html); Nullable: True; Default: None|
|netbeheerderNetAanduiding           |String(50,0,0)          |KLIC; Eigen definitie van het utiliteitsnet waar de objecten waar een EV (eisvoorzorgsmaatregel) op van toepassing is; ; Nullable: True; Default: None; Visible: No|
|aanvraagSoort                       |String(250,0,0)         |KLIC; Geeft aan of het een orientatie, graaf, of calamiteitmelding betreft. Begint met 'http://definities.geostandaarden.nl/imkl2015/id/waarde/AanvraagSoortValue/'; keuzelijst [AanvraagSoort](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/AanvraagSoort.html); Nullable: True; Default: None; Visible: No|
|netbeheerderWerkAanduiding          |String(100,0,0)         |KLIC; Een omschrijving van de gegeven prioriteit; ; Nullable: True; Default: None; Visible: No|
|maatregel                           |String(50,0,0)          |KLIC; Maatregel waartoe een grondroerder verplicht is bij een orientatie/graaf/calamiteitmelding; ; Nullable: True; Default: None; Visible: No|
|maatregelPrioriteit                 |SmallInteger(0,5,0)     |KLIC; Prioriteitstelling obv combinaties van waarden in overige attributen. Let op: ivm prioriteitsstelling dient gegeven prioriteit dient uniek te zijn, waarbij 1 = hoogste; ; Nullable: True; Default: None; Visible: No|