## AREAALDATA.buis_l

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL1.2.1
* __Positionele nauwkeurigheid:__ 7,5 cm
* __Geometrie:__ Lijn
* __Definitie:__ Holle leiding voor het doorstromen van gassen, vloeistoffen of capsules, bestemd om hetzij gas,
een vloeistof of capsules te transporteren, hetzij een vloeistof als intermediair te gebruiken voor het transport van
warmte of een opgeloste of verpulverde stof. NB. Bij PNH eigenlijk alleen gebruikt voor riolering.
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ Buis
* __Mapping_NTA8035:__ bs:PhysicalObject


***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__(oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                   |-----    |
|OBJECTID                            |OID(38,0,0)            |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)       |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: No|
|AD_ID                               |TEXT(255,0,0)          |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)           |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)          |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |DATE(8,0,0)            |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)            |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|HUIDIGESTATUS                       |TEXT(50,0,0)           |PNH; Huidige status; keuzelijst [ConditionOfFacilityValue]; Nullable: False; Default: functional; Visible: No|
|BEHEERDER                           |TEXT(255,0,0)          |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)          |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |TEXT(255,0,0)          |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: False; Default: None; Visible: Yes|
|TYPESPEC                            |TEXT(255,0,0)          |PNH; Nadere typering van het object; keuzelijst [typeSpecBUI]; Nullable: True; Default: None; Visible: Yes|
|DATUMPLAATSING                      |DATE(8,0,0)            |PNH; Datum aanleg; ; Nullable: True; Default: None; Visible: No|
|DIAMETERMM                          |SHORT(0,5,0)           |PNH; Diameter van de buis in mm, afgerond op hele getallen; ; Nullable: True; Default: None; Visible: Yes|
|OPMERKING                           |TEXT(255,0,0)          |PNH; Toevoeging van subjectieve informatie met betrekking tot opmerkelijke waarnemingen; ; Nullable: True; Default: None; Visible: Yes|
|PLANJAAR                            |SHORT(0,5,0)           |PNH; Het jaar dat nu gepland staat om item te vervangen; ; Nullable: True; Default: None; Visible: No|
|RESTLEVENSDUUR                      |SHORT(0,5,0)           |PNH; Verwachte restlevensduur in jaren vanaf moment van inspectie; ; Nullable: True; Default: None; Visible: No|
|MATERIAALTYPE                       |TEXT(255,0,0)          |PNH; Type materiaal; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None; Visible: Yes|
|IMKL_INNETWORK                      |TEXT(255,0,0)          |PNH; Provincie aanduiding voor het type net, VB: VRI of OVL; keuzelijst [IMKL_InNetwork]; Nullable: False; Default: RIOOL; Visible: Yes|
|INNETWERK                           |TEXT(255,0,0)          |PNH; Verwijzende sleutel naar utiliteitsNet_tbl (simpel); ; Nullable: True; Default: None; Visible: No|
|VERTICALE_POSITIE                   |LONG(0,10,0)           |PNH; Verticale positie; keuzelijst [VerticalePositie]; Nullable: False; Default: 3; Visible: No|
|AFVALWATERTYPE                      |TEXT(255,0,0)          |PNH; Typering afvalwater; keuzelijst [Afvalwatertype]; Nullable: False; Default: gecombineerd; Visible: Yes|
|INDICATIEVELIGGING                  |TEXT(1,0,0)            |PNH; Is de geometrie indicatief ingetekend, ja of nee; keuzelijst [jaNee]; Nullable: false; Default: J; Visible: No|
|EISVOORZORGSMAATRBUFFER             |LONG(0,10,0)           |PNH; Wanneer de asset een verhoogd risico/impact op/bij graafschade heeft, kan hier een veiligheidsbuffer in meters worden opgegeven. Wanneer aan de algemene EV-voorwaarden is voldaan en er binnen deze buffer gegraven wordt, ontvangt de grondroerder een eisvoorzorgsmaatregelbrief. Zonder opgaaf gelden algemene uitgangspunten en voorgedefinieerde bufferafstand. Bij een negatieve waarde, als -1, wordt geen brief uitgestuurd; ; Nullable: True; Default: None; Visible: No|
|DIEPTELEGGING                       |TEXT(255,0,0)          |PNH; Dieptelegging van de gehele buis tov maaiveld in cm; ; Nullable: False; Default: None; Visible: Yes|
|DATALEVERANCIER                     |TEXT(255,0,0)          |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |TEXT(255,0,0)          |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)            |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)           |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)            |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry               |PNH; Lijn; ; Nullable: False; Default: None; Visible: Yes|
|SHAPE_Length                        |DOUBLE(0,0,0)          |PNH; Lengte in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|LENGTE                              |DOUBLE(0,0,0)          |PNH; Lengte in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|


***
