## AREAALDATA.perron_v

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 7,5 cm
* __Geometrie:__ Vlak
* __Definitie:__ Kleinste functioneel onafhankelijk stuk van een NEN 3610 Weg met gelijkblijvende, homogene eigenschappen en relaties en primair bedoeld voor gebruik door weg-, spoor- en vliegverkeer te land. __LET OP:__ In dit objecttype worden een kopie van wegdeel_v met BGTPlustype Voetpad opgenomen die als perron bij een bushalte in gebruik is. ![Perron illustratie](c:\git\bu_geodata_beheer_43d4\gereedschap\documentatie\areaaldata_datamodel\4.3d4\Objectbladen\08_Haltes\perron.jpg)
* __Mapping_BGT:__ wegdeel_v
* __Mapping_Gisib:__ Perron
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                           |__TYPE (length, precision, scale)__       |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----          	                        |-----    |
|OBJECTID                            |OID(38,0,0)                               |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)                          |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |TEXT(255,0,0)                             |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)                             |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |DATE(8,0,0)                               |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)                               |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Visible: Yes|
|RELATIEVEHOOGTELIGGING              |SHORT(0,5,0)                              |BGT; Aanduiding voor de relatieve hoogte van het object;  ;Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                           |TEXT(255,0,0)                             |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)                             |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: No|
|EIGENAAR                            |TEXT(255,0,0)                             |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: No|
|PERRONIDENTIFICATIE                 |TEXT(255,0,0)                             |PNH; Halte identificatie conform NDOV QUAY; ; Nullable: True; Default: None; Visible: No|
|VERLICHTING_AANW                    |TEXT(1,0,0)                               |PNH; Aanwezigheid van verlichting; keuzelijst [jaNee]; Nullable: False; Default: N; Visible: No|
|TOV                                 |TEXT(1,0,0)                               |PNH; Voldoet aan richtlijnen TOV : Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible: No|
|GLADHEIDSBESTRIJDING                |TEXT(1,0,0)                               |PNH; Gladheidsbestrijding uitgevoerd; keuzelijst [jaNeeOnbekend]; Nullable: False; Default: None; Visible: No|
|GLADHEIDSBESTRIJDING_PARTIJ         |TEXT(255,0,0)                             |PNH; Naam van de uitvoerende organisatie Gladheidsbestrijding; ; Nullable: True; Default: None; Visible: No|
|VERWARMING_AANW                     |TEXT(1,0,0)                               |PNH; Verwarming aanwezig : Ja/Nee; keuzelijst [jaNeeOnbekend]; Nullable: False; Default: N; Visible: No|
|MATERIAALTYPE                       |TEXT(20,0,0)                              |PNH; Materiaaltype; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None; Visible: No|
|BLINDEGELEIDESTR_AANW               |TEXT(1,0,0)                               |PNH; Blindegeleidestrook aanwezig : Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible: No|
|HOOGTE                              |FLOAT(0,10,2)                             |PNH; Hoogte van het instappunt van het perron in meters, 2 decimalen; ; Nullable: True; Visible: Yes|
|LENGTE_VLAK                         |FLOAT(0,10,2)                             |PNH; Lengte van de voorkant van het perron in meters, scriptmatig bepaald; ; Nullable: True; Visible: Yes|
|BREEDTE                             |FLOAT(0,10,2)                             |PNH; Breedte in Meters, 2 decimalen; ; Nullable: True; Visible: No|
|HEKWERK_AANW                        |TEXT(1,0,0)                               |PNH; Hekwerk aanwezig : Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible: No|
|HALTEPAAL_AANW                      |TEXT(1,0,0)                               |PNH; Haltepaal aanwezig : Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible: No|
|AANPASSING_VISUEEL_BEPERKTEN        |TEXT(1,0,0)                               |PNH; Aanpassing visueel beperkten; keuzelijst [jaNeeOnbekend]; Nullable: False; Default: None; Visible: No|
|MARKERING_PERRONRAND                |TEXT(1,0,0)                               |PNH; Markering perronrand; keuzelijst [jaNeeOnbekend]; Nullable: False; Default: None; Visible: No|
|HALTE                               |TEXT(255,0,0)                             |PNH; Verwijzende sleutel naar halte_v (simpel); ; Nullable: True; Default: None; Visible: No|
|TRAJECT                             |TEXT(255,0,0)                             |PNH; Verwijzende sleutel naar traject_v (simpel); ; Nullable: True; Default: None; Visible: Yes|
|PAAL                                |TEXT(255,0,0)                             |PNH; Verwijzende sleutel naar paalDraagconstructie_p (simpel); ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |TEXT(255,0,0)                             |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |TEXT(255,0,0)                             |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|CREATED_USER                        |TEXT(255,0,0)                             |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)                               |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)                              |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)                               |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Visible: No|
|SHAPE                               |Geometry(0,0,0)                           |PNH; Vlak; ; Nullable: False; Default: None; Visible: Yes|
|SHAPE_Length                        |DOUBLE(0,0,0)                             |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld; ; Nullable: False; Default: None; Visible: Yes|
|SHAPE_Area                          |DOUBLE(0,0,0)                             |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld; ; Nullable: False; Default: None; Visible: Yes|


***
