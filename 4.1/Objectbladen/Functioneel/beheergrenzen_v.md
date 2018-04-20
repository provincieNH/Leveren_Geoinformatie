## AREAALDATA.beheergrenzen_v

*Feature dataset: Functioneel*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt, Abstracte indeling
* __SHAPE:__ Vlak
* __Definitie:__

De beheergrens bakent de publiekrechtelijke zeggenschap en verantwoordelijkheid van de provincie over het
areaal af. Zo wordt duidelijk tot hoever de provincie krachtens de Omgevingswet, de Waterwet en de
Wegenverkeerswet 1994 beheerder is van de provinciale (vaar)wegen. Ook regelt de beheergrens tot hoever de
provinciale bevoegdheid reikt bij het treffen van maatregelen, het al dan niet toestaan van handelingen van
derden, of juist het gedogen van situaties die van invloed zijn op de toestand of het gebruik van de (vaar)weg.
Daarnaast geeft de beheergrens aan tot hoever de provincie met haar Omgevingsverordening,
Waterverordening en Wegenverordening de publiekrechtelijke nadere regels voor de provinciale (vaar)wegen
voor kan schrijven. Daarmee regelt de beheergrens eenduidigheid en transparantie over het beheer. Dit om te
behoeden voor nadelige gevolgen voor beheerbaarheid, doorstroming en veiligheid van activiteiten op of rond
de infrastructuur.


***

|KOLOM                               |TYPE                  |DEFINITIE|
|------                              |----                  |-----    |
|OBJECTID                            |OID(38,0,0)           |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None|
|AD_ID                               |String(255,0,0)       |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None|
|STATUS                              |String(255,0,0)       |PNH; Nadere toelichting op het beheer en onderhoud van het gebied indien bekend; Nullable: True; Default: None|
|CREATED_USER                        |String(255,0,0)       |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)           |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)        |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)           |PNH; Datum van de laatste mutatie; Nullable: True|
|SHAPE                               |Geometry              |PNH; Vlak|
|SHAPE.LENGTH                        |Double(0,0,0)         |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None|
|SHAPE.AREA                          |Double(0,0,0)         |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None|

***

