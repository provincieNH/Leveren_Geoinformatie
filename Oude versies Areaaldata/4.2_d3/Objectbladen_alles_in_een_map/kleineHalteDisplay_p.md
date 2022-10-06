## AREAALDATA.kleinehaltedisplay_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH/IMGEO
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Punt
* __Definitie:__ Kleine halte display: klein scherm dat actuele vertrektijden toont, maar daarnaast ook een 
audiovoorziening voor slechthorenden heefy én een stoplamp waarmee de reiziger in het donker de aandacht van de 
buschauffeur kan trekken. Werkt op zonnecellen.
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ x



***

|__KOLOM__                           |__TYPE (length, precision, scale)__           |__DEFINITIE__(oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                          	 |----          	                            |-----    |
|OBJECTID                            |OID(38,0,0)                                   |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)                              |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: No|
|AD_ID                               |String(255,0,0)                               |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|VERWERKINGSSTATUS                   |String(255,0,0)                               |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|STATUS                              |String(10,0,0)                                |BGT; BGT status van het object; keuzelijst [status]; Nullable: False; Default: bestaand; Visible: No|
|OBJECTBEGINTIJD                     |Date(8,0,0)                                   |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)                                   |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|BEHEERDER                           |String(255,0,0)                               |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |String(255,0,0)                               |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |String(255,0,0)                               |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |String(255,0,0)                               |PNH; Nadere typering van het object; keuzelijst [typeSpecBRD]; Nullable: True; Default: None; Visible: Yes|
|DATUMPLAATSING                      |Date(8,0,0)                                   |PNH; Datum Plaatsing; ; Nullable: True; Default: None; Visible: No|
|HALTE                               |String(255,0,0)                               |PNH; Verwijzende sleutel naar halte_v (simpel); ; Nullable: True; Default: None; Visible: No|
|TRAJECT                             |String(255,0,0)                               |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM]; Nullable: True; Default: None; Visible: Yes|
|HALTECODE                           |String(255,0,0)                               |PNH; Haltecode; ; Nullable: True; Default: None; Visible: Yes|
|HALTENAAM                           |String(255,0,0)                               |PNH; Haltenaam; ; Nullable: True; Default: None; Visible: Yes|
|DHPSERIAL                           |String(255,0,0)                               |PNH; Serial nummer klein halte display; ; Nullable: True; Default: None; Visible: Yes|
|CONTRACTNR                          |String(255,0,0)                               |PNH; Numnmer van het contract; ; Nullable: True; Default: None; Visible: No|
|OVEREENKOMSTNR                      |String(255,0,0)                               |PNH; Numnmer van de overeenkomst; ; Nullable: True; Default: None; Visible: No|
|FACTUURNR                           |String(255,0,0)                               |PNH; Numnmer van de factuur; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |String(255,0,0)                               |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|FOTO                                |String(255,0,0)                               |PNH; Verwijzing naar Foto; ; Nullable: True; Default: None; Visible: Yes|
|FOTO2                               |String(255,0,0)                               |PNH; Verwijzing naar Foto; ; Nullable: True; Default: None; Visible: Yes|
|CREATED_USER                        |String(255,0,0)                               |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)                                   |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)                                |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)                                   |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |String(255,0,0)                               |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry(0,0,0)                               |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|

***
