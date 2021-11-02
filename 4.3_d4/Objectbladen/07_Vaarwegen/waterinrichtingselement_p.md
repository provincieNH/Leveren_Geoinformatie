## AREAALDATA.waterinrichtingselement_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMGEO
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Een ruimtelijk object ter inrichting van het water. Objecten als meerpalen en betonning worden in dit objecttype geadministreerd. Daar waar het object onderdeel uitmaakt van een kunstwerk wordt dit opgenomen in de NEN-2767-4 decompositie van het kunstwerk. In deze decompositie worden verder geen 
                geometrieën vastgelegd.
* __Mapping_BGT:__ waterinrichtingselement_p
* __Mapping_Gisib:__ Betonning, Meerpaal
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                          	 |----                     |-----    |
|OBJECTID                            |OID(38,0,0)              |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)         |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |TEXT(255,0,0)            |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)             |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)            |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |DATE(8,0,0)              |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)              |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING              |SHORT(0,5,0)             |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                           |TEXT(255,0,0)            |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)            |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |TEXT(255,0,0)            |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |TEXT(255,0,0)            |PNH; Nadere typering van het object; keuzelijst [typeSpecWIIPunt]; Nullable: True; Default: None; Visible: Yes|
|BGTPLUSTYPE                         |TEXT(50,0,0)             |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeWTIPunt]; Nullable: False; Default: None; Visible: No|
|JAARPLAATSING                       |SHORT(0,5,0)             |PNH; Is het jaar van aanleg van het waterinrichtingselement_p; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |TEXT(255,0,0)            |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|IDCODE                              |SHORT(0,5,0)             |PNH; Unieke ID code, komt voor op nautische kaarten; ; Nullable: True; Default: None; Visible: Yes|
|LICHTKARAKTER                       |TEXT(255,0,0)            |PNH; Lichtkarakter; keuzelijst [LICHTKARAKTER]; Nullable: True; Default: None; Visible: Yes|
|BEVESTIGINGSWIJZE                   |TEXT(255,0,0)            |PNH; Bevestigingswijze; keuzelijst [BEVESTIGINGSWIJZE]; Nullable: True; Default: None; Visible: No|
|MATERIAALTYPE                       |TEXT(20,0,0)             |PNH; Materiaalkeuze; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None; Visible: Yes|
|SOORT_ENERGIE                       |TEXT(10,0,0)             |PNH; Soort Energie; keuzelijst [SOORT_ENERGIE]; Nullable: True; Default: None; Visible: No|
|ZIJDE                               |TEXT(10,0,0)             |PNH; Zijde; keuzelijst [ZIJDE]; Nullable: True; Default: None; Visible: No|
|JAAR_PLAATSING_AANLEG_GESCHAT       |TEXT(1,0,0)              |PNH; Jaar plaatsing of aanleg is geschat: Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|MAXBELASTING                        |TEXT(255,0,0)            |PNH; Maximale toegestaan kracht wat op de bolder mag uitgedrukt worden (eenheid?) TODO; ; Nullable: True; Default: None; Visible: No|
|HECTOMETER                          |TEXT(255,0,0)            |PNH; Hectometrering; ; Nullable: True; Default: None; Visible: Yes|
|HOOGTE                              |FLOAT(0,10,0)            |PNH; Hoogte in meters; ; Nullable: True; Default: None; Visible: Yes|
|VAARWEGDEELTRAJECT                  |TEXT(255,0,0)            |PNH; Verwijzende sleutel naar vaarwegdeeltraject_v (simpel); ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |TEXT(255,0,0)            |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |TEXT(255,0,0)            |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)              |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)             |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)              |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry(0,0,0)          |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|


***
