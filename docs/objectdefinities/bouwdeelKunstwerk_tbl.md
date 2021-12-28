## AREAALDATA.bouwdeelKunstwerk_tbl

*Feature dataset: -*

* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ NEN 2767-4 / PNH
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Geen
* __Definitie:__ Laagste niveau van decompositie van kunstwerk_vast via kwElement. Het begrip NEN Bouwdeel is niet gedefinieerd.
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__(oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                   |-----    |
|OBJECTID                            |OID(38,0,0)            |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|NENMATERIAALSOORT                   |TEXT(255,0,0)          |PNH; NENMateriaalsoort; keuzelijst [MATERIAALTYPE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/MATERIAALTYPE.html); Nullable: True; Default: None; Visible: No|
|BEHEERDER                           |TEXT(255,0,0)          |PNH; Beheerder van het object; keuzelijst [BEHEERDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEERDER.html); Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)          |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ONDERHOUDER.html); Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |TEXT(255,0,0)          |PNH; Eigenaar van het object; keuzelijst [INSTANTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/INSTANTIE.html); Nullable: True; Default: None; Visible: Yes|
|OPMERKING                           |TEXT(255,0,0)          |PNH; Extra toelichting; ; Nullable: True; Default: None; Visible: Yes|
|CONDITIESCORE                       |LONG(0,10,0)           |PNH; Conditiescore conform NEN 2767-4; ; Nullable: True; Default: None; Visible: No|
|CONDITIESCORE_DATUM                 |DATE(8,0,0)            |PNH; Datum opname Conditiescore; ; Nullable: True; Default: None; Visible: No|
|CONDITIESCORE_OPM                   |TEXT(3000,0,0)         |PNH; Opmerking bij conditiescore conform NEN 2767-4; ; Nullable: True; Default: None; Visible: Yes|
|KWELEMENT                           |TEXT(255,0,0)          |PNH; Verwijzende sleutel naar kwElement_tbl (simpel); ; Nullable: True; Default: None; Visible: No|
|TYPESPEC                            |TEXT(255,0,0)          |PNH; Nadere typering van het object; keuzelijst [typeSpecBWD](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecBWD.html); Nullable: True; Default: None; Visible: Yes|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)          |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.html); Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |DATE(8,0,0)            |BGT; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)            |BGT; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)       |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: No|
|GISIB_ID                            |LONG(0,10,0)           |PNH; ID beheer openbare ruimte (GISIB); ; Nullable: True; Default: None; Visible: No|
|AD_ID                               |TEXT(255,0,0)          |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; ; Nullable: False; Default: None; Visible: Yes|
|CREATED_USER                        |TEXT(255,0,0)          |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)            |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)           |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)            |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |TEXT(255,0,0)          |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|VOLGNR                              |LONG(0,10,0)           |PNH; Indien een reeks van dezelfde bouwdelen voorkomen dan dienen deze worden met een volgnummer te worden geduid. De nummering dient logischerwijs te worden gestart met noord georiënteerde item als eerste te benoemen en vervolgens de daaropvolgende items door te nummeren met de klok mee.; keuzelijst [VOLGNUMMER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VOLGNUMMER.html); Nullable: True; Default: None; Visible: No |
|WINDRICHTING                        |TEXT(255,0,0)          |PNH; Om de locatie van verschillende bouwdelen aan te duiden; keuzelijst [WINDRICHTING](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/WINDRICHTING.html); Nullable: True; Default: None; Visible: Yes|
|LOCATIEDUIDING                      |TEXT(255,0,0)          |PNH; Om de locatie van verschillende bouwdelen aan te duiden waar volgnr en windrichting niet volstaan; keuzelijst [LOCATIEDUIDING](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/LOCATIEDUIDING.html); Nullable: True; Default: None; Visible: Yes|
|AANTAL_BOUWDELEN                    |LONG(0,10,0)           |PNH; Indien een of meer dezelfde bouwdelen als een enkel bouwdeel mogen worden opgenomen, kan in dit attribuut worden aangegeven hoeveel bouwdelen het betreft. Let op: Enkel door PNH in te vullen; ; Nullable: True; Default: 1; Visible: No |
|CAD_CODE                            |TEXT(255,0,0)          |PNH; Afkorting van het bouwdeel zoals opgenomen in bijbehorende CAD-tekeningen; keuzelijst [CAD_code](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/CAD_code.html); Nullable: True; Default: None; Visible: Yes|

***

