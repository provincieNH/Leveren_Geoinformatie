## AREAALDATA.plaatsbepalingspunt_p

*Feature dataset: -*

* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ BGT
* __Positionele nauwkeurigheid:__ nvt
* __Geometrie:__ Geen
* __Definitie:__ Punt dat is ingemeten en vervolgens gebruikt is bij en onderdeel uitmaakt van de begrenzing van BGT objecten.


***

|KOLOM                              |TYPE (length, precision, scale)          	        |DEFINITIE (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                          	|----          	        |-----    |
|OBJECTID                           |OID(38,0,0)            |PNH; Interne ID ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|IDENTIFICATIE                      |String(255,0,0)        |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|NAUWKEURIGHEID                     |Integer(0,0,0)         |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|DATUMINWINNING                     |Date(8,0,0)            |PNH; Beschrijving; ; Nullable: False; Default: None; Visible: No|
|INWINNINGSMETHODE                  |String(50,0,0)         |PNH; Beschrijving; keuzelijst [inwinningsmethode]; Nullable: False; Default: None; Visible: No|
|INWINNENDEINSTANTIE                |String(5,0,0)          |PNH; Beschrijving; ; Nullable: True; Default: None; Visible: No|
|GLOBALID                           |GlobalID(38,0,0)       |PNH; Global Unique Identifier; ; Nullable: False; Default: None; Visible: No|
|CREATED_USER                       |String(255,0,0)        |PNH; Naam van gebruiker die de rij heeft aangemaakt; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                       |Date(8,0,0)            |PNH; Aanmaakdatum; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                   |String(50,0,0)         |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                   |Date(8,0,0)            |PNH; Datum van de laatste mutatie; ; Nullable: True; Default: None; Visible: No|
|SHAPE                              |Geometry(0,0,0)        |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|
|BEHEERDER                          |String(255,0,0)        |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                        |String(255,0,0)        |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: No|
|EIGENAAR                           |String(255,0,0)        |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                    |String(255,0,0)        |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                  |String(255,0,0)        |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|

***
