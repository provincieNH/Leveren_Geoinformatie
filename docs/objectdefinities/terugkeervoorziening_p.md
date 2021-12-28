## AREAALDATA.terugkeervoorziening_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ BGT/PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ een voorziening in een raster of geleidingswand waardoor fauna dat aan de wegkant van het raster/de geleidingswand staat weer aan de andere kant van het raster/de geleidingswand kan komen, maar waarbij dezelfde faunasoort aan de niet-wegkant niét het raster/de geleidingswand kan passeren om de weg op te komen.
Een faunaterugkeervoorziening kan geschikt zijn voor één of meerdere faunasoorten. Voorbeelden van faunaterugkeervoorzieningen in raster of geleidingswand zijn:
-	Terugspringvoorzieningen voor reeën (zie afbeelding);
-	Klapluik voor das (zie afbeelding).
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ x
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                           |__TYPE (length, precision, scale)__          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----          	                           |-----    |
|OBJECTID                            |OID(38,0,0)                                  |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)                             |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |TEXT(255,0,0)                                |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None|
|BEHEERDER                           |TEXT(255,0,0)                                |PNH; Beheerder van het object; keuzelijst [BEHEERDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEERDER.html); Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)                                |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ONDERHOUDER.html); Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |TEXT(255,0,0)                                |PNH; Eigenaar van het object; keuzelijst [INSTANTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/INSTANTIE.html); Nullable: True; Default: None; Visible: Yes|
|OPMERKING                           |TEXT(255,0,0)                                |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|FAUNAVOORZIENING                    |TEXT(255,0,0)                                |PNH; Verwijzende sleutel naar faunavoorziening_v (simpel); ; Nullable: True; Default: None|
|CREATED_USER                        |TEXT(255,0,0)                                |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)                                  |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)                                 |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)                                  |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry(0,0,0)                              |PNH; Lijn; ; Nullable: True; Default: None; Visible: No|


***
