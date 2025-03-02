## AREAALDATA.buis_l

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL
* __Positionele nauwkeurigheid:__ 7,5 cm
* __SHAPE:__ Lijn
* __Definitie:__ Holle leiding voor het doorstromen van gassen, vloeistoffen of capsules, bestemd om hetzij gas,
een vloeistof of capsules te transporteren, hetzij een vloeistof als intermediair te gebruiken voor het transport van
warmte of een opgeloste of verpulverde stof. NB. Bij PNH eigenlijk alleen gebruikt voor riolering.

***

|KOLOM                               |TYPE (length, precision, scale)                   |DEFINITIE (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                   |-----    |
|OBJECTID                            |OID(38,0,0)            |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)       |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |String(255,0,0)        |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |Integer(0,10,0)        |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                       |String(255,0,0)        |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |String(255,0,0)        |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)            |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)            |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|BEHEERDER                           |String(255,0,0)        |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |String(255,0,0)        |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |String(255,0,0)        |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |String(255,0,0)        |PNH; Nadere typering van het object; keuzelijst [typeSpecBUI]; Nullable: True; Default: None; Visible: Yes|
|THEMAKAART                          |String(255,0,0)        |PNH; Themakaart; keuzelijst [THEMAKAART]; Nullable: True; Default: None; Visible: Yes|
|bovengrondsZichtbaar                |String(1,0,0)          |IMKL; Aangegeven wordt of de buis bovengronds vanaf het maaiveld zichtbaar is; keuzelijst [jaNee]; Nullable: True; Default: None; Visible: No|
|OMSCHRIJVING                        |String(255,0,0)        |PNH; Extra toelichting; ; Nullable: True; Default: None; Visible: Yes|
|DATUMPLAATSING                      |Date(8,0,0)            |PNH; Datum aanleg; ; Nullable: True; Default: None; Visible: No|
|DIAMETERCM                          |SmallInteger(0,10,0)   |PNH; Diameter van de buis in cm, afgerond op hele getallen; ; Nullable: True; Default: None; Visible: Yes|
|OPMERKING                           |String(255,0,0)        |PNH; Toevoeging van subjectieve informatie met betrekking tot opmerkelijke waarnemingen; ; Nullable: True; Default: None; Visible: No|
|PLANJAAR                            |SmallInteger(0,10,0)   |PNH; Het jaar dat nu gepland staat om item te vervangen; ; Nullable: True; Default: None; Visible: No|
|PRODUCT                             |String(255,0,0)        |PNH; Het product dat door de leiding vervoerd wordt of kan worden vervoerd, 'Energie', 'Data' of 'Onbekend'; ; Nullable: True; Default: Onbekend; Visible: No|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0)   |PNH; Verwachte restlevensduur in jaren vanaf moment van inspectie; ; Nullable: True; Default: None; Visible: No|
|VOORZORGMAATREGEL                   |String(255,0,0)        |PNH; Vermelding of er voorzorgsmaatregelen getroffen dienen te worden. Aangegeven wordt wat de voorzorgsmaatregel is; ; Nullable: True; Default: None; Visible: No|
|MATERIAALTYPE                       |String(255,0,0)        |PNH; Type materiaal; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None; Visible: Yes|
|INNETWERK                           |String(255,0,0)        |PNH; FK naar utiliteitsNet_tbl; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |String(255,0,0)        |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |String(255,0,0)        |PNH; Naam van gebruiker die de rij heeft aangemaakt; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)            |PNH; Aanmaakdatum; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)         |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)            |PNH; Datum van de laatste mutatie; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry               |PNH; Lijn; ; Nullable:False; Default:None; Visible: Yes|
|SHAPE_Length                        |Double(0,0,0)          |PNH; Lengte in meters, 5 decimalen. Dit wordt automatisch gevuld; ; Nullable: False; Default: None; Visible: Yes|


***
