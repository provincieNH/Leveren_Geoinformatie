## AREAALDATA.vaarwegdeeltraject_v

*Feature dataset: Functioneel*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ n.v.t. (abstracte indeling)
* __Geometrie:__ Vlak
* __Definitie:__ Vaarwegdeeltraject is een abstract functioneel gebied waarvan
de afmetingen zijn bepaald aan de hand van het geografisch
bereik van de geldende beperking en de geldende functie
zoals die is aangegeven door de beheerder of vanuit het
beheerplan. Het heeft geen vaste afmetingen maar past
altijd binnen het vaarwegtraject.
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ Vaarwegdeeltraject
* __Mapping_NTA8035:__ bs:SpatialRegion

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__| (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                |-----    |
|OBJECTID                            |OID(38,0,0)         |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)    |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |TEXT(255,0,0)       |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)        |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)       |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.html); Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |DATE(8,0,0)         |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)         |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|BEHEERDER                           |TEXT(255,0,0)       |PNH; Beheerder van het object; keuzelijst [BEHEERDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEERDER.html); Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)       |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ONDERHOUDER.html); Nullable: True; Default: None; Visible: Yes|
|NAAM                                |TEXT(255,0,0)       |PNH; Deeltraject-naam, bijvoorbeeld k20n-d; ; Nullable: True; Default: None; Visible: Yes|
|DEELTRAJECTNUMMER                   |TEXT(25,0,0)        |PNH; Deeltraject Nr; ; Nullable: True; Default: None; Visible: Yes|
|OPMERKING                           |TEXT(255,0,0)       |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|BEGINLINKEROEVER                    |TEXT(255,0,0)       |PNH; Begin Linker Oever; ; Nullable: True; Default: None; Visible: No|
|BEGINRECHTEROEVER                   |TEXT(255,0,0)       |PNH; Begin Rechter Oever; ; Nullable: True; Default: None; Visible: No|
|EINDLINKEROEVER                     |TEXT(255,0,0)       |PNH; Eind Linker Oever; ; Nullable: True; Default: None; Visible: No|
|EINDRECHTEROEVER                    |TEXT(255,0,0)       |PNH; Eind Rechter Oever; ; Nullable: True; Default: None; Visible: No|
|GELDENDEBEPERKING                   |TEXT(255,0,0)       |PNH; Waar een vaarwegdeeltraject niet voldoet aan een streefbeeld worden beperking opgelegd qua gebruik; ; Nullable: True; Default: None; Visible: No|
|LENGTELINKEROEVER                   |FLOAT(0,25,10)      |PNH; Lengte linkeroever (m); ; Nullable: True; Default: None; Visible: Yes|
|LENGTERECHTEROEVER                  |FLOAT(0,25,10)      |PNH; Lengte rechteroever (m); ; Nullable: True; Default: None; Visible: Yes|
|BESLUITNUMMER                       |TEXT(255,0,0)       |PNH; Besluitnummer waarde; keuzelijst [BESLUITNUMMER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BESLUITNUMMER.html); Nullable: True; Default: None; Visible: Yes|
|GEWENSTEBAGGERKWAL                  |TEXT(255,0,0)       |PNH; Gewenste baggerkwaliteit; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |TEXT(255,0,0)       |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|TRAJECT                             |TEXT(255,0,0)       |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/TRAJECT_NAAM.html); Nullable: True; Default: None; Visible: Yes|
|CREATED_USER                        |TEXT(255,0,0)       |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)         |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)        |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)         |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry            |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                        |DOUBLE(0,0,0)       |PNH; Omtrek in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|SHAPE_Area                          |DOUBLE(0,0,0)       |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|OMTREK                              |DOUBLE(0,0,0)       |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|
|OPPERVLAKTE                         |DOUBLE(0,0,0)       |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Area; ; Nullable: False; Default: None; Visible: Yes|


***
