## AREAALDATA.kleinehaltedisplay_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH/IMGEO
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Punt
* __Definitie:__ Kleine halte display: klein scherm dat actuele vertrektijden toont, maar daarnaast ook een 
audiovoorziening voor slechthorenden heefy én een stoplamp waarmee de reiziger in het donker de aandacht van de 
buschauffeur kan trekken. Werkt op zonnecellen.
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ x
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                           |__TYPE (length, precision, scale)__           |__DEFINITIE__(oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                          	 |----          	                            |-----    |
|OBJECTID                            |OID(38,0,0)                                   |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)                              |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |TEXT(255,0,0)                                 |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)                                 |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.html); Nullable: False; Default: Nieuw; Visible: Yes|
|STATUS                              |TEXT(10,0,0)                                  |BGT; BGT status van het object; keuzelijst [Status](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/Status.html); Nullable: False; Default: bestaand; Visible: No|
|OBJECTBEGINTIJD                     |DATE(8,0,0)                                   |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)                                   |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|BEHEERDER                           |TEXT(255,0,0)                                 |PNH; Beheerder van het object; keuzelijst [BEHEERDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEERDER.html); Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)                                 |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ONDERHOUDER.html); Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |TEXT(255,0,0)                                 |PNH; Eigenaar van het object; keuzelijst [INSTANTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/INSTANTIE.html); Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |TEXT(255,0,0)                                 |PNH; Nadere typering van het object; keuzelijst [typeSpecBRD](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecBRD.html); Nullable: True; Default: None; Visible: Yes|
|DATUMPLAATSING                      |DATE(8,0,0)                                   |PNH; Datum Plaatsing; ; Nullable: True; Default: None; Visible: No|
|HALTE                               |TEXT(255,0,0)                                 |PNH; Verwijzende sleutel naar halte_v (simpel); ; Nullable: True; Default: None; Visible: No|
|TRAJECT                             |TEXT(255,0,0)                                 |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/TRAJECT_NAAM.html); Nullable: True; Default: None; Visible: Yes|
|HALTECODE                           |TEXT(255,0,0)                                 |PNH; Haltecode; ; Nullable: True; Default: None; Visible: Yes|
|HALTENAAM                           |TEXT(255,0,0)                                 |PNH; Haltenaam; ; Nullable: True; Default: None; Visible: Yes|
|DHPSERIAL                           |TEXT(255,0,0)                                 |PNH; Serial nummer klein halte display; ; Nullable: True; Default: None; Visible: Yes|
|CONTRACTNR                          |TEXT(255,0,0)                                 |PNH; Numnmer van het contract; ; Nullable: True; Default: None; Visible: No|
|OVEREENKOMSTNR                      |TEXT(255,0,0)                                 |PNH; Numnmer van de overeenkomst; ; Nullable: True; Default: None; Visible: No|
|FACTUURNR                           |TEXT(255,0,0)                                 |PNH; Numnmer van de factuur; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |TEXT(255,0,0)                                 |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|FOTO                                |TEXT(255,0,0)                                 |PNH; Verwijzing naar Foto; ; Nullable: True; Default: None; Visible: Yes|
|FOTO2                               |TEXT(255,0,0)                                 |PNH; Verwijzing naar Foto; ; Nullable: True; Default: None; Visible: Yes|
|CREATED_USER                        |TEXT(255,0,0)                                 |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)                                   |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)                                  |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)                                   |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |TEXT(255,0,0)                                 |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry(0,0,0)                               |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|

***
