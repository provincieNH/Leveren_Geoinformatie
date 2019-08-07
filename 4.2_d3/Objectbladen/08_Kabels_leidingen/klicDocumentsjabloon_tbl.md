## AREAALDATA.klicDocumentsjabloon_tbl

*Feature dataset: -*

* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL (20151.2.1)
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Geen
* __Definitie:__Definitie van de Eisvoorzorgsmaatregelen-sjabloonbrief/brieven.

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                    |-----    |
|OBJECTID                            |OID(38,0,0)             |KLIC; Interne ID ArcGIS; ; Nullable: False; Default: None; Visible: No|
|sjabloonID_namespace                |String(50,0,0)          |KLIC; Bevat altijd IMKL-namespace 'nl.imkl'; ; Nullable: True; Default: nl.imkl; Visible: No|
|sjabloonID_lokaalID                 |String(50,0,0)          |KLIC; Lokaal ID van het EV-sjabloon. Altijd in de vorm Bronhoudercode.uniekID; ; Nullable: True; Default: None; Visible: No|
|bestandMediaType                    |String(100,0,0)         |KLIC; Bestandstype van het EV-sjabloon; ; Nullable: True; Default: http://definities.geostandaarden.nl/imkl2015/id/waarde/BestandMediaTypeValue/PDF; Visible: No|
|bestandsnaam                        |String(50,0,0)          |KLIC; Naam van het EV-sjabloon. Dient uniek te zijn; ; Nullable: True; Default: None; Visible: No|