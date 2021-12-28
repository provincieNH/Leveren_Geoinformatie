## AREAALDATA.weg_l

*Feature dataset: Functioneel*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH, obv script afgeleid uit FCD wegvakken NDW. Wordt maandelijks door PNH ge-updated obv bron: http://opendata.ndw.nu/.
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Lijn
* __Definitie:__ De 'as' van de verschillende wegen zoals tot standgekomen in de iNHi(richtingonafhankelijke trajecten), en volgen de rechter rijbaan. De lijn wordt in de richting van de oplopende hectometrering getekend. Het startpunt is altijd bij de laagste hectometerwaarde. Het eindpunt altijd bij de hoogste. Measure values zijn van toepassing, en zijn gedefinieerd in meters.
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ x
* __Aanwezig in BeheerApp (onder alias)__: Alle BeheerApps als referentielaag - is niet bewerktbaar (wegnummers)
* __Mapping_NTA8035:__ bs:SpatialRegion

***

|__KOLOM__                             |__TYPE (length, precision, scale)__                      |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                |-----    |
|OBJECTID                            |OID(38,0,0)         |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)    |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: No|
|AD_ID                               |TEXT(255,0,0)       |PNH; Uniek identificatienummer voor het object dat verandert bij iedere update. in format 'AD.[GUID]'; ; Nullable: False; Default: None; Visible: Yes|
|BEHEERDER                           |TEXT(255,0,0)       |PNH; Beheerder van het object; keuzelijst [BEHEERDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEERDER.html); Nullable: True; Default: None; Visible: Yes|
|HM_MIN                              |DOUBLE(0,0,0)       |PNH; Begin HM van het traject; ; Nullable: True; Default: None; Visible: Yes|
|HM_MAX                              |DOUBLE(0,0,0)       |PNH; Eind HM van het traject; ; Nullable: True; Default: None; Visible: Yes|
|WEGNR                               |TEXT(25,0,0)        |PNH; Nummer van de weg; ;Nullable: True; Default: None; Visible: Yes|
|OPMERKING                           |TEXT(255,0,0)       |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTBEGINTIJD                     |DATE(8,0,0)         |PNH; Datum waarop het object voor het eerst volgens het areaaldata datamodel wordt vastgelegd ; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)         |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|CREATED_USER                        |TEXT(255,0,0)       |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)         |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry            |PNH; Lijn; ; Nullable: False; Default: None; Visible: Yes|
|SHAPE_Length                        |DOUBLE(0,0,0)       |PNH; Lengte in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|LENGTE                              |DOUBLE(0,0,0)       |PNH; Lengte in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|