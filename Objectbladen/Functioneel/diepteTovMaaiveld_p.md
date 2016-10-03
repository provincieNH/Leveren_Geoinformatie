## AREAALDATA.diepteTovMaaiveld_p

$ Feature dataset: Functioneel


* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL (2015)
* __Positionele nauwkeurigheid:__ n.v.t.
* __SHAPE:__ Punt
* __Definitie:__ Diepte bevat informatie over de dieptelegging van netwerkelementen. Het is een uitvoerige beschrijving die diepte tov het lokale maaiveld beschrijft. (Bron: IMKL 2015):

***

|KOLOM                               |TYPE                |DEFINITIE|
|------                              |----                |-----    |
|SHAPE                               |Geometry            |Punt|
|IDENTIFICATIE                       |String(255,0,0)    |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)    |Status van de gegevens, keuzelijst [VERWERKINGSSTATUS] - Nullable: False Default: Nieuwl|
|OBJECTID                            |OID(38,0,0)        |Interne ID ArcGIS - Nullable: False|
|GLOBALID                            |GlobalID(38,0,0)   |Global Unique Identifier - Nullable: False|
|GISIB_ID                            |Integer(0,10,0)    |ID beheer openbare ruimte (GISIB) - Nullable: True|
|AD_ID                               |String(255,0,0)    |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]' - Nullable: False Default: None|
|CREATED_USER                        |String(255,0,0)    |Naam van gebruiker die de rij heeft aangemaakt - Nullable: True Default: None|
|CREATED_DATE                        |Date(8,0,0)        |Aanmaakdatum - Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)     |Naam van gebruiker die de laatste mutatie heeft doorgevoerd - Nullable: True Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)        |Datum van de laatste mutatie - Nullable: True|
|DATALEVERANCIER                     |String(255,0,0)    |Leverancier van de data - Nullable: True Default: None|
|INNETWERK                           |String(255,0,0)    |FK naar utiliteitsNet_tbl - Nullable: True Default: None|
|DIEPTENAUWKEURIGHEID                |String(50,0,0)     |Nauwkeurigheidsklasse waarmee de diepte is opgenomen, keuzelijst [NauwkeurigheidDiepteValue] - Nullable: True Default: None|
|DIEPTEPEIL                          |Float(0,10,2)      |afstand vanaf de referentie tot aan de bovenkant van een object - Nullable: True Default: None|
|DATUMOPMETINGDIEPTEPEIL             |Date(8,0,0)        |Datum waarop dieptepeil opgenomen is - Nullable: True Default: None|
|DIEPTEAANGRIJPINGSPUNT              |String(50,0,0)     |Aangrijpingspunt van het element dat geldt als punt van meting, keuzelijst [DiepteAangrijpingspuntValue] - Nullable: True Default: bovenkant|



***