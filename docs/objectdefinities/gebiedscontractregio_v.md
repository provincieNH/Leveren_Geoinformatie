## AREAALDATA.gebiedscontractregio_v

*Feature dataset: Functioneel*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ n.v.t. (abstracte indeling)
* __Geometrie:__ Vlak
* __Definitie:__ Perceelsindeling t.b.v. de onderhoudsbestekken en contractregio's.
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ Gebiedscontractregio
* __Aanwezig in BeheerApp (onder alias)__: Alle BeheerApps als referentielaag - is niet bewerktbaar (Gebiedscontractregio (referentie))
* __Mapping_NTA8035:__ bs:SpatialRegion


***

|__KOLOM__                             |__TYPE (length, precision, scale)__                      |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                  |-----    |
|OBJECTID                            |OID(38,0,0)           |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)      |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: No|
|AD_ID                               |TEXT(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|OPMERKING                           |TEXT(255,0,0)         |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)          |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)         |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.html); Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |DATE(8,0,0)           |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)           |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|REGIO                               |TEXT(255,0,0)         |PNH; Regio naam; ; Nullable: True; Default: None; Visible: Yes|
|NUMMER                              |SHORT(0,5,0)          |PNH; Noord Holland is opgedeeld in 7 regio's. Hier het nummer van de regio invullen (1 tot en met 7); ; Nullable: False; Default: None; Visible: Yes|
|DATALEVERANCIER                     |TEXT(255,0,0)         |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|OPDRACHTNEMER                       |TEXT(255,0,0)         |PNH; Opdrachtnemer; ; Nullable: True; Default: None; Visible: Yes|
|CONTOPDRACHTNEMER                   |TEXT(30,0,0)          |PNH; Contactpersoon van de opdrachtnemer, naam en telefoonnummer; ; Nullable: True; Default: None; Visible: No|
|CONTBSP                             |TEXT(30,0,0)          |PNH; Contactpersoon bij BSP PNH voor regio, naam en telefooonnummer; ; Nullable: True; Default: None; Visible: No|
|CONTINFRA                           |TEXT(30,0,0)          |PNH; Contactpersoon bij INFRA PNH voor regio, naam en telefoonnummer; ; Nullable: True; Default: None; Visible: Nos|
|CREATED_USER                        |TEXT(255,0,0)         |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)           |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)          |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)           |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry              |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                        |DOUBLE(0,0,0)         |PNH; Omtrek in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|SHAPE_Area                          |DOUBLE(0,0,0)         |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|OMTREK                              |DOUBLE(0,0,0)         |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|
|OPPERVLAKTE                         |DOUBLE(0,0,0)         |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Area; ; Nullable: False; Default: None; Visible: Yes|

***
