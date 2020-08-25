## AREAALDATA.kunstwerkdeel_v

*Feature dataset: Opdelend*


* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ IMGeo BGT 
* __Positionele nauwkeurigheid:__ 5 cm
* __Geometrie:__ Vlak
* __Definitie:__ Onderdeel van een civiel-technisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen met een breedte >30cm.
* __Mapping_BGT:__ kunstwerkdeel_v
* __Mapping_Gisib:__ Stuw, Overig Bouwwerk

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                            |----          	        |-----    |
|OBJECTID                          |OID(38,0,0)             |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                          |GlobalID(38,0,0)        |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: No|
|AD_ID                             |String(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                          |Integer(0,10,0)         |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                     |String(255,0,0)         |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|STATUS                            |String(10,0,0)          |BGT; BGT status van het object; keuzelijst [status](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/status.html); Nullable: False; Default: bestaand; Visible: No|
|VERWERKINGSSTATUS                 |String(255,0,0)         |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.html); Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                   |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                    |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING            |SmallInteger(0,5,0)     |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                         |String(255,0,0)         |PNH; Beheerder van het object; keuzelijst [BEHEERDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEERDER.html); Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                       |String(255,0,0)         |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ONDERHOUDER.html); Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                          |String(255,0,0)         |PNH; Eigenaar van het object; keuzelijst [INSTANTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/INSTANTIE.html); Nullable: True; Default: None; Visible: Yes|
|BRONHOUDER                        |String(5,0,0)           |BGT; De bronhoudercode van het object; keuzelijst [bronhouder](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/bronhouder.html); Nullable: False; Default: None; Visible: No|
|TYPESPEC                          |String(255,0,0)         |PNH; Nadere typering van het object; keuzelijst [typeSpecKWD](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecKWD.html); Nullable: True; Default: None; Visible: Yes|
|BGTPLUSTYPE                       |String(50,0,0)          |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeKWDVlak](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeKWDVlak.html); Nullable: False; Default: None; Visible: No|
|FUNCTIE                           |String(255,0,0)         |PNH; Functie; ; Nullable: True; Default: None; Visible: No|
|AANLEGJAAR                        |SmallInteger(0,4,0)     |PNH; Aanlegjaar; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |String(255,0,0)        |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|FOTO                              |String(255,0,0)         |PNH; Locatie van de foto op de S schijf bij PNH. Deze hoeft niet gevuld te worden door de aannemer; ; Nullable: True; Default: None; Visible: No|
|HECTOMETER                        |String(255,0,0)         |PNH; Hectometrering; ; Nullable: True; Default: None; Visible: Yes|
|KERENDEHOOGTE                     |Float(0,25,10)          |PNH; Bovenkant van de constructie tov NAP; ; Nullable: True; Default: None; Visible: Yes|
|OPMERKINGMBTONDERH                |String(255,0,0)         |PNH; Opmerking met betrekking tot het onderhoud; ; Nullable: True; Default: None; Visible: No|
|PLANJAAR                          |SmallInteger(0,5,0)     |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|VASTOFBEWEEGBAAR                  |String(255,0,0)         |PNH; Vaste of Beweegbare stuw; ; Nullable: True; Default: None; Visible: No|
|MATERIAALTYPE                     |String(20,0,0)          |PNH; Type materiaal; keuzelijst [MATERIAALTYPE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/MATERIAALTYPE.html); Nullable: True; Default: None; Visible: Yes|
|BESTEMMING                        |String(255,0,0)         |PNH; Bestemming; ; Nullable: True; Default: None; Visible: No|
|CONSTRUCTIE                       |String(255,0,0)         |PNH; Constructie TODO; ; Nullable: True; Default: None; Visible: No|
|HOOGTEBOVENNAP                    |Float(0,25,10)          |PNH; HoogteBoven NAP (cm?) TODO; ; Nullable: True; Default: None; Visible: Yes|
|LOOPDEK                           |String(255,0,0)         |PNH; Loopdek Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNeeOnbekend.html); Nullable: True; Default: O; Visible: No|
|TRAJECT                           |String(255,0,0)         |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/TRAJECT_NAAM.html); Nullable: True; Default: None; Visible: Yes|
|INONDERZOEK                       |String(1,0,0)           |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.html); Nullable: False; Default: N; Visible: No|
|TIJDSTIPREGISTRATIE               |Date(8,0,0)             |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|EINDREGISTRATIE                   |Date(8,0,0)             |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|LV_PUBLICATIEDATUM                |Date(8,0,0)             |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BERICHT_ID                        |String(128,0,0)         |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                   |String(255,0,0)         |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                      |String(255,0,0)         |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                      |Date(8,0,0)             |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                  |String(50,0,0)          |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                  |Date(8,0,0)             |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                             |Geometry(0,0,0)         |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                      |Double(0,0,0)           |PNH; Omtrek in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|SHAPE_Area                        |Double(0,0,0)           |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|OMTREK                            |Double(0,0,0)           |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|
|OPPERVLAKTE                       |Double(0,0,0)           |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Area; ; Nullable: False; Default: None; Visible: Yes|



***
