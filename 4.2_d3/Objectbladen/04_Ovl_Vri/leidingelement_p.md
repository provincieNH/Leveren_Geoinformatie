## AREAALDATA.leidingelement_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL
* __Positionele nauwkeurigheid:__ 7,5 cm
* __Geometrie:__ Punt
* __Definitie:__ Een ondergronds object dat bij een leiding of een themakaart hoort. __LET OP:__ dit is het objecttype waar kolken etc. in vastgelegd worden!
* __Mapping_BGT:__ x, put_p
* __Mapping_Gisib:__ Leidingelement

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                    |-----    |
|OBJECTID                            |OID(38,0,0)             |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)        |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |String(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |Integer(0,10,0)         |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                       |String(255,0,0)         |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |String(255,0,0)         |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|STATUS                              |String(10,0,0)          |BGT; BGT status van het object; keuzelijst [status]; Nullable: True; Default: bestaand; Visible: No|
|HUIDIGESTATUS                       |String(50,0,0)          |IMKL; Huidige status; keuzelijst [ConditionOfFacilityValue]; Nullable: True; Default: None; Visible: No|
|OBJECTBEGINTIJD                     |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING              |SmallInteger(0,5,0)     |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BOVENGRONDSZICHTBAAR                |String(1,0,0)           |PNH; Aangegeven of het leidingelement bovengronds vanaf het maaiveld zichtbaat is; keuzelijst [jaNee]; Nullable: True; Default: None; Visible: No|
|BEHEERDER                           |String(255,0,0)         |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |String(255,0,0)         |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |String(255,0,0)         |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |String(255,0,0)         |PNH; Nadere typering van het object; keuzelijst [typeSpecLDE]; Nullable: True; Default: None; Visible: Yes|
|DATUMPLAATSING                      |Date(8,0,0)             |PNH; Datum Plaatsing; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |String(255,0,0)         |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|PLANJAAR                            |SmallInteger(0,5,0)     |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|VERHOOGDRISICO                      |String(10,0,0)          |PNH; Verhoogd risico Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: O; Visible: No|
|MATERIAALTYPE                       |String(20,0,0)          |PNH; Type materiaal; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None; Visible: Yes|
|CONSTRUCTIEGEGEVEN                  |String(255,0,0)         |PNH; Constructiegegevens; ; Nullable: True; Default: None; Visible: No|
|VERTICALE_POSITIE                   |Float(0,10,2)           |PNH; Verticale positie; ; Nullable: True; Default: None; Visible: No|
|EISVOORZORGSMAATRBUFFER             |Integer(0,10,0)         |PNH; Wanneer de asset een verhoogd risico op graafschade heeft, kan hier een veiligheidsbuffer in meters worden opgegeven. Wanneer binnen deze buffer gegraven wordt, ontvangt de grondroerder een eisvoorzorgsmaatregelbrief; ; Nullable: True; Default: None; Visible: No|
|IMKL_InNetwork                      |String(255,0,0)         |PNH; Provincie aanduiding voor het type net, VB: VRI of OVL; ; Nullable: False; Default: None; Visible: No|
|DIEPTELEGGING                       |String(255,0,0)         |PNH; Diepte van leidingelement; ; Nullable: True; Default: None; Visible: Yes|
|INNETWERK                           |String(255,0,0)         |PNH; Verwijzende sleutel naar utiliteitsNet_tbl (simpel); ; Nullable: True; Default: None; Visible: Yes|
|GEONAUWKEURIGHEIDXY                 |String(50,0,0)          |IMKL; Nauwkeurigheid van de liggingsgegevens in het horizontale vlak; ; Nullable: True; Default: False; Visible: No|
|DATALEVERANCIER                     |String(255,0,0)         |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |String(255,0,0)         |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)             |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)          |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)             |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry                |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|



***
