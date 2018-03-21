## AREAALDATA.onderdeel_tbl

$ Feature dataset: -

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt
* __Geometrie:__ Geen
* __Definitie:__ Component bij een mast, zoals een voorschakelapparaat, drukknop,rateltikker, windmeter, gms onderdeel


***

|KOLOM                               |TYPE                   |DEFINITIE|
|------                              |----                   |-----    |
|VERWERKINGSSTATUS                   |String(255,0,0)        |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|DATUMPLAATSING                      |Date(8,0,0)            |PNH; Datum plaatsing installatie; Nullable: True|
|INSTALLATIENUMMER                   |SmallInteger(0,10,0)   |PNH; Bestaande uit 4 cijfers: de eerste drie het nummerdeel van het wegnummer (N201 -> 201), de laatste een volgnummer van één positie (1 t/m 9); Nullable: True|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)   |PNH; TODO; Nullable: True|
|PLANJAAR                            |SmallInteger(0,10,0)   |PNH; TODO; Nullable: True|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0)   |PNH; Restlevensduur; Nullable: True; Default: None|
|IDENTIFICATIE                       |String(255,0,0)        |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None|
|OBJECTID                            |OID(38,0,0)            |PNH; Interne ID ArcGIS; Nullable: False|
|GLOBALID                            |GlobalID(38,0,0)       |PNH; Global Unique Identifier; Nullable: False|
|GISIB_ID                            |Integer(0,10,0)        |PNH; ID beheer openbare ruimte (GISIB); Nullable: True|
|AD_ID                               |String(255,0,0)        |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; Nullable: False; Default: None|
|OBJECTBEGINTIJD                     |Date(8,0,0)            |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)            |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|CREATED_USER                        |String(255,0,0)        |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)            |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)         |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)            |PNH; Datum van de laatste mutatie; Nullable: True|
|BEHEERDER                           |String(255,0,0)        |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None|
|ONDERHOUDER                         |String(255,0,0)        |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None|
|EIGENAAR                            |String(255,0,0)        |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None|
|DATALEVERANCIER                     |String(255,0,0)        |PNH; Leverancier van de data; Nullable: True; Default: None|
|TYPESPEC                            |String(255,0,0)        |PNH; Nadere typering van het object; keuzelijst [typeSpecOND]; Nullable: True; Default: None|
|DIMBAAR                             |String(255,0,0)        |PNH; Voorschakelapparaat: Bevat het voorschakelapparaat een dimvoorziening; Nullable: True; Default: None|
|FABRIKANTTYPECODE                   |String(255,0,0)        |PNH; Fabrikanttypecode; keuzelijst [FABRIKANT_TYPECODE]; Nullable: True; Default: None|
|MAST                                |String(255,0,0)        |PNH; FK naar mastDraagconstructie_p; Nullable: True; Default: None|



***

