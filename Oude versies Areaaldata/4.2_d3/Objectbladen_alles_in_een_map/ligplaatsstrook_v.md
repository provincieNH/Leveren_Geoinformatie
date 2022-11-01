## AREAALDATA.ligplaatsstrook_v

*Feature dataset: Functioneel*


* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Vlak
* __Definitie:__ Een Ligplaatsstrook is een gebied waar ligplaatsen toegestaan zijn
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ Ligplaatsstrook

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__| (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                 |-----    |
|OBJECTID                            |OID(38,0,0)          |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)     |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: No|
|AD_ID                               |String(255,0,0)      |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |Integer(0,10,0)      |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|TYPESPEC                            |String(255,0,0)      |PNH; Nadere typering van het object; keuzelijst [typeSpecLPS]; Nullable: True; Default: None; Visible: Yes|
|VERWERKINGSSTATUS                   |String(255,0,0)      |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)          |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)          |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|BEHEERDER                           |String(255,0,0)      |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |String(255,0,0)      |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |String(255,0,0)      |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|ZIJDE                               |String(255,0,0)      |PNH; Zijde; keuzelijst [ZIJDE]; Nullable: True; Default: None; Visible: No|
|CULTUURHISTORISCHE                  |String(255,0,0)      |PNH; Cultuur Historische Waarde; ; Nullable: True; Default: None; Visible: No|
|GEMIDDELDEBREEDTE                   |Float(0,25,10)       |PNH; Gemiddelde Breedte; ; Nullable: True; Default: None; Visible: No|
|HMBEGIN                             |Float(0,25,10)       |PNH; Begin Hectometrering van Ligplaatsstrook; ; Nullable: True; Default: None; Visible: No|
|HMEIND                              |Float(0,25,10)       |PNH; Eind Hectometrering van Ligplaatsstrook; ; Nullable: True; Default: None; Visible: No|
|LENGTE                              |Float(0,10,0)        |PNH; Lengte Ligplaatsstrook in meter; ; Nullable: True; Default: None; Visible: Yes|
|LIGPLAATSSTROOKLIN                  |Float(0,25,10)       |PNH; Ligplaatsstrook Linker Oever; ; Nullable: True; Default: None; Visible: No|
|LIGPLAATSSTROOKREC                  |Float(0,25,10)       |PNH; Ligplaatsstrook Rechter Oever; ; Nullable: True; Default: None; Visible: No|
|OPENBAAR                            |String(1,0,0)        |PNH; Is het een openbare ligplaats; keuzelijst [jaNee]; Nullable: True; Default: None; Visible: Yes|
|OPMERKING                           |String(3000,0,0)     |PNH; Extra toelichting; ; Nullable: True; Default: None; Visible: No|
|RESTRUIMTE                          |Float(0,25,10)       |PNH; Beschikbare ruimte in nautisch profiel; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |String(255,0,0)      |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |String(255,0,0)      |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)          |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)       |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)          |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry             |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                      |Double(0,0,0)           |PNH; Omtrek in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|SHAPE_Area                        |Double(0,0,0)           |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|OMTREK                            |Double(0,0,0)           |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|
|OPPERVLAKTE                       |Double(0,0,0)           |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Area; ; Nullable: False; Default: None; Visible: Yes|
|ECOLOGISCHEHOOFDST                  |String(255,0,0)      |PNH; Verwijzende sleutel naar ecoHoofdstructuur_v (simpel); ; Nullable: True; Default: None; Visible: No|
|ECOLOGISCHEVERBIND                  |String(255,0,0)      |PNH; Verwijzende sleutel naar ecoVerbZone_v (simpel); ; Nullable: True; Default: None; Visible: No|
|VAARWEGDEELTRAJECT                  |String(255,0,0)      |PNH; Verwijzende sleutel naar vaarwegdeeltraject_v (simpel); ; Nullable: True; Default: None; Visible: Yes|

***
