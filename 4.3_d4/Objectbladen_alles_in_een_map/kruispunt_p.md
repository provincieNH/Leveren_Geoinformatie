## AREAALDATA.kruispunt_p

*Feature dataset: Functioneel*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Punt
* __Definitie:__ Kruisingen hebben een uniek nummer.
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ Kruispunt
* __Aanwezig in BeheerApp (onder alias)__: VRI (Kruispunt)
* __Mapping_NTA8035:__ bs:SpatialRegion

***

|__KOLOM__                             |__TYPE (length, precision, scale)__                      |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----               |-----    |
|OBJECTID                            |OID(38,0,0)        |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)   |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: No|
|AD_ID                               |TEXT(255,0,0)      |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)       |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)      |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |DATE(8,0,0)        |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)        |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|BEHEERDER                           |TEXT(255,0,0)      |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)      |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |TEXT(255,0,0)      |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: No|
|TYPESPEC                            |TEXT(255,0,0)      |PNH; Nadere typering van het object; keuzelijst [typeSpecKRU]; Nullable: True; Default: None; Visible: Yes|
|CODE                                |TEXT(25,0,0)       |PNH; Kruispunt nummer; ; Nullable: True; Default: None; Visible: Yes|
|OPMERKING                           |TEXT(255,0,0)      |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|INNETWERK                           |TEXT(255,0,0)      |PNH; Verwijzende sleutel naar utiliteitsNet_tbl (simpel); ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |TEXT(255,0,0)      |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |TEXT(255,0,0)      |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)        |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)       |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)        |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry           |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|


***
