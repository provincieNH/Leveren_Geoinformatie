## AREAALDATA.ExtraDetailInfo_p

*Feature dataset: -*

* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL1.2.1
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Punt
* __Definitie:__ Puntgeometrie voor het leggen van een link naar aan een asset te koppelen document (nu enkel nog pdf's ondersteund).
* __Mapping_NTA8035:__ bs:InformationObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                          	|----          	        |-----    |
|OBJECTID                           |OID(38,0,0)            |PNH; Interne ID ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|bestandIdentificator               |String(255,0,0)        |PNH; Uniek ID dat in de IMKL-conversie wordt gegenereerd per gekoppeld document; ; Nullable: True; Default: None; Visible: No|
|ASSET_ID                           |String(255,0,0)        |PNH; Niet geimplementeerde koppeling naar het AD_ID van de asset waar het gerelateerde document betrekking op heeft; ; Nullable: False; Default: None; Visible: No|
|LABEL                              |String(255,0,0)        |PNH; Label van alle IMKL-objecten tbv annotatielaag; ; Nullable: True; Default: None; Visible: No|
|IMKL_InNetwork                     |String(255,0,0)        |PNH; Provincie aanduiding voor het type net, VB: VRI of OVL; keuzelijst [IMKL_InNetwork](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/IMKL_InNetwork.html); Nullable: False; Default: None; Visible: No|
|extraInfoType                      |String(255,0,0)        |PNH; Beschrijft het type document inhoudelijk; keuzelijst [extraInfoType](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/extraInfoType.html); Nullable: False; Default: None; Visible: No|
|bestandsnaam                       |String(255,0,0)        |PNH; Tbv gebruik in metadata.xml die met de documenten wordt aangeleverd aan het Kadaster; ; Nullable: False; Default: None; Visible: No|
|bestandMediaType                   |String(10,0,0)         |PNH; Op dit moment (IMKL1.2.1) wordt enkel pdf ondersteund; ; Nullable: False; Default: PDF; Visible: No|
|CREATED_USER                       |String(255,0,0)        |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                       |Date(8,0,0)            |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                   |String(50,0,0)         |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                   |Date(8,0,0)            |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                              |Geometry(0,0,0)        |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|

***
