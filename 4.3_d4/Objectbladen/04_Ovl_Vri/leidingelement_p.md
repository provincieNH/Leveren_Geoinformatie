## AREAALDATA.leidingelement_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL
* __Positionele nauwkeurigheid:__ 7,5 cm
* __Geometrie:__ Punt
* __Definitie:__ Een ondergronds object dat bij een leiding of een themakaart hoort. __LET OP:__ dit is het objecttype waar kolken etc. in vastgelegd worden!
* __Mapping_BGT:__ x, put_p
* __Mapping_Gisib:__ Leidingelement
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                    |-----    |
|OBJECTID                            |OID(38,0,0)             |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)        |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken;; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |TEXT(255,0,0)           |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)            |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)           |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|HUIDIGESTATUS                       |TEXT(50,0,0)            |IMKL; Huidige status; keuzelijst [ConditionOfFacilityValue]; Nullable: True; Default: None; Visible: No|
|OBJECTBEGINTIJD                     |DATE(8,0,0)             |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)             |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING              |SHORT(0,5,0)            |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BOVENGRONDSZICHTBAAR                |TEXT(1,0,0)             |PNH; Aangegeven of het leidingelement bovengronds vanaf het maaiveld zichtbaat is; keuzelijst [jaNee]; Nullable: True; Default: None; Visible: No|
|BEHEERDER                           |TEXT(255,0,0)           |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)           |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |TEXT(255,0,0)           |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |TEXT(255,0,0)           |PNH; Nadere typering van het object; keuzelijst [typeSpecLDE]; Nullable: True; Default: None; Visible: Yes|
|DATUMPLAATSING                      |DATE(8,0,0)             |PNH; Datum Plaatsing; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |TEXT(255,0,0)           |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|PLANJAAR                            |SHORT(0,5,0)            |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|VERHOOGDRISICO                      |TEXT(10,0,0)            |PNH; Verhoogd risico Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: O; Visible: No|
|MATERIAALTYPE                       |TEXT(20,0,0)            |PNH; Type materiaal; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None; Visible: Yes|
|CONSTRUCTIEGEGEVEN                  |TEXT(255,0,0)           |PNH; Constructiegegevens; ; Nullable: True; Default: None; Visible: No|
|VERTICALE_POSITIE                   |FLOAT(0,10,2)           |PNH; Verticale positie; ; Nullable: True; Default: None; Visible: No|
|EISVOORZORGSMAATRBUFFER             |LONG(0,10,0)            |PNH; Wanneer de asset een verhoogd risico op graafschade heeft, kan hier een veiligheidsbuffer in meters worden opgegeven. Wanneer binnen deze buffer gegraven wordt, ontvangt de grondroerder een eisvoorzorgsmaatregelbrief; ; Nullable: True; Default: None; Visible: No|
|IMKL_InNetwork                      |TEXT(255,0,0)           |PNH; Provincie aanduiding voor het type net, VB: VRI of OVL; ; Nullable: False; Default: None; Visible: No|
|DIEPTELEGGING                       |TEXT(255,0,0)           |PNH; Diepte van leidingelement; ; Nullable: True; Default: None; Visible: Yes|
|INNETWERK                           |TEXT(255,0,0)           |PNH; Verwijzende sleutel naar utiliteitsNet_tbl (simpel); ; Nullable: True; Default: None; Visible: No|
|BUIS                                |TEXT(255,0,0)           |PNH; Verwijzende sleutel naar buis_l (simpel); ; Nullable: True; Default: None; Visible: No|
|GEONAUWKEURIGHEIDXY                 |TEXT(50,0,0)            |IMKL; Nauwkeurigheid van de liggingsgegevens in het horizontale vlak; ; Nullable: True; Default: False; Visible: No|
|DATALEVERANCIER                     |TEXT(255,0,0)           |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |TEXT(255,0,0)           |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)             |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)            |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)             |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry                |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|



***
