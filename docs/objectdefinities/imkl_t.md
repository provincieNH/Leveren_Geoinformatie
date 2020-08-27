## AREAALDATA.IMKL_t

*Feature dataset: -*

* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL1.2.1
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Punt
* __Definitie:__ Annotatie behorend bij IMKL-objecten, tijdelijk nodig tbv weergave labels in KLIC-viewers. Deze feature class wordt enkel vanuit de FME IMKL-conversie workbench gemuteerd (bij iedere conversie leeg gegooid, en opnieuw gevuld.
* __Mapping_NTA8035:__ bs:InformationObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                          	|----          	        |-----    |
|OBJECTID                           |OID(38,0,0)            |PNH; Interne ID ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                           |GlobalID(38,0,0)       |PNH; Global Unique Identifier; ; Nullable: False; Default: None; Visible: No|
|IMKLID                             |String(255,0,0)        |PNH; Uniek ID dat in de IMKL-conversie wordt gegenereerd per annotatiepoint; ; Nullable: True; Default: None; Visible: No|
|LABEL                              |String(255,0,0)        |PNH; Label van alle IMKL-objecten tbv annotatielaag; ; Nullable: True; Default: None; Visible: No|
|ANNOTATIETYPE                      |String(255,0,0)        |PNH; Type annotatie volgens IMKL1.2.1; ; Nullable: False; Default: https://definities.geostandaarden.nl/imkl2015/doc/waarde/AnnotatieTypeValue/annotatielabel; Visible: No|
|ROTATIEHOEK                        |Float(0,10,1)          |PNH; Hoek van het annotatiepunt tussen de -180 en +180 graden, met max 1 decimaal nauwkeurig; ; Nullable: False; Default: None; Visible: No|
|AANGRIJPINGHORIZONTAAL             |String(255,0,0)        |PNH; Horizontale afstand van de labeltekst tot het labelpoint; ; Nullable: False; Default: http://definities.geostandaarden.nl/imkl2015/id/waarde/LabelpositieValue/0.5; Visible: No|
|AANGRIJPINGVERTICAAL               |String(255,0,0)        |PNH; Verticale afstand van de labeltekst tot het labelpoint; ; Nullable: False; Default: http://definities.geostandaarden.nl/imkl2015/id/waarde/LabelpositieValue/0.5; Visible: No|
|IMKL_InNetwork                     |String(255,0,0)        |PNH; Provincie aanduiding voor het type net, VB: VRI of OVL; keuzelijst [IMKL_InNetwork](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/IMKL_InNetwork.html); Nullable: False; Default: None; Visible: No|
|BRONHOUDER                         |String(255,0,0)        |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ONDERHOUDER.html); Nullable: True; Default: None; Visible: No|
|CREATED_USER                       |String(255,0,0)        |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                       |Date(8,0,0)            |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                   |String(50,0,0)         |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                   |Date(8,0,0)            |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                              |Geometry(0,0,0)        |PNH; Punt; ; Nullable: True; Default: None; Visible: Yes|


***
