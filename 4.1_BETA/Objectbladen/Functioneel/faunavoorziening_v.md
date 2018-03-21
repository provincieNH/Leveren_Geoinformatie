## AREAALDATA.faunavoorziening_v

$ Feature dataset: Functioneel

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt
* __SHAPE:__ Vlak
* __Definitie:__ Een faunavoorziening is een voorziening die het passeren door dieren van infrastructuur geleidt, bevordert of juist voorkomt (bron: Leidraad Faunavoorzieningen bij Infrastructuur).
[Leidraad faunavoorzieningen](http://www.mjpo.nl/publicaties/leidraad_faunavoorzieningen_bij_infrastructuur/?page=leidraad)


***

|KOLOM                               |TYPE                    |DEFINITIE|
|------                              |----                    |-----    |
|OBJECTID                            |OID(38,0,0)             |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None|
|GLOBALID                            |GlobalID(38,0,0)        |PNH; Global Unique Identifier,  aangemaakt door ArcGIS.; Nullable: False; Default: None|
|AD_ID                               |String(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer.; Nullable: False; Default: None|
|GISIB_ID                            |Integer(0,10,0)         |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer.; Nullable: True; Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)         |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|OBJECTBEGINTIJD                     |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|BEHEERDER                           |String(255,0,0)         |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None|
|ONDERHOUDER                         |String(255,0,0)         |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None|
|EIGENAAR                            |String(255,0,0)         |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None|
|TYPESPEC                            |String(255,0,0)         |PNH; Nadere typering van het object; keuzelijst [typeSpecFNV]; Nullable: True; Default: None|
|FAUNASOORT                          |String(255,0,0)         |PNH; Doelsoorten; Nullable: True; Default: None|
|FAUNADOELGROEP                      |String(255,0,0)         |PNH; Faunadoelgroep; keuzelijst [FAUNA_DOELGROEP]; Nullable: True; Default: None|
|AANLEGJAAR                          |SmallInteger(0,10,0)    |PNH; Aanlegjaar; Nullable: True|
|JAAR_PLAATSING_AANLEG_GESCHAT       |String(1,0,0)           |PNH; Jaar plaatsing of aanleg is geschat: Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N|
|OMSCHRIJVING                        |String(255,0,0)         |PNH; Extra toelichting; Nullable: True; Default: None|
|FOTO                                |String(255,0,0)         |PNH; Verwijzing naar Foto; Nullable: True; Default: None|
|HECTOMETER                          |String(255,0,0)         |PNH; Aanduiding Hectometrering; Nullable: True; Default: None|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)    |PNH; Levensverwachting; Nullable: True|
|OPMERKING                           |String(3000,0,0)        |PNH; Extra toelichting; Nullable: True; Default: None|
|PLANJAAR                            |SmallInteger(0,10,0)    |PNH; Het geplande jaar dat het object vervangen wordt; Nullable: True; Default: None|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0)    |PNH; Restlevensduur; Nullable: True|
|ZIJDE                               |String(255,0,0)         |PNH; Zijde; keuzelijst [ZIJDE]; Nullable: True; Default: None|
|DATALEVERANCIER                     |String(255,0,0)         |PNH; Leverancier van de data; Nullable: True; Default: None|
|CREATED_USER                        |String(255,0,0)         |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)             |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)          |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)             |PNH; Datum van de laatste mutatie; Nullable: True|
|SHAPE                               |Geometry                |PNH; Vlak|
|SHAPE_Length                        |Double(0,0,0)           |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None|
|SHAPE_Area                          |Double(0,0,0)           |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None|
|TRAJECT                             |String(255,0,0)         |PNH; FK naar traject_v; Nullable: True; Default: None|

***