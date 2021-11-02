## AREAALDATA.bord_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH/IMGEO
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Een paneel waarop informatie wordt afgebeeld. Dit zijn zowel RVV borden als matrix borden (voor automobilisten);  DRIP panelen zijn in Areaaldata te vinden als matrix borden met een TOPdesk ID
__LET OP:__ Bebording voor scheepvaartverkeer, wegwijzers, zwemwaterbebording en DRIS Panelen (voor OV reizigers) worden apart geadministreerd.
* __Mapping_BGT:__ bord_p
* __Mapping_Gisib:__ Bord, Matrix
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__(oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                          	 |----          	    |-----    |
|OBJECTID                            |OID(38,0,0)           |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)      |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |TEXT(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|NBD_NR                              |TEXT(25,0,0)          |NBD; Enkel tbv wegwijzers: Wegwijzernummer van een bord, zoals vastgelegd door NBD (https://www.rijkswaterstaat.nl/apps/geoservices/geodata/regios/civ/bewegwijzering_open/); Nullable: True; Default: None; Visible: No|
|GISIB_ID                            |LONG(0,10,0)          |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: Yes|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)         |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |DATE(8,0,0)           |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)           |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING              |SHORT(0,5,0)          |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: No|
|BEHEERDER                           |TEXT(255,0,0)         |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)         |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |TEXT(255,0,0)         |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |TEXT(255,0,0)         |PNH; Nadere typering van het object; keuzelijst [typeSpecBRD]; Nullable: True; Default: None; Visible: Yes|
|BGTPLUSTYPE                         |TEXT(50,0,0)          |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeBRD]; Nullable: False; Default: None; Visible: No|
|MATERIAALTYPE                       |TEXT(255,0,0)         |PNH; Materiaalkeuze; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None; Visible: No|
|REFLECTIEKLASSE                     |TEXT(255,0,0)         |PNH; Reflectieklasse; keuzelijst [REFLECTIEKLASSE]; Nullable: True; Default: None; Visible: Yes|
|RVVTYPEBORD                         |TEXT(255,0,0)         |PNH; RVV Type Bord; ; Nullable: True; Default: None; Visible: Yes|
|BEVESTIGINGSWIJZE                   |TEXT(255,0,0)         |PNH; BevestigingsWijze; keuzelijst [BEVESTIGINGSWIJZE]; Nullable: True; Default: None; Visible: No|
|AFMETINGEN                          |TEXT(255,0,0)         |PNH; Afmeting klasse opgeven, indien afwijkend in mm; ; Nullable: True; Default: None; Visible: No|
|DATUMPLAATSING                      |DATE(8,0,0)           |PNH; Datum Plaatsing; ; Nullable: True; Default: None; Visible: No|
|HECTOMETER                          |TEXT(255,0,0)         |PNH; Hectometrering; ; Nullable: True; Default: None; Visible: No|
|MAXIMUMSNELHEIDGEM                  |TEXT(1,0,0)           |PNH; MaximunSnelheidGemeld: veld om aan te geven als de toegestane max. snelheid is gemeld op het (hectometerings)bord: Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: O; Visible: No|
|PLANJAAR                            |SHORT(0,5,0)          |PNH; Planjaar TODO; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |TEXT(255,0,0)         |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|TOPDESK_ID                          |TEXT(255,0,0)         |PNH; Verwijzing naar ObjectID TOPdesk; ; Nullable: True; Default: None; Visible: No|
|HALTE                               |TEXT(255,0,0)         |PNH; Verwijzende sleutel naar halte_v (simpel); ; Nullable: True; Default: None; Visible: No|
|TRAJECT                             |TEXT(255,0,0)         |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM]; Nullable: True; Default: None; Visible: Yes|
|UITLEGGERPORTAAL                    |TEXT(255,0,0)         |PNH; Verwijzende sleutel naar uitleggerPortaal_l (simpel); ; Nullable: True; Default: None; Visible: No|
|PAAL                                |TEXT(255,0,0)         |PNH; Verwijzende sleutel naar paalDraagconstructie_p (simpel); ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |TEXT(255,0,0)         |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)           |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)          |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)           |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |TEXT(255,0,0)         |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry(0,0,0)       |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|

***
