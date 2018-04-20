## AREAALDATA.doorvaartmaat_p

*Feature dataset: Functioneel*

* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __SHAPE:__ Punt
* __Definitie:__ Aanduiding van Doorvaarthoogte bij bijv. Kunstwerken

***

|KOLOM                               |TYPE                  |DEFINITIE|
|------                              |----                  |-----    |
|OBJECTID                            |OID(38,0,0)           |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None|
|GLOBALID                            |GlobalID(38,0,0)      |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None|
|AD_ID                               |String(255,0,0)       |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None|
|GISIB_ID                            |Integer(0,10,0)       |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)       |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|OBJECTBEGINTIJD                     |Date(8,0,0)           |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)           |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|OBJECTNAAM                          |String(255,0,0)       |PNH; Object naam; Nullable: True; Default: None|
|DOORVAARTHOOGTEAFG                  |String(255,0,0)       |PNH; Peilschaal aflezen van de werkelijke waterstand van NAP + 0; Nullable: True; Default: None |
|GEMEENTE                            |String(255,0,0)       |PNH; Gemeente naam; keuzelijst [GEMEENTE]; Nullable: True; Default: None|
|OMSCHRIJVING                        |String(255,0,0)       |PNH; Extra toelichting; Nullable: True; Default: None|
|VOLGNUMMER                          |SmallInteger(0,10,0)  |PNH; Volgnummer; Nullable: False|
|OPMERKING                           |String(3000,0,0)      |PNH; extra opmerking Nullable: True; Default: None|
|BEHEEROBJECT                        |String(255,0,0)       |PNH; FK naar kunstwerkVast_p; Nullable: True; Default: None|
|CREATED_USER                        |String(255,0,0)       |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)           |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)        |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)           |PNH; Datum van de laatste mutatie; Nullable: True|
|SHAPE                               |Geometry              |PNH; Punt|
|VAARWEG                             |String(255,0,0)       |PNH; FK naar vaarweg_l; Nullable: True; Default: None|
|DATALEVERANCIER                     |String(255,0,0)       |PNH; Leverancier van de data; Nullable: True; Default: None|

***


