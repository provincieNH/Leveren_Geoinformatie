## AREAALDATA.onderdeel_tbl

$ Feature dataset: -

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt
* __Geometrie:__ Geen
* __Definitie:__ Component bij een mast, zoals een voorschakelapparaat, drukknop,rateltikker, windmeter, gms onderdeel


***

|KOLOM                               |TYPE                |DEFINITIE|
|------                              |----                |-----    |
|VERWERKINGSSTATUS                   |String(255,0,0)     |Status van de gegevens, keuzelijst [VERWERKINGSSTATUS] - Nullable: False Default: Nieuwl|
|DATUMPLAATSING                      |Date(8,0,0)         |Datum plaatsing installatie - Nullable: True|
|OMSCHRIJVING                        |String(255,0,0)     |Extra toelichting - Nullable: True Default: None|
|INSTALLATIENUMMER                   |SmallInteger(0,10,0)|Bestaande uit 4 cijfers: de eerste drie het nummerdeel van het wegnummer (N201 -> 201), de laatste een volgnummer van één positie (1 t/m 9) - Nullable: True|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)|TODO - Nullable: True|
|PLANJAAR                            |SmallInteger(0,10,0)|TODO - Nullable: True|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0)|Restlevensduur - Nullable: True Default: None|
|KRUISPUNT                           |String(255,0,0)     |FK naar kruispunt_p - Nullable: True Default: None|
|TRAJECT                             |String(255,0,0)     |FK naar traject_v - Nullable: True Default: None|
|WEG                                 |String(255,0,0)     |FK naar weg_l - Nullable: True Default: None|
|IDENTIFICATIE                       |String(255,0,0)      |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|OBJECTID                            |OID(38,0,0)        |Interne ID ArcGIS - Nullable: False|
|GLOBALID                            |GlobalID(38,0,0)   |Global Unique Identifier - Nullable: False|
|GISIB_ID                            |Integer(0,10,0)    |ID beheer openbare ruimte (GISIB) - Nullable: True|
|AD_ID                               |String(255,0,0)    |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]' - Nullable: False Default: None|
|OBJECTBEGINTIJD                     |Date(8,0,0)        |Datum waarop het object bij de bronhouder is ontstaan - Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)        |Datum waarop het object bij de bronhouder niet meer geldig is - Nullable: True|
|CREATED_USER                        |String(255,0,0)    |Naam van gebruiker die de rij heeft aangemaakt - Nullable: True Default: None|
|CREATED_DATE                        |Date(8,0,0)        |Aanmaakdatum - Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)     |Naam van gebruiker die de laatste mutatie heeft doorgevoerd - Nullable: True Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)        |Datum van de laatste mutatie - Nullable: True|
|BEHEERDER                           |String(255,0,0)    |Beheerder van het object, keuzelijst [BEHEERDER] - Nullable: True Default: None|
|ONDERHOUDER                         |String(255,0,0)    |Onderhouder van het object, keuzelijst [ONDERHOUDER] - Nullable: True Default: None|
|EIGENAAR                            |String(255,0,0)    |Eigenaar van het object, keuzelijst [INSTANTIE] - Nullable: True Default: None| 
|DATALEVERANCIER                     |String(255,0,0)    |Leverancier van de data - Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)     |Nadere typering van het object, keuzelijst [typeSpecOND] - Nullable: True Default: None|
|AANSLUITSPANNING                    |String(255,0,0)     |Rateltikker: Bijvoorbeeld 40V of 220 V (is gerelateerd aan de lamp-spanning)- Nullable: True Default: None|
|DATUMGARANTIE                       |Date(8,0,0)         |Datum garantie - Nullable: True|
|DIMBAAR                             |String(255,0,0)     |Voorschakelapparaat: Bevat het voorschakelapparaat een dimvoorziening - Nullable: True Default: None|
|WACHTTIJDVOORSPELL                  |String(255,0,0)     |Drukknop: Visualiseert de wachttijd voor een verkeerslicht (met name voor voetgangers en fietsers), meestal ondergebracht in drukknop of verkeerslicht - Nullable: True Default: None|
|WINDMETERHOOGTE                     |Integer(0,10,0)     |Windmeter: Hoogte waarop de windmeter geplaatst (m) - Nullable: True|
|FABRIKANTTYPECODE                   |String(255,0,0)     |Fabrikanttypecode, keuzelijst [FABRIKANT_TYPECODE] - Nullable: True Default: None|
|MAST                                |Guid(38,0,0         |FK naar mastDraagconstructie_p - Nullable: True|



***

