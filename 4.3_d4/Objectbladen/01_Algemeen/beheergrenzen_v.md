## AREAALDATA.beheergrenzen_v

*Feature dataset: Functioneel*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ n.v.t. (abstracte indeling)
* __Geometrie:__ Vlak
* __Definitie:__ De beheergrens bakent de publiekrechtelijke zeggenschap en verantwoordelijkheid van de provincie over het
areaal af. Zo wordt duidelijk tot hoever de provincie krachtens de Omgevingswet, de Waterwet en de
Wegenverkeerswet 1994 beheerder is van de provinciale (vaar)wegen. Ook regelt de beheergrens tot hoever de
provinciale bevoegdheid reikt bij het treffen van maatregelen, het al dan niet toestaan van handelingen van
derden, of juist het gedogen van situaties die van invloed zijn op de toestand of het gebruik van de (vaar)weg.
Daarnaast geeft de beheergrens aan tot hoever de provincie met haar Omgevingsverordening,
Waterverordening en Wegenverordening de publiekrechtelijke nadere regels voor de provinciale (vaar)wegen
voor kan schrijven. Daarmee regelt de beheergrens eenduidigheid en transparantie over het beheer. Dit om te
behoeden voor nadelige gevolgen voor beheerbaarheid, doorstroming en veiligheid van activiteiten op of rond
de infrastructuur.
* __Aanwezig in BeheerApp (onder alias)__: Alle BeheerApps als referentielaag - is niet bewerktbaar (Beheergrenzen)
* __Mapping_NTA8035:__ bs:SpatialRegion

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE(oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)__|
|------                              |----                  |-----    |
|OBJECTID                            |OID(38,0,0)           |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)      |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |TEXT(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|STATUS                              |TEXT(255,0,0)         |PNH; Nadere toelichting op het beheer en onderhoud van het gebied indien bekend; ; Nullable: True; Default: None; Visible: Yes|
|OPMERKING                           |TEXT(255,0,0)         |PNH; Toevoeging van subjectieve informatie met betrekking tot opmerkelijke waarnemingen; ; Nullable: True; Default: None; Visible: Yes|
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

