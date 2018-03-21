## AREAALDATA.ligplaatsstrook_v

$ Feature dataset: Functioneel


* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt
* __SHAPE:__ Vlak
* __Definitie:__ Een Ligplaatsstrook is een gebied waar ligplaatsen toegestaan zijn

***

|KOLOM                               |TYPE                 |DEFINITIE|
|------                              |----                 |-----    |
|OBJECTID                            |OID(38,0,0)          |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None|
|GLOBALID                            |GlobalID(38,0,0)     |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None|
|AD_ID                               |String(255,0,0)      |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False;Default: None|
|GISIB_ID                            |Integer(0,10,0)      |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)      |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|OBJECTBEGINTIJD                     |Date(8,0,0)          |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)          |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|BEHEERDER                           |String(255,0,0)      |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None|
|ONDERHOUDER                         |String(255,0,0)      |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None|
|EIGENAAR                            |String(255,0,0)      |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None|
|ZIJDE                               |String(255,0,0)      |PNH; Zijde; keuzelijst [ZIJDE]; Nullable: True; Default: None|
|CULTUURHISTORISCHE                  |String(255,0,0)      |PNH; Cultuur Historische Waarde; Nullable: True; Default: None|
|GEMIDDELDEBREEDTE                   |Float(0,25,10)       |PNH; Gemiddelde Breedte; Nullable: True|
|HMBEGIN                             |Float(0,25,10)       |PNH; Begin Hectometrering van Ligplaatsstrook; Nullable: True|
|HMEIND                              |Float(0,25,10)       |PNH; Eind Hectometrering van Ligplaatsstrook; Nullable: True|
|LENGTE                              |Float(0,10,0)        |PNH; Lengte Ligplaatsstrook in meter; Nullable: True|
|LIGPLAATSSTROOKLIN                  |Float(0,25,10)       |PNH; Ligplaatsstrook Linker Oever; Nullable: True|
|LIGPLAATSSTROOKREC                  |Float(0,25,10)       |PNH; Ligplaatsstrook Rechter Oever; Nullable: True|
|OPMERKING                           |String(3000,0,0)     |PNH; Extra toelichting; Nullable: True; Default: None|
|RESTRUIMTE                          |Float(0,25,10)       |PNH; Beschikbare ruimte in nautisch profiel; Nullable: True|
|DATALEVERANCIER                     |String(255,0,0)      |PNH; Leverancier van de data; Nullable: True; Default: None|
|CREATED_USER                        |String(255,0,0)      |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)          |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)       |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)          |PNH; Datum van de laatste mutatie; Nullable: True|
|SHAPE                               |Geometry             |PNH; Vlak|
|SHAPE_Length                        |Double(0,0,0)        |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld. ; Nullable: False; Default: None|
|SHAPE_Area                          |Double(0,0,0)        |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld.; Nullable: False; Default: None|
|ECOLOGISCHEHOOFDST                  |String(255,0,0)      |PNH; FK naar ecoHoofdstructuur_v; Nullable: True; Default: None|
|ECOLOGISCHEVERBIND                  |String(255,0,0)      |PNH; FK naar ecoVerbZone_v; Nullable: True; Default: None|
|VAARWEGDEELTRAJECT                  |String(255,0,0)      |PNH; FK naar vaarwegdeeltraject_v; Nullable: True; Default: None|

***
