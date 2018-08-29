## AREAALDATA.onderdeel_tbl

*Feature dataset: -*

* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt
* __Geometrie:__ Geen
* __Definitie:__ Component bij een mast, zoals een voorschakelapparaat, drukknop,rateltikker, windmeter, gms onderdeel


***

|KOLOM                               |TYPE                   |DEFINITIE|
|------                              |----                   |-----    |
|VERWERKINGSSTATUS                   |String(255,0,0)        |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible:Yes|
|DATUMPLAATSING                      |Date(8,0,0)            |PNH; Datum plaatsing installatie; Nullable: True; Visible:No|
|INSTALLATIENUMMER                   |SmallInteger(0,10,0)   |PNH; Bestaande uit 4 cijfers: de eerste drie het nummerdeel van het wegnummer (N201 -> 201), de laatste een volgnummer van één positie (1 t/m 9); Nullable: True; Visible:Yes|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)   |PNH; TODO; Nullable: True; Visible:No|
|PLANJAAR                            |SmallInteger(0,10,0)   |PNH; TODO; Nullable: True; Visible:No|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0)   |PNH; Restlevensduur; Nullable: True; Default: None; Visible:No|
|IDENTIFICATIE                       |String(255,0,0)        |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None; Visible:No|
|OBJECTID                            |OID(38,0,0)            |PNH; Interne ID ArcGIS; Nullable: False; Visible:Yes|
|GLOBALID                            |GlobalID(38,0,0)       |PNH; Global Unique Identifier; Nullable: False; Visible:No|
|GISIB_ID                            |Integer(0,10,0)        |PNH; ID beheer openbare ruimte (GISIB); Nullable: True; Visible:No|
|AD_ID                               |String(255,0,0)        |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; Nullable: False; Default: None; Visible:Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)            |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True; Visible:Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)            |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True; Visible:Yes|
|CREATED_USER                        |String(255,0,0)        |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None; Visible:No|
|CREATED_DATE                        |Date(8,0,0)            |PNH; Aanmaakdatum; Nullable: True; Visible:No|
|LAST_EDITED_USER                    |String(50,0,0)         |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None; Visible:No|
|LAST_EDITED_DATE                    |Date(8,0,0)            |PNH; Datum van de laatste mutatie; Nullable: True; Visible:No|
|BEHEERDER                           |String(255,0,0)        |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible:Yes|
|ONDERHOUDER                         |String(255,0,0)        |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible:No|
|EIGENAAR                            |String(255,0,0)        |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible:No|
|DATALEVERANCIER                     |String(255,0,0)        |PNH; Leverancier van de data; Nullable: True; Default: None; Visible:No|
|TYPESPEC                            |String(255,0,0)        |PNH; Nadere typering van het object; keuzelijst [typeSpecOND]; Nullable: True; Default: None; Visible:Yes|
|DIMBAAR                             |String(255,0,0)        |PNH; Voorschakelapparaat: Bevat het voorschakelapparaat een dimvoorziening; Nullable: True; Default: None; Visible:No|
|FABRIKANTTYPECODE                   |String(255,0,0)        |PNH; Fabrikanttypecode; keuzelijst [FABRIKANT_TYPECODE]; Nullable: True; Default: None; Visible:Yes|
|MAST                                |String(255,0,0)        |PNH; FK naar mastDraagconstructie_p; Nullable: True; Default: None; Visible:No|



***

