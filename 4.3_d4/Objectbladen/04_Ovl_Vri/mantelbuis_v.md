## AREAALDATA.mantelbuis_v

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL 2015
* __Positionele nauwkeurigheid:__ 7,5 cm
* __Geometrie:__ Vlak
* __Definitie:__ Een mantelbuis is een buis bestemd voor de doorvoer en bescherming van kabels
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ Mantelbuis
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                    |-----    |
|OBJECTID                            |OID(38,0,0)             |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)        |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken;; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |TEXT(255,0,0)           |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)            |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)           |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |DATE(8,0,0)             |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)             |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|BEHEERDER                           |TEXT(255,0,0)           |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)           |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |TEXT(255,0,0)           |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |TEXT(255,0,0)           |PNH; Beschrijft de mantelbuis zelf; keuzelijst [typeSpecMBUI]; Nullable: True; Default: MB; Visible: Yes|
|MATERIAALTYPE                       |TEXT(20,0,0)            |PNH; Materiaaltype; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None; Visible: Yes|
|VERTICALE_POSITIE                   |LONG(0,10,0)            |PNH; Verticale positie; keuzelijst [VerticalePositie]; Nullable: False; Default: 3; Visible: No|
|DIAMETERCM                          |SHORT(0,5,0)            |PNH; De diameter van de mantelbuis uitgedrukt in cm, afgerond in hele cijfers; ; Nullable: True; Default: None; Visible: Yes|
|OPMERKING                           |TEXT(255,0,0)           |PNH; Toevoeging van subjectieve informatie met betrekking tot opmerkelijke waarnemingen; ; Nullable: True; Default: None; Visible: Yes|
|PLANJAAR                            |SHORT(0,5,0)            |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|HUIDIGESTATUS                       |TEXT(50,0,0)            |PNH; Huidige status; keuzelijst [ConditionOfFacilityValue]; Nullable: False; Default: functional; Visible: Yes|
|GEONAUWKEURIGHEIDXY                 |TEXT(50,0,0)            |PNH; Nauwkeurigheid van de liggingsgegevens in het horizontale vlak in cm; ; Nullable: False; Default: None; Visible: Yes|
|DIEPTELEGGING                       |TEXT(255,0,0)           |PNH; Dieptelegging van de gehele buis tov maaiveld in cm; ; Nullable: True; Default: None; Visible: Yes|
|INDICATIEVELIGGING                  |TEXT(1,0,0)             |PNH; Is de geometrie indicatief ingetekend, ja of nee; keuzelijst [jaNee]; Nullable: false; Default: J; Visible: Yes|
|EISVOORZORGSMAATRBUFFER             |LONG(0,10,0)            |PNH; Wanneer de asset een verhoogd risico/impact op/bij graafschade heeft, kan hier een veiligheidsbuffer in meters worden opgegeven. Wanneer aan de algemene EV-voorwaarden is voldaan en er binnen deze buffer gegraven wordt, ontvangt de grondroerder een eisvoorzorgsmaatregelbrief. Zonder opgaaf gelden algemene uitgangspunten en voorgedefinieerde bufferafstand. Bij een negatieve waarde, als -1, wordt geen brief uitgestuurd; ; Nullable: True; Default: None; Visible: No|
|INNETWERK                           |TEXT(255,0,0)           |PNH; Verwijzende sleutel naar utiliteitsNet_tbl (simpel); ; Nullable: True; Default: None; Visible: No|
|IMKL_INNETWORK                      |TEXT(255,0,0)           |PNH; Provincie aanduiding voor het type net, VB: VRI of OVL; keuzelijst [IMKL_InNetwork]; Nullable: False; Default: None; Visible: Yes|
|DATALEVERANCIER                     |TEXT(255,0,0)           |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |TEXT(255,0,0)           |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)             |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)            |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)             |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LENGTE_VLAK                         |FLOAT(0,10,0)           |PNH; Lengte in meter, scriptmatig bepaald obv lengterichting mantelbuis; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE                               |Geometry                |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                        |DOUBLE(0,0,0)           |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld; ; Nullable: False; Default: None; Visible: Yes|
|SHAPE_Area                          |DOUBLE(0,0,0)           |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld; ; Nullable: False; Default: None; Visible: Yes|

***
