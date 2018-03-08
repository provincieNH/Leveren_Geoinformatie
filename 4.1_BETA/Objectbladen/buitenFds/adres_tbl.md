## AREAALDATA.adres_tbl

$ Feature dataset: -


* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt
* __Geometrie:__ Geen
* __Definitie:__ Een object met adresgegevens, om naar te verwijzen vanuit kunstwerken, vri_; en ovl_kasten

***

|KOLOM                               |TYPE                |DEFINITIE|
|-----                               |----                |------    |
|STRAAT                              |String(255,0,0)     |PNH; TODO; Nullable: True; Default: None|
|HUISNUMMER                          |Integer(0,10,0)     |PNH; TODO; Nullable: True|
|TOEVOEGING                          |String(10,0,0)      |PNH; TODO; Nullable: True; Default: None|
|POSTCODE                            |String(10,0,0)      |PNH; TODO; Nullable: True; Default: None|
|PLAATS                              |String(255,0,0)     |PNH; TODO; Nullable: True; Default: None|
|IDENTIFICATIE                       |String(255,0,0)     |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True;; Default: None|
|OBJECTID                            |OID(38,0,0)         |PNH; Interne ID ArcGIS; Nullable: False|
|VERWERKINGSSTATUS                   |String(255,0,0)     |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|GLOBALID                            |GlobalID(38,0,0)    |PNH; Global Unique Identifier; Nullable: False|
|GISIB_ID                            |Integer(0,10,0)     |PNH; ID beheer openbare ruimte (GISIB); Nullable: True|
|AD_ID                               |String(255,0,0)     |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; Nullable: False; Default: None|
|OBJECTBEGINTIJD                     |Date(8,0,0)         |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)         |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|DATALEVERANCIER                     |String(255,0,0)     |PNH; Leverancier van de data; Nullable: True; Default: None|
|CREATED_USER                        |String(255,0,0)     |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)         |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)      |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)         |PNH; Datum van de laatste mutatie; Nullable: True|

***

