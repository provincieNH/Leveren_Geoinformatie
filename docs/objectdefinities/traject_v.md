## AREAALDATA.traject_v

*Feature dataset: Functioneel*


* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ n.v.t. (abstracte indeling)
* __Geometrie:__ Vlak
* __Definitie:__ Een abstract functioneel gebied rondom een weg of vaarweg dat onder de verantwoordelijkheid van de provincie Noord-Holland valt. Richtlijnen voor omvang van een wegtraject:
    + Een traject start/eindigt bij een eigendoms/beheergrens + Een traject start/eindigt bij een aansluiting op een weg van een hogere orde. Fietspaden vormen een ander traject (AD_ID) met eenzelfde nummer.
    + Een traject start/eindigt op een weg van een gelijke orde. Richtlijn voor omvang vaarwegtraject:
het gebied dat is gedefinieerd in de vaarwegverordening (breedte) en een
logisch doorvaartraject (lengte). In Areaaldata behoren tot een traject alle (beheer)objecten van de provincie Noord-Holland die binnen de beheergrenzen
van het traject liggen.
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ Traject
* __Aanwezig in BeheerApp (onder alias)__: Alle BeheerApps als referentielaag - is niet bewerktbaar (Traject (referentie))
* __Mapping_NTA8035:__ bs:SpatialRegion

***

|__KOLOM__                             |__TYPE (length, precision, scale)__                      |__DEFINITIE__(oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                  |-----    |
|OBJECTID                            |OID(38,0,0)           |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)      |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |String(255,0,0)       |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |Integer(0,10,0)       |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |String(255,0,0)       |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.html); Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)           |PNH; Datum waarop het object voor het eerst volgens het areaaldata datamodel wordt vastgelegd ; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)           |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |String(255,0,0)       |PNH; Nadere typering van het object; keuzelijst [typeSpecTRA](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecTRA.html); Nullable: True; Default: None; Visible: Yes|
|CODE                                |String(25,0,0)        |PNH; Unieke code ter identificatie van een traject; ; Nullable: True; Default: None; Visible: Yes|
|GEBRUIKSFUNCTIE                     |String(255,0,0)       |PNH; Gebruiksfunctie; keuzelijst [GEBRUIKSFUNCTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/GEBRUIKSFUNCTIE.html); Nullable: True; Default: None; Visible: Yes|
|OPMERKING                           |String(255,0,0)       |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|PLANJAAR                            |SmallInteger(0,5,0)   |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|RANGORDE                            |SmallInteger(0,5,0)   |PNH; TODO; ; Nullable: True; Default: None; Visible: No|
|AANLEGJAAR                          |SmallInteger(0,5,0)   |PNH; Is het jaar van aanleg van de vaarweg; ; Nullable: True; Default: None; Visible: No|
|BEGINLINKEROEVER                    |String(255,0,0)       |PNH; Begin Linker Oever; ; Nullable: True; Default: None; Visible: No|
|BEGINRECHTEROEVER                   |String(255,0,0)       |PNH; Begin Rechter Oever; ; Nullable: True; Default: None; Visible: No|
|BEPERKING                           |String(255,0,0)       |PNH; In het geval waar een vaarwegtraject niet voldoet aan het streefbeeld moet de geldende beperkingen die gelden voor het hele traject aangegeven worden; ; Nullable: True; Default: None; Visible: No|
|EINDLINKEROEVER                     |String(255,0,0)       |PNH; Eind Linker Oever; ; Nullable: True; Default: None; Visible: No|
|EINDRECHTEROEVER                    |String(255,0,0)       |PNH; Eind Rechter Oever; ; Nullable: True; Default: None; Visible: No|
|JAARAANLEG                          |SmallInteger(0,5,0)   |PNH; Is het jaar van aanleg van de vaarweg; ; Nullable: True; Default: None; Visible: No|
|LENGTELINKEROEVER                   |Float(0,25,10)        |PNH; Lengte linkeroever (m); ; Nullable: True; Default: None; Visible: Yes|
|LENGTERECHTEROEVER                  |Float(0,25,10)        |PNH; Lengte rechteroever (m); ; Nullable: True; Default: None; Visible: Yes|
|STREEFBEELD                         |String(255,0,0)       |PNH; Concrete visuele doelstelling; ; Nullable: True; Default: None; Visible: No|
|VOLDOET                             |SmallInteger(0,1,0)   |PNH; Geeft aan als de vaarweg voldoet aan het streefbeeld omschrijving; ; Nullable: True; Default: None; Visible: No|
|CEMTKLASSE                          |String(255,0,0)       |PNH; CEMTKLASSE object; keuzelijst [CEMT_KLASSE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/CEMT_KLASSE.html); Nullable: True; Default: None; Visible: No|
|MAATGEVENDSCHIP                     |String(255,0,0)       |PNH; MAATGEVENDSCHIP waarde; keuzelijst [MAATGEVEND_SCHIP](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/MAATGEVEND_SCHIP.html); Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |String(255,0,0)       |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |String(255,0,0)       |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)           |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)        |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)           |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry              |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                        |Double(0,0,0)         |PNH; Omtrek in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|SHAPE_Area                          |Double(0,0,0)         |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|OMTREK                              |Double(0,0,0)         |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|
|OPPERVLAKTE                         |Double(0,0,0)         |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Area; ; Nullable: False; Default: None; Visible: Yes|
|GEBIEDSCONTRACTREGIO                |String(255,0,0)       |PNH; Verwijzende sleutel naar gebiedscontractregio_v (simpel); keuzelijst [GCR_NAAM](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/GCR_NAAM.html); Nullable: True; Default: None; Visible: Yes|

***
