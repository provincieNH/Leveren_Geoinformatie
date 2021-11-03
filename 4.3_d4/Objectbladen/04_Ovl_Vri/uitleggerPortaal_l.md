## AREAALDATA.uitleggerPortaal_l

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Lijn
* __Definitie:__ Uitlegger/Portaal is het lijnvormige element van een uitlegger of portaal. In het geval van een uitlegger bestaat het totaal uit 1 mast (object in paalDraagconstructie_p) en een object in uitleggerPortaal_l. In het geval van een portaal bestaat het geheel uit 2 masten (objecten in paalDraagconstructie_p) en een object in uitleggerPortaal_l. Aan een uitleggePortaal kunnen vervolgens lantaarns of armaturen gekoppeld zijn.

![Portaal](c:\git\bu_geodata_beheer_43d4\gereedschap\documentatie\areaaldata_datamodel\4.3d4\Objectbladen\04_Ovl_Vri\portaal_uithouder.png)
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ Uitlegger portaal
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                     |-----    |
|OBJECTID                            |OID(38,0,0)              |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)         |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |TEXT(255,0,0)            |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)             |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)            |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |DATE(8,0,0)              |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)              |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING              |SHORT(0,5,0)             |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                           |TEXT(255,0,0)            |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)            |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |TEXT(255,0,0)            |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |TEXT(255,0,0)            |PNH; Nadere typering van het object, 'Uitlegger' of 'Portaal'; keuzelijst [typeSpecUIP]; Nullable: True; Default: None; Visible: Yes|
|DATUMPLAATSING                      |DATE(8,0,0)              |PNH; Datum plaatsing; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |TEXT(255,0,0)            |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|LENGTE                              |FLOAT(0,10,1)            |PNH; Lengte in meters met 1 decimaal; ; Nullable: True; Default: None; Visible: Yes|
|LEVENSVERWACHTING                   |SHORT(0,5,0)             |PNH; Levensverwachting; ; Nullable: True; Default: None; Visible: No|
|PLANJAAR                            |SHORT(0,5,0)             |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|TRAJECT                             |TEXT(255,0,0)            |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM]; Nullable: True; Default: None; Visible: Yes|
|PAAL                                |TEXT(255,0,0)            |PNH; Verwijzende sleutel naar paalDraagconstructie_p (simpel); ; Nullable: True; Default: None; Visible: Yes|
|PAAL2                               |TEXT(255,0,0)            |PNH; Tweede verwijzende sleutel paalDraagconstructie_p, alleen in geval van TYPESPEC Portaal; ; Nullable: True; Default: None; Visible: Yes|
|INNETWERK                           |TEXT(255,0,0)          |PNH; Verwijzende sleutel naar utiliteitsNet_tbl (simpel); ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |TEXT(255,0,0)            |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |TEXT(255,0,0)            |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)              |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)             |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)              |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry                 |PNH; Lijn; ; Nullable: False; Default: None; Visible: Yes|
|SHAPE_Length                        |DOUBLE(0,0,0)            |PNH; Lengte in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|


***

