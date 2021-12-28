## AREAALDATA.paalDraagconstructie_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Hoge draagconstructie, vervaardigd van metaal, hout, steen of kunststof dat dient om iets te dragen. __LET OP:__ In dit objecttype worden de IMGEO palen geadministreerd die primair een dragende functie hebben, zoals lichtmast, verkeersregelinstallatiepaal, verkeersbordpaal en haltepaal.
* __Mapping_BGT:__ paal_p
* __Mapping_Gisib:__ Mast
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__(oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                         	 |----          	       |-----    |
|OBJECTID                            |OID(38,0,0)              |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)         |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: No|
|AD_ID                               |TEXT(255,0,0)            |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)             |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BGTPLUSTYPE                         |TEXT(50,0,0)             |PNH; Nadere type omschrijving in de BGT; keuzelijst [typePAL](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typePAL.html); Nullable: False; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)            |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.html); Nullable: False; Default: Nieuw; Visible: Yes|
|HUIDIGESTATUS                       |TEXT(50,0,0)             |PNH; Huidige status; keuzelijst [ConditionOfFacilityValue](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ConditionOfFacilityValue.html); Nullable: False; Default: functional; Visible: No|
|OBJECTBEGINTIJD                     |DATE(8,0,0)              |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)              |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING              |SHORT(0,5,0)             |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                           |TEXT(255,0,0)            |PNH; Beheerder van het object; keuzelijst [BEHEERDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEERDER.html); Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)            |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ONDERHOUDER.html); Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |TEXT(255,0,0)            |PNH; Eigenaar van het object; keuzelijst [INSTANTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/INSTANTIE.html); Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |TEXT(255,0,0)            |PNH; Nadere typering van het object; keuzelijst [typeSpecPALDraagconstructie](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecPALDraagconstructie.html); Nullable: True; Default: None; Visible: Yes|
|FABRIKANTTYPECODE                   |TEXT(255,0,0)            |PNH; Fabrikanttypecode; ; Nullable: True; Default: None; Visible: Yes|
|MATERIAALTYPE                       |TEXT(20,0,0)             |PNH; Type materiaal; keuzelijst [MATERIAALTYPE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/MATERIAALTYPE.html); Nullable: True; Default: None; Visible: Yes|
|HECTOMETER                          |TEXT(255,0,0)            |PNH; Hectometrering; ; Nullable: True; Default: None; Visible: Yes|
|AANTALLUIKEN                        |SHORT(0,5,0)             |PNH; Aantal luiken; ; Nullable: True; Default: None; Visible: No|
|DATUMPLAATSING                      |DATE(8,0,0)              |PNH; Datum plaatsing; ; Nullable: True; Default: None; Visible: No|
|ELEVATIEHOEK                        |SHORT(0,5,0)             |PNH; Hoek van de uithouder indien aanwezig; ; Nullable: True; Default: None; Visible: No|
|HOOGTE                              |FLOAT(0,10,1)            |PNH; Lichtpunt hoogte in meters, 1 decimaal achter de komma; ; Nullable: True; Default: None; Visible: Yes|
|LENGTEUITHOUDER1                    |FLOAT(0,25,10)           |PNH; De lengte van de uithouder indien aanwezig in meters, 2 decimalen achter de komma; ; Nullable: True; Default: None; Visible: Yes|
|PAALNUMMER                          |TEXT(255,0,0)            |PNH; Paalnummer; ; Nullable: True; Default: None; Visible: Yes|
|OPMERKING                           |TEXT(3000,0,0)           |PNH; Extra toelichting; ; Nullable: True; Default: None; Visible: No|
|RALKLEUR                            |TEXT(30,0,0)             |PNH; De RAL-kleur(en) die gebruikt zijn voor het object. Eerst de kleurcode gevolgd door de naam van de kleur; ; Nullable: True; Default: None; Visible: No|
|LEVENSVERWACHTING                   |SHORT(0,5,0)             |PNH; Levensverwachting; ; Nullable: True; Default: None; Visible: No|
|PLANJAAR                            |SHORT(0,5,0)             |PNH; Het jaar dat nu gepland staat om item te vervangen; ; Nullable: True; Default: None; Visible: No|
|LENGTEUITHOUDER2                    |FLOAT(0,25,10)           |PNH; De lengte van de uithouder indien aanwezig in meters, 2 decimalen achter de komma; ; Nullable: True; Default: None; Visible: Yes|
|INNETWERK                           |String(255,0,0)          |PNH; Verwijzende sleutel naar utiliteitsNet_tbl (simpel); ; Nullable: True; Default: None; Visible: Yes|
|VERTICALE_POSITIE                   |LONG(0,10,0)             |PNH; Verticale positie; keuzelijst [VerticalePositie](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VerticalePositie.html); Nullable: False; Default: 3; Visible: No|
|TRAJECT                             |TEXT(255,0,0)            |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/TRAJECT_NAAM.html); Nullable: True; Default: None; Visible: Yes|
|UITLEGGERPORTAAL                    |TEXT(255,0,0)            |PNH; Verwijzende sleutel naar uitleggerPortaal_l (simpel), als armatuur daarop is gemonteerd; ; Nullable: True; Default: None; Visible: No|
|EISVOORZORGSMAATRBUFFER             |LONG(0,10,0)             |PNH; Wanneer de asset een verhoogd risico op graafschade heeft, kan hier een veiligheidsbuffer in meters worden opgegeven. Wanneer binnen deze buffer gegraven wordt, ontvangt de grondroerder een eisvoorzorgsmaatregelbrief; ; Nullable: True; Default: None; Visible: No|
|IMKL_INNETWORK                      |TEXT(255,0,0)            |PNH; Provincie aanduiding voor het type net, VB: VRI of OVL; keuzelijst [IMKL_InNetwork](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/IMKL_InNetwork.html); Nullable: False; Default: None; Visible: No|
|DATALEVERANCIER                     |TEXT(255,0,0)            |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |TEXT(255,0,0)            |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)              |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)             |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)              |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry(0,0,0)          |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|


***
