## AREAALDATA.terugkeervoorziening_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.2
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

***

|__KOLOM__                           |__TYPE (length, precision, scale)__          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----          	                           |-----    |
|OBJECTID                            |OID(38,0,0)                                  |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)                             |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: No|
|AD_ID                               |String(255,0,0)                              |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None|
|FAUNAVOORZIENING                    |String(255,0,0)                              |PNH; Verwijzende sleutel naar faunavoorziening_v (simpel); ; Nullable: True; Default: None|
|CREATED_USER                        |String(255,0,0)                              |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)                                  |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)                               |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)                                  |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry(0,0,0)                              |PNH; Lijn; ; Nullable: True; Default: None; Visible: No|


***
