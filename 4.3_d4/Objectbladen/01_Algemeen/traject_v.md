## AREAALDATA.traject_v

*Feature dataset: Functioneel*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ n.v.t. (abstracte indeling)
* __Geometrie:__ Vlak
* __Definitie:__ Een abstract functioneel gebied rondom een weg of vaarweg dat onder de verantwoordelijkheid van de provincie Noord-Holland valt. Richtlijnen voor omvang van een wegtraject:
    + Een traject start/eindigt bij een eigendoms/beheergrens + Een traject start/eindigt bij een aansluiting op een weg van een hogere orde.
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
|GLOBALID                            |GlobalID(38,0,0)      |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: No|
|AD_ID                               |TEXT(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|BEHEERDER                           |TEXT(255,0,0)         |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)          |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)         |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |DATE(8,0,0)           |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)           |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |TEXT(255,0,0)         |PNH; Nadere typering van het object; keuzelijst [typeSpecTRA]; Nullable: True; Default: None; Visible: Yes|
|CODE                                |TEXT(25,0,0)          |PNH; Unieke code ter identificatie van een traject; ; Nullable: True; Default: None; Visible: Yes|
|GEBRUIKSFUNCTIE                     |TEXT(255,0,0)         |PNH; Gebruiksfunctie; keuzelijst [GEBRUIKSFUNCTIE]; Nullable: True; Default: None; Visible: Yes|
|OPMERKING                           |TEXT(255,0,0)         |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|PLANJAAR                            |SHORT(0,5,0)          |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|RANGORDE                            |SHORT(0,5,0)          |PNH; TODO; ; Nullable: True; Default: None; Visible: No|
|AANLEGJAAR                          |SHORT(0,5,0)          |PNH; Is het jaar van aanleg van de vaarweg; ; Nullable: True; Default: None; Visible: No|
|BEGINLINKEROEVER                    |TEXT(255,0,0)         |PNH; Begin Linker Oever; ; Nullable: True; Default: None; Visible: No|
|BEGINRECHTEROEVER                   |TEXT(255,0,0)         |PNH; Begin Rechter Oever; ; Nullable: True; Default: None; Visible: No|
|BEPERKING                           |TEXT(255,0,0)         |PNH; In het geval waar een vaarwegtraject niet voldoet aan het streefbeeld moet de geldende beperkingen die gelden voor het hele traject aangegeven worden; ; Nullable: True; Default: None; Visible: No|
|EINDLINKEROEVER                     |TEXT(255,0,0)         |PNH; Eind Linker Oever; ; Nullable: True; Default: None; Visible: No|
|EINDRECHTEROEVER                    |TEXT(255,0,0)         |PNH; Eind Rechter Oever; ; Nullable: True; Default: None; Visible: No|
|JAARAANLEG                          |SHORT(0,5,0)          |PNH; Is het jaar van aanleg van de vaarweg; ; Nullable: True; Default: None; Visible: No|
|LENGTELINKEROEVER                   |FLOAT(0,25,10)        |PNH; Lengte linkeroever (m); ; Nullable: True; Default: None; Visible: Yes|
|LENGTERECHTEROEVER                  |FLOAT(0,25,10)        |PNH; Lengte rechteroever (m); ; Nullable: True; Default: None; Visible: Yes|
|STREEFBEELD                         |TEXT(255,0,0)         |PNH; Concrete visuele doelstelling; ; Nullable: True; Default: None; Visible: No|
|VOLDOET                             |SHORT(0,1,0)          |PNH; Geeft aan als de vaarweg voldoet aan het streefbeeld omschrijving; ; Nullable: True; Default: None; Visible: No|
|CEMTKLASSE                          |TEXT(255,0,0)         |PNH; CEMTKLASSE object; keuzelijst [CEMT_KLASSE]; Nullable: True; Default: None; Visible: No|
|MAATGEVENDSCHIP                     |TEXT(255,0,0)         |PNH; MAATGEVENDSCHIP waarde; keuzelijst [MAATGEVEND_SCHIP]; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |TEXT(255,0,0)         |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |TEXT(255,0,0)         |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)           |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)          |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)           |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry              |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                        |DOUBLE(0,0,0)         |PNH; Omtrek in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|SHAPE_Area                          |DOUBLE(0,0,0)         |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|OMTREK                              |DOUBLE(0,0,0)         |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|
|OPPERVLAKTE                         |DOUBLE(0,0,0)         |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Area; ; Nullable: False; Default: None; Visible: Yes|
|GEBIEDSCONTRACTREGIO                |TEXT(255,0,0)         |PNH; Verwijzende sleutel naar gebiedscontractregio_v (simpel); keuzelijst [GCR_NAAM]; Nullable: True; Default: None; Visible: Yes|

***
