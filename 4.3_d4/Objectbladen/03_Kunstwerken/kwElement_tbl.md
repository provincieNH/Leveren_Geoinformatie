## AREAALDATA.kwElement_tbl

*Feature dataset: -*

* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ NEN 2767-4 / PNH
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__  Geen
* __Definitie:__ Een NEN Element is gedefinieerd als "een samenstel van bouwdelen die tezamen een afzonderlijk herkenbaar 
component van een beheerobject vormen". Een NEN Element kan afhankelijk van het beheerobject waar deze bij hoort
gemodelleerd zijn als ELEMENT of GELUIDWERENDE_CONSTRUCTIE. 
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                    |-----    |
|CONFORMNEN                          |TEXT(1,0,0)             |PNH; Is Element conform NEN (Ja/Nee); keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|OPMERKING                           |TEXT(255,0,0)           |PNH; Opmerking; ; Nullable: True; Default: None; Visible: No|
|CONDITIESCORE                       |LONG(0,10,0)            |PNH; Conditiescore conform NEN 2767-4; ; Nullable: True; Default: None; Visible: No|
|CONDITIESCORE_DATUM                 |DATE(8,0,0)             |PNH; Datum opname Conditiescore; ; Nullable: True; Default: None; Visible: No|
|CONDITIESCORE_OPM                   |TEXT(3000,0,0)          |PNH; Opmerking bij conditiescore conform NEN 2767-4; ; Nullable: True; Default: None; Visible: Yes|
|KRITISCH                            |TEXT(1,0,0)             |PNH; Kritisch (Ja/Nee); keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|KUNSTWERK                           |TEXT(255,0,0)           |PNH; Verwijzende sleutel naar kunstwerk_p (simpel); ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                       |TEXT(255,0,0)           |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|TYPESPEC                            |TEXT(255,0,0)           |PNH; Nadere typering van het object; keuzelijst [typeSpecKWE]; Nullable: True; Default: None; Visible: Yes|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)           |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTID                            |OID(38,0,0)             |PNH; Interne ID ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)        |PNH; Global Unique Identifier; ; Nullable: False; Default: None; Visible: No|
|GISIB_ID                            |LONG(0,10,0)            |PNH; ID beheer openbare ruimte (GISIB); ; Nullable: True; Default: None; Visible: No|
|AD_ID                               |TEXT(255,0,0)           |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; ; Nullable: False; Default: None; Visible: Yes|
|OBJECTBEGINTIJD                     |DATE(8,0,0)             |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)             |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|CREATED_USER                        |TEXT(255,0,0)           |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)             |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)            |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)             |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|BEHEERDER                           |TEXT(255,0,0)           |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)           |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: No|
|EIGENAAR                            |TEXT(255,0,0)           |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |TEXT(255,0,0)           |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|VOLGNR                              |LONG(0,10,0)            |PNH; Indien een reeks van dezelfde elementen voorkomen dan dienen deze worden met een volgnummer te worden geduid. De nummering dient logischerwijs te worden gestart met noord-georiënteerde item als eerste te benoemen en vervolgens de daaropvolgende items door te nummeren met de klok mee.; keuzelijst [VOLGNUMMER]; Nullable: True; Default: None; Visible: No |
|WINDRICHTING                        |TEXT(255,0,0)           |PNH; Om de locatie van verschillende elementen aan te duiden; keuzelijst [WINDRICHTING]; Nullable: True; Default: None; Visible: Yes|
|LOCATIEDUIDING                      |TEXT(255,0,0)           |PNH; Om de locatie van verschillende elementen aan te duiden waar volgnr en windrichting niet volstaan; keuzelijst [Locatieduiding]; Nullable: True; Default: None; Visible: Yes|
|AANTAL_ELEMENTEN                    |LONG(0,10,0)            |PNH; Indien een of meer dezelfde elementen als een enkel element mogen worden opgenomen, kan in dit attribuut worden aangegeven hoeveel elementen het betreft. Let op: Enkel door PNH in te vullen; ; Nullable: True; Default: 1; Visible: No |
|CAD_CODE                            |TEXT(255,0,0)           |PNH; Afkorting van het element zoals opgenomen in bijbehorende CAD-tekeningen; keuzelijst [CAD_code]; Nullable: True; Default: None; Visible: Yes|

***


