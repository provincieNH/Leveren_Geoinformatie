## AREAALDATA.halte_v

*Feature dataset: Functioneel*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH/NDOV
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Vlak
* __Definitie:__ Het geheel van objecten behorende bij een stopplaats van een autobus. (Integraal Gegevens Model Ideaal Areaal 1.2). STOPPLACE in NDOV terminologie
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ Halte
* __Mapping_NTA8035:__ bs:SpatialRegion

![Halte illustratie](D:\git\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.3d4\Objectbladen\08_Haltes\halte.png)

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__| (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                |-----    |
|OBJECTID                            |OID(38,0,0)         |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)    |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |TEXT(255,0,0)       |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)        |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)       |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.html); Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |DATE(8,0,0)         |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)         |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|BEHEERDER                           |TEXT(255,0,0)       |PNH; Beheerder van het object; keuzelijst [BEHEERDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEERDER.html); Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)       |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ONDERHOUDER.html); Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |TEXT(255,0,0)       |PNH; Eigenaar van het object; keuzelijst [INSTANTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/INSTANTIE.html); Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |TEXT(255,0,0)       |PNH; Nadere typering van het object; keuzelijst [typeSpecHLT](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecHLT.html); Nullable: True; Default: None; Visible: Yes|
|NAAM                                |TEXT(255,0,0)       |PNH; Naam van de halte; ; Nullable: True; Default: None; Visible: Yes|
|WEGNAAM                             |TEXT(255,0,0)       |PNH; Naam vd Weg; ; Nullable: True; Default: None; Visible: Yes|
|WEGNUMMER                           |TEXT(255,0,0)       |PNH; Nummer vd Weg; ; Nullable: True; Default: None; Visible: Yes|
|GEMEENTE                            |TEXT(255,0,0)       |PNH; Gemeentenaam; keuzelijst [GEMEENTE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/GEMEENTE.html); Nullable: True; Default: None; Visible: No|
|HALTENUMMER                         |TEXT(255,0,0)       |PNH; Identificatienummer van de Halte. Let op: Het landelijk unieke nummer van NDOV staat bij Perron; ; Nullable: True; Default: None; Visible: Yes|
|PROJECT                             |TEXT(1,0,0)         |PNH; Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNeeOnbekend.html); Nullable: True; Default: O; Visible: No|
|SUBSIDIEPROJECT                     |TEXT(255,0,0)       |PNH; Naam van het subsidieproject voor aanleg; ; Nullable: True; Default: None; Visible: No|
|HALTEKOM                            |TEXT(1,0,0)         |PNH; Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNeeOnbekend.html); Nullable: False; Default: O; Visible: No|
|ZONNEPANEEL                         |TEXT(1,0,0)         |PNH; Zonnepaneel aanwezig; keuzelijst [jaNeeOnbekend](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNeeOnbekend.html); Nullable: True; Default: None; Visible: Yes|
|ZITMEUBEL                           |TEXT(255,0,0)       |PNH; Type zitmeubel vd Halte; keuzelijst [ZITMEUBEL](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ZITMEUBEL.html); Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDSOVEREENKOMST              |TEXT(255,0,0)       |PNH; Verwijzing naar de Onderhoud overeenkomst (documentnr, locatie e.d.); ; Nullable: True; Default: None; Visible: No|
|FOTO                                |TEXT(255,0,0)       |PNH; Verwijzing naar naam/locatie van een foto vd Halte; ; Nullable: True; Default: None; Visible: No|
|ELEKTROTECHN_TEKENING               |TEXT(255,0,0)       |PNH; Verwijzing naar naam/locatie van een elektrotechnische tekening vd Halte; ; Nullable: True; Default: None; Visible: No|
|WOONPLAATS                          |TEXT(255,0,0)       |PNH; Gemeentenaam; ; Nullable: True; Default: None; Visible: No|
|STATUS_HALTE                        |TEXT(255,0,0)       |PNH; Status van de halte: is deze in gebruik of niet; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |TEXT(255,0,0)       |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |TEXT(255,0,0)       |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |TEXT(255,0,0)       |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|CREATED_DATE                        |DATE(8,0,0)         |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)        |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)         |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry            |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                        |DOUBLE(0,0,0)       |PNH; Omtrek in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|SHAPE_Area                          |DOUBLE(0,0,0)       |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|OMTREK                              |DOUBLE(0,0,0)       |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|
|OPPERVLAKTE                         |DOUBLE(0,0,0)       |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Area; ; Nullable: False; Default: None; Visible: Yes|
|CONCESSIEVERLENER                   |TEXT(255,0,0)       |PNH; Verwijzende sleutel naar concessieverlener_tbl (simpel); ; Nullable: True; Default: None; Visible: No|
|TRAJECT                             |TEXT(255,0,0)       |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/TRAJECT_NAAM.html); Nullable: True; Default: None; Visible: Yes|

***
