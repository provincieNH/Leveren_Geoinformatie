﻿## AREAALDATA.diepteTovMaaiveld_p

$ Feature dataset: Functioneel


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL (2015)
* __Positionele nauwkeurigheid:__ n.v.t.
* __SHAPE:__ Punt
* __Definitie:__ Diepte bevat informatie over de dieptelegging van netwerkelementen. Het is een uitvoerige beschrijving die diepte tov het lokale maaiveld beschrijft. (Bron: IMKL 2015):

***

|KOLOM                               |TYPE                |DEFINITIE|
|------                              |----                |-----    |
|OBJECTID                            |OID(38,0,0)         |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None|
|GLOBALID                            |GlobalID(38,0,0)    |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None|
|AD_ID                               |String(255,0,0)     |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None|
|GISIB_ID                            |Integer(0,10,0)     |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None|
|IDENTIFICATIE                       |String(255,0,0)     |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)     |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|OBJECTBEGINTIJD                     |Date(8,0,0)         |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True; Default: None|
|OBJECTEINDTIJD                      |Date(8,0,0)         |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True; Default: None|
|DIEPTENAUWKEURIGHEID                |String(50,0,0)      |PNH; Nauwkeurigheidsklasse waarmee de diepte is opgenomen; keuzelijst [NauwkeurigheidDiepteValue]; Nullable: True; Default: None|
|DIEPTEPEIL                          |Float(0,10,2)       |PNH; Afstand vanaf de referentie tot aan de bovenkant van een object; Nullable: True; Default: None|
|DATUMOPMETINGDIEPTEPEIL             |Date(8,0,0)         |PNH; Datum waarop dieptepeil opgenomen is; Nullable: True; Default: None|
|DIEPTEAANGRIJPINGSPUNT              |String(50,0,0)      |PNH; Aangrijpingspunt van het element dat geldt als punt van meting; keuzelijst [DiepteAangrijpingspuntValue]; Nullable: True; Default: bovenkant|
|DATALEVERANCIER                     |String(255,0,0)     |PNH; Leverancier van de data; Nullable: True; Default: None|
|CREATED_USER                        |String(255,0,0)     |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)         |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)      |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)         |PNH; Datum van de laatste mutatie; Nullable: True|
|SHAPE                               |Geometry            |PNH; Punt|



***