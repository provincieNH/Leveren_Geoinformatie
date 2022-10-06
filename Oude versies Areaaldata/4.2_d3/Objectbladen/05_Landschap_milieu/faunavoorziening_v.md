## AREAALDATA.faunavoorziening_v

*Feature dataset: Functioneel*


* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Vlak
* __Definitie:__ Een faunavoorziening is een voorziening die het passeren door dieren van infrastructuur geleidt, bevordert of juist voorkomt (bron: Leidraad Faunavoorzieningen bij Infrastructuur).
[Leidraad faunavoorzieningen](https://www.mjpo.nl/downloads/203/leidraad-2013-hoofddocument[1].pdf)
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ Fauna voorziening
* __Mapping_NTA8035:__ bs:SpatialRegion

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                    |-----    |
|OBJECTID                            |OID(38,0,0)             |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)        |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |String(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |Integer(0,10,0)         |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |String(255,0,0)         |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)             |PNH; Datum waarop het object voor het eerst volgens het areaaldata datamodel wordt vastgelegd ; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|BEHEERDER                           |String(255,0,0)         |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |String(255,0,0)         |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |String(255,0,0)         |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |String(255,0,0)         |PNH; Nadere typering van het object; keuzelijst [typeSpecFNV]; Nullable: True; Default: None; Visible: Yes|
|FAUNASOORT                          |String(255,0,0)         |PNH; Doelsoorten; ; Nullable: True; Default: None; Visible: Yes|
|FAUNADOELGROEP                      |String(255,0,0)         |PNH; Faunadoelgroep; keuzelijst [FAUNA_DOELGROEP]; Nullable: True; Default: None; Visible: No|
|AANLEGJAAR                          |SmallInteger(0,5,0)     |PNH; Aanlegjaar; ; Nullable: True; Default: None; Visible: No|
|JAAR_PLAATSING_AANLEG_GESCHAT       |String(1,0,0)           |PNH; Jaar plaatsing of aanleg is geschat: Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|FOTO                                |String(255,0,0)         |PNH; Verwijzing naar Foto; ; Nullable: True; Default: None; Visible: No|
|HECTOMETER                          |String(255,0,0)         |PNH; Aanduiding Hectometrering; ; Nullable: True; Default: None; Visible: Yes|
|LEVENSVERWACHTING                   |SmallInteger(0,5,0)     |PNH; Levensverwachting; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |String(255,0,0)         |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|PLANJAAR                            |SmallInteger(0,5,0)     |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|RESTLEVENSDUUR                      |SmallInteger(0,5,0)     |PNH; Restlevensduur; ; Nullable: True; Default: None; Visible: No|
|ZIJDE                               |String(255,0,0)         |PNH; Zijde; keuzelijst [ZIJDE]; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |String(255,0,0)         |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |String(255,0,0)         |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)             |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)          |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)             |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry                |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                        |Double(0,0,0)           |PNH; Omtrek in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|SHAPE_Area                          |Double(0,0,0)           |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|OMTREK                              |Double(0,0,0)           |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|
|OPPERVLAKTE                         |Double(0,0,0)           |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Area; ; Nullable: False; Default: None; Visible: Yes|
|XCOORDINAAT                         |Integer(0,10,0)         |PNH; X coördinaten (Rijksdriehoekstelsel). Dit wordt automatisch gevuld; ; Nullable: False; Default: None; Visible: Yes|
|YCOORDINAAT                         |Integer(0,10,0)         |PNH; Y coördinaten (Rijksdriehoekstelsel). Dit wordt automatisch gevuld; ; Nullable: False; Default: None; Visible: Yes|
|TRAJECT                             |String(255,0,0)         |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM]; Nullable: True; Default: None; Visible: Yes|

### Illustratie decompositie faunavoorzienning:


 |__Naam__ | __Illustratie__ |
 |-----------------------------------------|----|
 |faunavoorziening_decompositie |[faunavoorziening_decompositie ](D:\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.2d3\Objectbladen\00_Illustraties\illustraties_Landschap_milieu\faunavoorziening_decompositie.png)
 |
***
