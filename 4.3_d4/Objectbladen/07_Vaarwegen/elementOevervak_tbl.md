## AREAALDATA.ElementOevervak_tbl

*Feature dataset: -*

* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ NEN 2767-4 / PNH
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Geen
* __Definitie:__ Elementniveau van decompositie van oevervakken. Een NEN Element is gedefinieerd als 'een samenstel van bouwdelen die tezamen een afzonderlijk herkenbaar 
component van een beheerobject vormen'.
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                     |-----    |
|OBJECTID                            |OID(38,0,0)              |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)         |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |TEXT(255,0,0)            |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)             |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)            |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |DATE(8,0,0)              |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)              |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|BEHEERDER                           |TEXT(255,0,0)            |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)            |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |TEXT(255,0,0)            |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |TEXT(255,0,0)            |PNH; Nadere typering van het object; keuzelijst [typeSpecSHDWater]; Nullable: True; Default: None; Visible: Yes|
|OPMERKING                           |TEXT(255,0,0)            |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|CONDITIESCORE                       |LONG(0,10,0)             |PNH; Conditiescore conform NEN 2767-4; ; Nullable: True; Default: None; Visible: No|
|CONDITIESCORE_DATUM                 |DATE(8,0,0)              |PNH; Datum opname Conditiescore; ; Nullable: True; Default: None; Visible: No|
|CONDITIESCORE_OPM                   |TEXT(3000,0,0)           |PNH; Opmerking bij conditiescore conform NEN 2767-4; ; Nullable: True; Default: None; Visible: Yes|
|ONDERDEELWATERKERING                |TEXT(1,0,0)              |PNH; Onderdeel van waterkering/dijk of niet; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|OEVERVAK                            |TEXT(255,0,0)            |PNH; Verwijzende sleutel naar oevervak_v (simpel); ; Nullable: True; Default: None; Visible: Yes|
|AANLEGJAAR                          |SHORT(0,5,0)             |PNH; Aanlegjaar; ; Nullable: True; Default: None; Visible: No|
|FOTO                                |TEXT(255,0,0)            |PNH; Verwijzing naar Foto; ; Nullable: True; Default: None; Visible: No|
|HMBEGIN                             |FLOAT(0,25,10)           |PNH; Hectometrering begin beschoeiing; ; Nullable: True; Default: None; Visible: No|
|HMEIND                              |FLOAT(0,25,10)           |PNH; Hectometrering eind beschoeiing; ; Nullable: True; Default: None; Visible: No|
|HOOGTE                              |FLOAT(0,10,0)            |PNH; Bovenkant van constructie tov NAP in centimeters en op 5 centimeter nauwkeurig; ; Nullable: True; Default: None; Visible: Yes|
|PLANJAAR                            |SHORT(0,5,0)             |PNH; Planjaar; ; Nullable: True; Default: None; Visible: No|
|RESTLEVENSDUUR                      |SHORT(0,5,0)             |PNH; Restlevensduur (berekend op basis van planjaar en datum inspectieopname; ; Nullable: True; Default: None; Visible: No|
|ZIJDE                               |TEXT(10,0,0)             |PNH; Zijde; keuzelijst [Zijde]; Nullable: True; Default: None; Visible: No|
|FUNDERING                           |TEXT(255,0,0)            |PNH; Fundering; ; Nullable: True; Default: None; Visible: No|
|HECTOMETER                          |TEXT(255,0,0)            |PNH; Hectometrering; ; Nullable: True; Default: None; Visible: Yes|
|FABRIKANT                           |TEXT(255,0,0)            |PNH; Fabrikant; ; Nullable: True; Default: None; Visible: No|
|GARANTIECERTIFICAAT                 |TEXT(255,0,0)            |PNH; Garantie certificaat aanwezig; ; Nullable: True; Default: None; Visible: No|
|TRAJECT                             |TEXT(255,0,0)            |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM] ; Nullable: True; Default: None; Visible: Yes|
|DATALEVERANCIER                     |TEXT(255,0,0)            |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |TEXT(255,0,0)            |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)              |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)             |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)              |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|

***

