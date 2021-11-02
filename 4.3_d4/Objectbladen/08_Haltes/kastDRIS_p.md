## AREAALDATA.kastDRIS_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Kast ten behoeve van de regeling van DRIS panelen
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ DRIS kast
* __Mapping_NTA8035:__ bs:PhysicalObject

***


|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__(oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----          	     |-----    |
|OBJECTID                            |OID(38,0,0)            |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)       |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |TEXT(255,0,0)          |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)           |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)          |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|HUIDIGESTATUS                       |TEXT(50,0,0)           |PNH; Huidige status; keuzelijst [ConditionOfFacilityValue]; Nullable: False; Default: functional; Visible: No|
|OPMERKING                           |TEXT(255,0,0)          |PNH; Toevoeging van subjectieve informatie met betrekking tot opmerkelijke waarnemingen; ; Nullable: True; Default: None; Visible: No|
|OBJECTBEGINTIJD                     |DATE(8,0,0)            |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)            |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING              |SHORT(0,5,0)           |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                           |TEXT(255,0,0)          |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)          |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |TEXT(255,0,0)          |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|VERTICALE_POSITIE                   |LONG(0,10,0)           |PNH; Verticale positie; keuzelijst [VerticalePositie]; Nullable: False; Default: 3; Visible: No|
|TYPESPEC                            |TEXT(255,0,0)          |PNH; Nadere typering van het object; keuzelijst [typeSpecKSTDRIS] ; Nullable: True; Default: None; Visible: Yes|
|BGTPLUSTYPE                         |TEXT(50,0,0)           |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeKST]; Nullable: False; Default: None; Visible: No|
|ZIJDE                               |TEXT(10,0,0)           |PNH; Zijde; keuzelijst [ZIJDE]; Nullable: True; Default: None; Visible: No|
|DATUMGARANTIE                       |DATE(8,0,0)            |PNH; Datum en jaartal tot wanneer de garantie geldig is; ; Nullable: True; Default: None; Visible: No|
|DATUMPLAATSING                      |DATE(8,0,0)            |PNH; Datum plaatsing; ; Nullable: True; Default: None; Visible: No|
|AANTALGROEPEN                       |LONG(0,10,0)           |PNH; Aantal elektriciteitsgroepen aanwezig in de kast; ; Nullable: True; Default: None; Visible: Yes|
|EANEMETER                           |TEXT(255,0,0)          |PNH; De EAN-code vermeld op de meter; ; Nullable: True; Default: None; Visible: No|
|KASTNUMMER                          |TEXT(255,0,0)          |PNH; Kastnummer; ; Nullable: True; Default: None; Visible: Yes|
|LEVENSVERWACHTING                   |SHORT(0,5,0)           |PNH; Levensverwachting; ; Nullable: True; Default: None; Visible: No|
|PLANJAAR                            |SHORT(0,5,0)           |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|VOEDING                             |TEXT(255,0,0)          |PNH; Keuze uit 220V of OV; ; Nullable: True; Default: None; Visible: No|
|TYPECOMMUNICATIE                    |TEXT(30,0,0)           |PNH; Type communicatie; keuzelijst [TYPE_COMMUNICATIE]; Nullable: True; Default: None; Visible: No|
|EISVOORZORGSMAATRBUFFER             |LONG(0,10,0)           |PNH; Wanneer de asset een verhoogd risico op graafschade heeft, kan hier een veiligheidsbuffer in meters worden opgegeven. Wanneer binnen deze buffer gegraven wordt, ontvangt de grondroerder een eisvoorzorgsmaatregelbrief; ; Nullable: True; Default: None; Visible: No|
|IMKL_INNETWORK                      |TEXT(255,0,0)          |PNH; Provincie aanduiding voor het type net, VB: VRI of OVL; keuzelijst [IMKL_InNetwork]; Nullable: False; Default: DRIS; Visible: No|
|DATALEVERANCIER                     |TEXT(255,0,0)          |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|INNETWERK                           |TEXT(255,0,0)          |PNH; Verwijzende sleutel naar utiliteitsNet_tbl (simpel); ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |TEXT(255,0,0)          |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)            |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)           |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)            |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry(0,0,0)        |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|



***
