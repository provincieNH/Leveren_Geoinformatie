## AREAALDATA.ligplaatsstrook_v

*Feature dataset: Functioneel*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Vlak
* __Definitie:__ Een Ligplaatsstrook is een gebied waar ligplaatsen toegestaan zijn
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ Ligplaatsstrook
* __Mapping_NTA8035:__ bs:SpatialRegion

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__| (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                 |-----    |
|OBJECTID                            |OID(38,0,0)          |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)     |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |TEXT(255,0,0)        |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)         |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|TYPESPEC                            |TEXT(255,0,0)        |PNH; Nadere typering van het object; keuzelijst [typeSpecLPS]; Nullable: True; Default: None; Visible: Yes|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)        |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |DATE(8,0,0)          |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)          |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|BEHEERDER                           |TEXT(255,0,0)        |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)        |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |TEXT(255,0,0)        |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|ZIJDE                               |TEXT(255,0,0)        |PNH; Zijde; keuzelijst [Zijde]; Nullable: True; Default: None; Visible: No|
|CULTUURHISTORISCHE                  |TEXT(255,0,0)        |PNH; Cultuur Historische Waarde; ; Nullable: True; Default: None; Visible: No|
|GEMIDDELDEBREEDTE                   |FLOAT(0,25,10)       |PNH; Gemiddelde Breedte; ; Nullable: True; Default: None; Visible: No|
|HMBEGIN                             |FLOAT(0,25,10)       |PNH; Begin Hectometrering van Ligplaatsstrook; ; Nullable: True; Default: None; Visible: No|
|HMEIND                              |FLOAT(0,25,10)       |PNH; Eind Hectometrering van Ligplaatsstrook; ; Nullable: True; Default: None; Visible: No|
|LENGTE_VLAK                         |FLOAT(0,10,0)        |PNH; Lengte Ligplaatsstrook in meter, scriptmatig bepaald obv lengterichting; ; Nullable: True; Default: None; Visible: Yes|
|LIGPLAATSSTROOKLIN                  |FLOAT(0,25,10)       |PNH; Ligplaatsstrook Linker Oever; ; Nullable: True; Default: None; Visible: No|
|LIGPLAATSSTROOKREC                  |FLOAT(0,25,10)       |PNH; Ligplaatsstrook Rechter Oever; ; Nullable: True; Default: None; Visible: No|
|OPENBAAR                            |TEXT(1,0,0)          |PNH; Is het een openbare ligplaats; keuzelijst [jaNee]; Nullable: True; Default: None; Visible: Yes|
|OPMERKING                           |TEXT(3000,0,0)       |PNH; Extra toelichting; ; Nullable: True; Default: None; Visible: No|
|RESTRUIMTE                          |FLOAT(0,25,10)       |PNH; Beschikbare ruimte in nautisch profiel; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |TEXT(255,0,0)        |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |TEXT(255,0,0)        |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)          |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)         |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)          |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry             |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                        |DOUBLE(0,0,0)        |PNH; Omtrek in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|SHAPE_Area                          |DOUBLE(0,0,0)        |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|OMTREK                              |DOUBLE(0,0,0)        |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|
|OPPERVLAKTE                         |DOUBLE(0,0,0)        |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Area; ; Nullable: False; Default: None; Visible: Yes|
|ECOLOGISCHEHOOFDST                  |TEXT(255,0,0)        |PNH; Verwijzende sleutel naar ecoHoofdstructuur_v (simpel); ; Nullable: True; Default: None; Visible: No|
|ECOLOGISCHEVERBIND                  |TEXT(255,0,0)        |PNH; Verwijzende sleutel naar ecoVerbZone_v (simpel); ; Nullable: True; Default: None; Visible: No|
|VAARWEGDEELTRAJECT                  |TEXT(255,0,0)        |PNH; Verwijzende sleutel naar vaarwegdeeltraject_v (simpel); ; Nullable: True; Default: None; Visible: Yes|

***
