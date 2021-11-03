## AREAALDATA.sensor_l

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ BGT/PNH
* __Positionele nauwkeurigheid:__ 15 cm 
* __Geometrie:__ Lijn
* __Definitie:__ Een fysiek detectiesysteem bestaande uit wikkelingen (lussen) in het wegdek bijvoorbeeld voor het beïnvloeden van de regeling van verkeerslichten of een virtueel detectieveld van een videodetector of radardetector, gebruikt voor het beïnvloeden van regelingen van verkeerslichten ![Lus](c:\git\bu_geodata_beheer_43d4\gereedschap\documentatie\areaaldata_datamodel\4.3d4\Objectbladen\04_Ovl_Vri\lus_1.png)
* __Mapping_BGT:__ sensor_l
* __Mapping_Gisib:__ Lus
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__(oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                          	 |----                    |-----    |
|OBJECTID                            |OID(38,0,0)             |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)        |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |TEXT(255,0,0)           |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)            |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)           |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|HUIDIGESTATUS                       |TEXT(50,0,0)            |PNH; Huidige status; keuzelijst [ConditionOfFacilityValue]; Nullable: False; Default: functional; Visible: No|
|OPMERKING                           |TEXT(255,0,0)           |PNH; Toevoeging van subjectieve informatie met betrekking tot opmerkelijke waarnemingen; ; Nullable: True; Default: None; Visible: No|
|OBJECTBEGINTIJD                     |DATE(8,0,0)             |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)             |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING              |SHORT(0,5,0)            |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                           |TEXT(255,0,0)           |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)           |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |TEXT(255,0,0)           |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |TEXT(255,0,0)           |PNH; Nadere typering van het object; keuzelijst [typeSpecSNSLijn]; Nullable: True; Default: None; Visible: Yes|
|BGTPLUSTYPE                         |TEXT(50,0,0)            |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeSNSLijn]; Nullable: False; Default: None; Visible: No|
|AANTALWINDINGEN                     |SHORT(0,5,0)            |PNH; Aantal windingen; ; Nullable: True; Default: None; Visible: Yes|
|DATUMPLAATSING                      |DATE(8,0,0)             |PNH; Datum plaatsing; ; Nullable: True; Default: None; Visible: No|
|DETECTIENUMMER                      |TEXT(255,0,0)           |PNH; Detectie nummer. Bestaat over het algemeen uit een hoofdletter, gevolgd door een cijfer (combinatie) met eventueel een decimaal die als punt wordt weergegeven. Voorbeeld: D2.1 of DM1; ; Nullable: True; Default: None; Visible: Yes|
|AFMETING                            |TEXT(255,0,0)           |PNH; Afmeting van sensor in meter afgerond op halve meters. Grootste getal altijd als eerst vermeld en decimalen met een punt weergegeven. Voorbeeld: 5x2.5; ; Nullable: True; Default: None; Visible: No|
|ELEKTRICITEITSKABEL                 |TEXT(255,0,0)           |PNH; Verwijzende sleutel naar electriciteitskabel_l (simpel); ; Nullable: True; Default: None; Visible: No|
|INNETWERK                           |TEXT(255,0,0)           |PNH; Verwijzende sleutel naar utiliteitsNet_tbl (simpel); ; Nullable: True; Default: None; Visible: Yes|
|EISVOORZORGSMAATRBUFFER             |LONG(0,10,0)            |PNH; Wanneer de asset een verhoogd risico/impact op/bij graafschade heeft, kan hier een veiligheidsbuffer in meters worden opgegeven. Wanneer aan de algemene EV-voorwaarden is voldaan en er binnen deze buffer gegraven wordt, ontvangt de grondroerder een eisvoorzorgsmaatregelbrief. Zonder opgaaf gelden algemene uitgangspunten en voorgedefinieerde bufferafstand. Bij een negatieve waarde, als -1, wordt geen brief uitgestuurd; ; Nullable: True; Default: None; Visible: No|
|IMKL_INNETWORK                      |TEXT(255,0,0)           |PNH; Provincie aanduiding voor het type net, VB: VRI of OVL; keuzelijst [IMKL_InNetwork]; Nullable: False; Default: VRI; Visible: Yes|
|DATALEVERANCIER                     |TEXT(255,0,0)           |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |TEXT(255,0,0)           |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)             |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)            |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)             |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry(0,0,0)         |PNH; Lijn; ; Nullable: False; Default: None; Visible: Yes|
|SHAPE_Length                        |DOUBLE(0,0,0)           |PNH; Lengte in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|LENGTE                              |DOUBLE(0,0,0)           |PNH; Lengte in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|


***
