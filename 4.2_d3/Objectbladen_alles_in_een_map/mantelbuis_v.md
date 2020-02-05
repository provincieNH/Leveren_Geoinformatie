## AREAALDATA.mantelbuis_v

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL 2015
* __Positionele nauwkeurigheid:__ 7,5 cm
* __Geometrie:__ Vlak
* __Definitie:__ Een mantelbuis is een buis bestemd voor de doorvoer en bescherming van kabels
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ Mantelbuis

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                    |-----    |
|OBJECTID                            |OID(38,0,0)             |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)        |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |String(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |Integer(0,10,0)         |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                       |String(255,0,0)         |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |String(255,0,0)         |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|BEHEERDER                           |String(255,0,0)         |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |String(255,0,0)         |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |String(255,0,0)         |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |String(255,0,0)         |PNH; Beschrijft de mantelbuis zelf; keuzelijst [typeSpecMBUI]; Nullable: True; Default: MB; Visible: Yes|
|MATERIAALTYPE                       |String(20,0,0)          |PNH; Materiaaltype; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None; Visible: Yes|
|VERTICALE_POSITIE                   |Integer(0,10,0)         |PNH; Verticale positie; keuzelijst [VerticalePositie]; Nullable: False; Default: 3; Visible: No|
|DIAMETERCM                          |SmallInteger(0,5,0)     |PNH; De diameter van de mantelbuis uitgedrukt in cm, afgerond in hele cijfers; ; Nullable: True; Default: None; Visible: Yes|
|OPMERKING                           |String(255,0,0)         |PNH; Toevoeging van subjectieve informatie met betrekking tot opmerkelijke waarnemingen; ; Nullable: True; Default: None; Visible: Yes|
|PLANJAAR                            |SmallInteger(0,5,0)     |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|HUIDIGESTATUS                       |String(50,0,0)          |PNH; Huidige status; keuzelijst [ConditionOfFacilityValue]; Nullable: False; Default: functional; Visible: Yes|
|GEONAUWKEURIGHEIDXY                 |String(50,0,0)          |PNH; Nauwkeurigheid van de liggingsgegevens in het horizontale vlak in cm; ; Nullable: False; Default: None; Visible: Yes|
|DIEPTELEGGING                       |String(255,0,0)         |PNH; Dieptelegging van de gehele buis tov maaiveld in cm; ; Nullable: True; Default: None; Visible: Yes|
|INDICATIEVELIGGING                  |String(1,0,0)           |PNH; Is de geometrie indicatief ingetekend, ja of nee; keuzelijst [jaNee]; Nullable: false; Default: J; Visible: Yes|
|EISVOORZORGSMAATRBUFFER             |Integer(0,10,0)         |PNH; Wanneer de asset een verhoogd risico/impact op/bij graafschade heeft, kan hier een veiligheidsbuffer in meters worden opgegeven. Wanneer aan de algemene EV-voorwaarden is voldaan en er binnen deze buffer gegraven wordt, ontvangt de grondroerder een eisvoorzorgsmaatregelbrief. Zonder opgaaf gelden algemene uitgangspunten en voorgedefinieerde bufferafstand. Bij een negatieve waarde, als -1, wordt geen brief uitgestuurd; ; Nullable: True; Default: None; Visible: Yes|
|INNETWERK                           |String(255,0,0)         |PNH; Verwijzende sleutel naar utiliteitsNet_tbl (simpel); ; Nullable: True; Default: None; Visible: No|
|IMKL_InNetwork                      |String(255,0,0)         |PNH; Provincie aanduiding voor het type net, VB: VRI of OVL; keuzelijst [IMKL_InNetwork]; Nullable: False; Default: None; Visible: Yes|
|DATALEVERANCIER                     |String(255,0,0)         |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |String(255,0,0)         |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)             |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)          |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)             |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry                |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                        |Double(0,0,0)           |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld; ; Nullable: False; Default: None; Visible: Yes|
|SHAPE_Area                          |Double(0,0,0)           |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld; ; Nullable: False; Default: None; Visible: Yes|

***
