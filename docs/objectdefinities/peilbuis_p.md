## AREAALDATA.peilbuis_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Peilbuis tbv opname grondwaterstanden. Samengesteld bestand van verschillende bronnen binnen PNH (o.a. bodem en groen, Areaaldata, Johan Wortelboer) met peilbuisgegevens.
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ x
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__(oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                          	 |----          	     |-----    |
|OBJECTID                            |OID(38,0,0)            |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: No|
|GLOBALID                            |GlobalID(38,0,0)       |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: Yes|
|Peilbuis                            |TEXT(20,0,0)           |PNH; Peilbuisidentificatie afkomstig uit BRO; ;Nullable: False; Default: None; Visible: No|
|Hoogte_cm                           |LONG(0,10,0)           |PNH; Gemeten hoogte in cm; ;Nullable: True; Default: None; Visible: No|
|AantalFilters                       |LONG(0,10,0)           |PNH; Aantal filters in de peilbuis; ;Nullable: True; Default: None; Visible: No|
|Diepte_m                            |LONG(0,10,0)           |PNH; Diepte van de buis in m; ;Nullable: True; Default: None; Visible: No|
|AD_ID                               |TEXT(255,0,0)          |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: No|
|HUIDIGESTATUS                       |TEXT(50,0,0)           |PNH; Huidige status; keuzelijst [ConditionOfFacilityValue](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ConditionOfFacilityValue.html); Nullable: False; Default: functional; Visible: No|
|OBJECTBEGINTIJD                     |DATE(8,0,0)            |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |TEXT(255,0,0)          |PNH; Toevoeging van subjectieve informatie met betrekking tot opmerkelijke waarnemingen; ; Nullable: True; Default: None; Visible: No|
|BEHEERDER                           |TEXT(255,0,0)          |PNH; Beheerder van het object; keuzelijst [BEHEERDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEERDER.html); Nullable: True; Default: None; Visible: No|
|ONDERHOUDER                         |TEXT(255,0,0)          |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ONDERHOUDER.html); Nullable: True; Default: None; Visible: No|
|EIGENAAR                            |TEXT(255,0,0)          |PNH; Eigenaar van het object; keuzelijst [PEILBUISEIGENAREN](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/PEILBUISEIGENAREN.html); Nullable: True; Default: None; Visible: No|
|EISVOORZORGSMAATRBUFFER             |LONG(0,10,0)           |PNH; Wanneer de asset een verhoogd risico/impact op/bij graafschade heeft, kan hier een veiligheidsbuffer in meters worden opgegeven. Wanneer aan de algemene EV-voorwaarden is voldaan en er binnen deze buffer gegraven wordt, ontvangt de grondroerder een eisvoorzorgsmaatregelbrief. Zonder opgaaf gelden algemene uitgangspunten en voorgedefinieerde bufferafstand. Bij een negatieve waarde, als -1, wordt geen brief uitgestuurd; ; Nullable: True; Default: None; Visible: No|
|EVUitleg                            |TEXT(255,0,0)          |PNH; Toelichting op de eisvoorzorgsmaatregel; ;Nullable: True; Default: None; Visible: No|
|IMKL_INNETWORK                      |TEXT(255,0,0)          |PNH; Provincie aanduiding voor het type net, VB: VRI of OVL; keuzelijst [IMKL_InNetwork](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/IMKL_InNetwork.html); Nullable: False; Default: RIOOL; Visible: No|
|APPURTENANCETYPE                    |TEXT(255,0,0)          |PNH; Duiding van het type kabel of leidingelement, danwel appendage of appurtenance. Let op dat het gekozen appurtenancetype onderdeel uit maakt van het betreffende utilitynetworktype; keuzelijst [typeSpecLDE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecLDE.html); Nullable: False; Default: None; Visible: No|
|CREATED_USER                        |TEXT(255,0,0)          |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)            |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)           |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)            |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|       
|TYPESPEC                            |TEXT(10,0,0)           |PNH; Nadere typering van het object; keuzelijst [typeSpecPBU](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecPBU.html); Nullable: True; Default: None; Visible: Yes|
|JAARAANLEG                          |LONG(255,0,0)          |PNH; Jaar waarin de peilbuis is aangelegd; ;Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |TEXT(255,0,0)          |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry(0,0,0)        |PNH; Punt; ; Nullable: False; Default: None; Visible: No|

***
