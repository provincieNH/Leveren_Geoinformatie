## AREAALDATA.faunavoorziening_v

*Feature dataset: Functioneel*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt
* __SHAPE:__ Vlak
* __Definitie:__ Een faunavoorziening is een voorziening die het passeren door dieren van infrastructuur geleidt, bevordert of juist voorkomt (bron: Leidraad Faunavoorzieningen bij Infrastructuur).
[Leidraad faunavoorzieningen](http://www.mjpo.nl/publicaties/leidraad_faunavoorzieningen_bij_infrastructuur/?page=leidraad)


***

|KOLOM                               |TYPE (length, precision, scale)                    |DEFINITIE (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                    |-----    |
|OBJECTID                            |OID(38,0,0)             |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)        |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |String(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |Integer(0,10,0)         |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |String(255,0,0)         |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|BEHEERDER                           |String(255,0,0)         |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |String(255,0,0)         |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |String(255,0,0)         |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |String(255,0,0)         |PNH; Nadere typering van het object; keuzelijst [typeSpecFNV]; Nullable: True; Default: None; Visible: Yes|
|FAUNASOORT                          |String(255,0,0)         |PNH; Doelsoorten; ; Nullable: True; Default: None; Visible: Yes|
|FAUNADOELGROEP                      |String(255,0,0)         |PNH; Faunadoelgroep; keuzelijst [FAUNA_DOELGROEP]; Nullable: True; Default: None; Visible: No|
|AANLEGJAAR                          |SmallInteger(0,10,0)    |PNH; Aanlegjaar; ; Nullable: True; Default: None; Visible: No|
|JAAR_PLAATSING_AANLEG_GESCHAT       |String(1,0,0)           |PNH; Jaar plaatsing of aanleg is geschat: Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|OMSCHRIJVING                        |String(255,0,0)         |PNH; Extra toelichting; ; Nullable: True; Default: None; Visible: Yes|
|FOTO                                |String(255,0,0)         |PNH; Verwijzing naar Foto; ; Nullable: True; Default: None; Visible: No|
|HECTOMETER                          |String(255,0,0)         |PNH; Aanduiding Hectometrering; ; Nullable: True; Default: None; Visible: Yes|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)    |PNH; Levensverwachting; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |String(3000,0,0)        |PNH; Extra toelichting; ; Nullable: True; Default: None; Visible: No|
|PLANJAAR                            |SmallInteger(0,10,0)    |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0)    |PNH; Restlevensduur; ; Nullable: True; Default: None; Visible: No|
|ZIJDE                               |String(255,0,0)         |PNH; Zijde; keuzelijst [ZIJDE]; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |String(255,0,0)         |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |String(255,0,0)         |PNH; Naam van gebruiker die de rij heeft aangemaakt; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)             |PNH; Aanmaakdatum; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)          |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)             |PNH; Datum van de laatste mutatie; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry                |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                        |Double(0,0,0)           |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld; ; Nullable: False; Default: None; Visible: Yes|
|SHAPE_Area                          |Double(0,0,0)           |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld; ; Nullable: False; Default: None; Visible: Yes|
|TRAJECT                             |String(255,0,0)         |PNH; FK naar traject_v; keuzelijst [TRAJECT_NAAM] ; Nullable: True; Default: None; Visible: Yes|

***
