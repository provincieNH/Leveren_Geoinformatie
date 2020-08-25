## AREAALDATA.perron_v

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 7,5 cm
* __Geometrie:__ Vlak
* __Definitie:__ Kleinste functioneel onafhankelijk stuk van een NEN 3610 Weg met gelijkblijvende, homogene eigenschappen en relaties en primair bedoeld voor gebruik door weg-, spoor- en vliegverkeer te land. __LET OP:__ In dit objecttype worden een kopie van wegdeel_v met BGTPlustype Voetpad opgenomen die als perron bij een bushalte in gebruik is. ![Perron illustratie](D:\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.2d3\Objectbladen\08_Haltes\perron.jpg)
* __Mapping_BGT:__ wegdeel_v
* __Mapping_Gisib:__ Perron
***

|__KOLOM__                           |__TYPE (length, precision, scale)__       |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----          	                        |-----    |
|OBJECTID                            |OID(38,0,0)                               |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)                          |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: No|
|AD_ID                               |String(255,0,0)                           |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|VERWERKINGSSTATUS                   |String(255,0,0)                           |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.html); Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)                               |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)                               |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Visible: Yes|
|RELATIEVEHOOGTELIGGING              |SmallInteger(0,5,0)                       |BGT; Aanduiding voor de relatieve hoogte van het object;  ;Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                           |String(255,0,0)                           |PNH; Beheerder van het object; keuzelijst [BEHEERDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEERDER.html); Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |String(255,0,0)                           |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ONDERHOUDER.html); Nullable: True; Default: None; Visible: No|
|EIGENAAR                            |String(255,0,0)                           |PNH; Eigenaar van het object; keuzelijst [INSTANTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/INSTANTIE.html); Nullable: True; Default: None; Visible: No|
|PERRONIDENTIFICATIE                 |String(255,0,0)                           |PNH; Halte identificatie conform NDOV QUAY; ; Nullable: True; Default: None; Visible: No|
|VERLICHTING_AANW                    |String(1,0,0)                             |PNH; Aanwezigheid van verlichting; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.html); Nullable: False; Default: N; Visible: No|
|TOV                                 |String(1,0,0)                             |PNH; Voldoet aan richtlijnen TOV : Ja/Nee; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.html); Nullable: False; Default: N; Visible: No|
|GLADHEIDSBESTRIJDING                |String(1,0,0)                             |PNH; Gladheidsbestrijding uitgevoerd; keuzelijst [jaNeeOnbekend](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNeeOnbekend.html); Nullable: False; Default: None; Visible: No|
|GLADHEIDSBESTRIJDING_PARTIJ         |String(255,0,0)                           |PNH; Naam van de uitvoerende organisatie Gladheidsbestrijding; ; Nullable: True; Default: None; Visible: No|
|VERWARMING_AANW                     |String(1,0,0)                             |PNH; Verwarming aanwezig : Ja/Nee; keuzelijst [jaNeeOnbekend](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNeeOnbekend.html); Nullable: False; Default: N; Visible: No|
|MATERIAALTYPE                       |String(20,0,0)                            |PNH; Materiaaltype; keuzelijst [MATERIAALTYPE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/MATERIAALTYPE.html); Nullable: True; Default: None; Visible: No|
|BLINDEGELEIDESTR_AANW               |String(1,0,0)                             |PNH; Blindegeleidestrook aanwezig : Ja/Nee; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.html); Nullable: False; Default: N; Visible: No|
|HOOGTE                              |Float(0,10,2)                             |PNH; Hoogte van het instappunt van het perron in meters, 2 decimalen; ; Nullable: True; Visible: Yes|
|LENGTE                              |Float(0,10,2)                             |PNH; Lengte van de voorkant van het perron in meters, 2 decimalen; ; Nullable: True; Visible: Yes|
|BREEDTE                             |Float(0,10,2)                             |PNH; Breedte in Meters, 2 decimalen; ; Nullable: True; Visible: No|
|HEKWERK_AANW                        |String(1,0,0)                             |PNH; Hekwerk aanwezig : Ja/Nee; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.html); Nullable: False; Default: N; Visible: No|
|HALTEPAAL_AANW                      |String(1,0,0)                             |PNH; Haltepaal aanwezig : Ja/Nee; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.html); Nullable: False; Default: N; Visible: No|
|AANPASSING_VISUEEL_BEPERKTEN        |String(1,0,0)                             |PNH; Aanpassing visueel beperkten; keuzelijst [jaNeeOnbekend](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNeeOnbekend.html); Nullable: False; Default: None; Visible: No|
|MARKERING_PERRONRAND                |String(1,0,0)                             |PNH; Markering perronrand; keuzelijst [jaNeeOnbekend](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNeeOnbekend.html); Nullable: False; Default: None; Visible: No|
|HALTE                               |String(255,0,0)                           |PNH; Verwijzende sleutel naar halte_v (simpel); ; Nullable: True; Default: None; Visible: No|
|TRAJECT                             |String(255,0,0)                           |PNH; Verwijzende sleutel naar traject_v (simpel); ; Nullable: True; Default: None; Visible: Yes|
|PAAL                                |String(255,0,0)                           |PNH; Verwijzende sleutel naar paalDraagconstructie_p (simpel); ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |String(255,0,0)                           |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |String(255,0,0)                           |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)                               |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)                            |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)                               |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Visible: No|
|SHAPE                               |Geometry(0,0,0)                           |PNH; Vlak; ; Nullable: False; Default: None; Visible: Yes|
|SHAPE_Length                        |Double(0,0,0)                             |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld; ; Nullable: False; Default: None; Visible: Yes|
|SHAPE_Area                          |Double(0,0,0)                             |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld; ; Nullable: False; Default: None; Visible: Yes|


***
