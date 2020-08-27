## AREAALDATA.vtaInspectie_tbl

*Feature dataset: -*


* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Geen
* __Definitie:__ Wettelijk verplichte inspectie van de veiligheid van bomen
* __Mapping_NTA8035:__ bs:InformationObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                |-----    |
|VERWERKINGSSTATUS                   |String(255,0,0)     |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.html); Nullable: False; Default: Nieuw; Visible: Yes|
|DATUM                               |Date(8,0,0)         |PNH; Datum Inspectie; ; Nullable: True; Default: None; Visible: No|
|INSPECTEUR                          |String(255,0,0)     |PNH; Naam van de Inspecteur; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |String(3000,0,0)    |PNH; Extra toelichting; ; Nullable: True; Default: None; Visible: No|
|OPMERKING2                          |String(3000,0,0)    |PNH; Extra toelichting m.b.t. kroonschade etc; ; Nullable: True; Default: None; Visible: No|
|VTA_GEBREK                          |String(255,0,0)     |PNH; Betreft visueel waarneembare kenmerken die (mogelijk) een negatieve invloed hebben op de boomveiligheid; keuzelijst [VTA_GEBREK](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VTA_GEBREK.html); Nullable: True; Default: None; Visible: No|
|VTA_HERKEURING                      |String(255,0,0)     |PNH; Gewenst moment of termijn van de volgende boomveiligheidscontrole; keuzelijst [VTA_HERKEURING](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VTA_HERKEURING.html); Nullable: True; Default: None; Visible: No|
|VTA_NADER_TECHN_ONDERZOEK           |String(255,0,0)     |PNH; Uitvoeren van Nader Technisch Onderzoek door bijv. de inzet van specialistische meetapparatuur of onderzoek op hoogte; keuzelijst [VTA_NTO](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VTA_NTO.html); Nullable: True; Default: None; Visible: No|
|VTA_FLORA                           |String(255,0,0)     |PNH; Aanwezigheid nesten, vleermuizen e.d.; ; Nullable: True; Default: None; Visible: No|
|VTA_URGENTIE_NTO                    |String(255,0,0)     |PNH; Gewenst moment of termijn van de NTO (e.e.a. houdt verband met de aard en omvang van de geconstateerde gebreken en de standplaats); keuzelijst [VTA_NTO_URGENTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VTA_NTO_URGENTIE.html); Nullable: True; Default: None; Visible: No|
|VTA_RISICO                          |String(255,0,0)     |PNH; Klasse van het risico wat een gebrek met zich mee kan brengen; keuzelijst [VTA_RISICO](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VTA_RISICO.html); Nullable: True; Default: None; Visible: No|
|BOOM                                |String(255,0,0)     |PNH; Verwijzende sleutel naar vegetatieObject_p (simpel); ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                       |String(255,0,0)     |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|OBJECTID                            |OID(38,0,0)         |PNH; Interne ID ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)    |PNH; Global Unique Identifier; ; Nullable: False; Default: None; Visible: No|
|GISIB_ID                            |Integer(0,10,0)     |PNH; ID beheer openbare ruimte (GISIB); ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |String(255,0,0)     |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|AD_ID                               |String(255,0,0)     |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; ; Nullable: False; Default: None; Visible: Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)         |PNH; Datum waarop het object voor het eerst volgens het areaaldata datamodel wordt vastgelegd ; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)         |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|CREATED_USER                        |String(255,0,0)     |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)         |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)      |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)         |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|

***
