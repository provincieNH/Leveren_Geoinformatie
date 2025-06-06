## AREAALDATA.scheidingGeluidsscherm_l

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ BGT/PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Lijn
* __Definitie:__ Kunstmatig, meestal lineair obstakel met een werende functie. __LET OP:__ Dit is het element niveau van de NEN 2767-4 decompositie van geluidwerende Voorzieningen __EN__ het BGT objecttype.
* __Mapping_BGT:__ scheiding_l
* __Mapping_Gisib:__ Geluidwerende constructie
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----          	       |-----    |
|OBJECTID                            |OID(38,0,0)              |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)         |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |TEXT(255,0,0)            |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)             |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                       |TEXT(255,0,0)            |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)            |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.html); Nullable: False; Default: Nieuw; Visible: Yes|
|STATUS                              |TEXT(10,0,0)             |BGT; BGT status van het object; keuzelijst [Status](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/Status.html); Nullable: False; Default: bestaand; Visible: No|
|OBJECTBEGINTIJD                     |DATE(8,0,0)              |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)              |PNH; Datum waarop het objeconet bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING              |SHORT(0,5,0)             |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                           |TEXT(255,0,0)            |PNH; Beheerder van het object; keuzelijst [BEHEERDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEERDER.html); Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)            |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ONDERHOUDER.html); Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |TEXT(255,0,0)            |PNH; Eigenaar van het object; keuzelijst [INSTANTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/INSTANTIE.html); Nullable: True; Default: None; Visible: Yes|
|BRONHOUDER                          |TEXT(5,0,0)              |BGT; De bronhoudercode van het object; keuzelijst [bronhouder](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/bronhouder.html); Nullable: False; Default: None; Visible: No|
|BGTPLUSTYPE                         |TEXT(50,0,0)             |BGT; Nadere BGT typering van het object; keuzelijst [typeSHDGeluid](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSHDGeluid.html); Nullable: True; Default: geluidsscherm; Visible: No|
|TYPESPEC                            |TEXT(255,0,0)            |PNH; Nadere typering van het object; keuzelijst [typeSpecSHDGeluidscherm](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecSHDGeluidscherm.html); Nullable: True; Default: None; Visible: Yes|
|NAAM                                |TEXT(255,0,0)            |PNH; Naam van het Element. Let op hier is een naamgevings systematiek op van toepassing; ; Nullable: True; Default: None; Visible: Yes|
|KRITISCH                            |TEXT(1,0,0)              |PNH; Kritisch (Ja / Nee); ; Nullable: True; Default: None; Visible: No|
|CONFORMNEN                          |TEXT(1,0,0)              |PNH; Is Element conform NEN ja of nee; ; Nullable: True; Default: None; Visible: No|
|CONDITIESCORE                       |LONG(0,10,0)             |PNH; Conditiescore conform NEN 2767-4; ; Nullable: True; Default: None; Visible: No|
|CONDITIESCORE_DATUM                 |DATE(8,0,0)              |PNH; Datum opname Conditiescore; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |TEXT(255,0,0)            |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|GELUID_VOORZ                        |TEXT(255,0,0)            |PNH; Verwijzende sleutel naar geluidwerendeVoorziening_l (simpel); ; Nullable: True; Default: None; Visible: No|
|HOOGTE                              |Float(0,10,2)            |PNH; Hoogte (m, 2 decimalen), hoogte van het scherm boven maaiveld; ; Nullable: True; Default: None; Visible: Yes|
|DATALEVERANCIER                     |TEXT(255,0,0)            |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|INONDERZOEK                         |TEXT(1,0,0)              |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.html); Nullable: False; Default: N; Visible: No|
|TIJDSTIPREGISTRATIE                 |DATE(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|EINDREGISTRATIE                     |DATE(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|LV_PUBLICATIEDATUM                  |DATE(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BERICHT_ID                          |TEXT(128,0,0)            |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |TEXT(255,0,0)            |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)              |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)             |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)              |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry(0,0,0)          |PNH; Lijn; ; Nullable: False; Default: None; Visible: Yes|
|SHAPE_Length                        |DOUBLE(0,0,0)            |PNH; Lengte in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|LENGTE                              |DOUBLE(0,0,0)            |PNH; Lengte in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|


***
