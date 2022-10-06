## AREAALDATA.metaDomeinen_tbl

*Feature dataset: -*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt
* __Geometrie:__ Geen
* __Definitie:__ Tabel met alle domeinen, codes en omschrijvingen

***

|KOLOM                               |TYPE (length, precision, scale)               |DEFINITIE (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----               |-----    |
|IDENTIFICATIE                       |String(255,0,0)    |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|DOMEIN_NAAM                         |String(255,0,0)    |PNH; Naam van het domein; ; Nullable: True; Default: None; Visible: Yes|
|CODE                                |String(255,0,0)    |PNH; Code; ; Nullable: True; Default: None; Visible: Yes|
|OMSCHRIJVING                        |String(255,0,0)    |PNH; Waarde; ; Nullable: True; Default: None; Visible: Yes|
|DATALEVERANCIER                     |String(255,0,0)    |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|

***
