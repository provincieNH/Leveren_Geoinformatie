## AREAALDATA.recreatieplek_v

*Feature dataset: Functioneel*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt
* __SHAPE:__ Vlak
* __Definitie:__ Terrein ingericht voor recreatief medegebruik

***

|KOLOM                               |TYPE                |DEFINITIE|
|-----;                              |---;                |----;    |
|OBJECTID                            |OID(38,0,0)         |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:Yes|
|GLOBALID                            |GlobalID(38,0,0)    |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:No|
|AD_ID                               |String(255,0,0)     |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None; Visible:Yes|
|GISIB_ID                            |Integer(0,10,0)     |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|VERWERKINGSSTATUS                   |String(255,0,0)     |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible:Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)         |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True; Visible:Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)         |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True; Visible:Yes|
|BEHEERDER                           |String(255,0,0)     |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible:Yes|
|ONDERHOUDER                         |String(255,0,0)     |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible:No|
|EIGENAAR                            |String(255,0,0)     |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible:No|
|TYPESPEC                            |String(255,0,0)     |PNH; Nadere typering van het object; keuzelijst [typeSpecREC]; Nullable: True; Default: None; Visible:Yes|
|AANLEGJAAR                          |SmallInteger(0,4,0) |PNH; Aanlegjaar; Nullable: True; Visible:No|
|FOTO                                |String(255,0,0)     |PNH; Verwijzing naar Foto; Nullable: True; Default: None; Visible:No|
|OPMERKING                           |String(3000,0,0)    |PNH; Extra toelichting; Nullable: True; Default: None; Visible:No|
|OMSCHRIJVING                        |String(255,0,0)     |PNH; Extra toelichting; Nullable: True; Default: None; Visible:Yes|
|DATALEVERANCIER                     |String(255,0,0)     |PNH; Leverancier van de data; Nullable: True; Default: None; Visible:No|
|CREATED_USER                        |String(255,0,0)     |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None; Visible:No|
|CREATED_DATE                        |Date(8,0,0)         |PNH; Aanmaakdatum; Nullable: True; Visible:No|
|LAST_EDITED_USER                    |String(50,0,0)      |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None; Visible:No|
|LAST_EDITED_DATE                    |Date(8,0,0)         |PNH; Datum van de laatste mutatie; Nullable: True; Visible:No|
|SHAPE                               |Geometry            |PNH; Vlak; Visible:Yes|
|SHAPE_Length                        |Double(0,0,0)       |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None; Visible:Yes|
|SHAPE_Area                          |Double(0,0,0)       |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None; Visible:Yes|
|GEBIEDSCONTRACTREGIO                |String(255,0,0)     |PNH; FK naar gebiedscontractregio_v; Nullable: True; Default: None|


***
