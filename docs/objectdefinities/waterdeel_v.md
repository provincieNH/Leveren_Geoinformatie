## AREAALDATA.waterdeel_v

*Feature dataset: Opdelend*


* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ BGT
* __Positionele nauwkeurigheid:__ 25 cm
* __Geometrie:__ Vlak
* __Definitie:__ Kleinste functioneel onafhankelijk stukje water met gelijkblijvende, homogene eigenschappen en relaties dat er binnen het objecttype Water van NEN 3610 wordt onderscheiden en dat permanent met water bedekt is. 
* __Mapping_BGT:__ waterdeel_v
* __Mapping_Gisib:__ Waterdeel, Waterloop
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__(oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                            |----          	          |-----    |
|OBJECTID                          |OID(38,0,0)               |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                          |GlobalID(38,0,0)          |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: No|
|AD_ID                             |String(255,0,0)           |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                          |Integer(0,10,0)           |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BGTPLUSTYPE                       |String(50,0,0)            |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeWTD](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeWTD.html); Nullable: False; Default: None; Visible: No|
|IDENTIFICATIE                     |String(255,0,0)           |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|STATUS                            |String(10,0,0)            |BGT; BGT status van het object; keuzelijst [status](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/status.html); Nullable: False; Default: bestaand; Visible: No|
|VERWERKINGSSTATUS                 |String(255,0,0)           |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.html); Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                   |Date(8,0,0)               |PNH; Datum waarop het object voor het eerst volgens het areaaldata datamodel wordt vastgelegd ; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                    |Date(8,0,0)               |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING            |SmallInteger(0,5,0)       |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                         |String(255,0,0)           |PNH; Beheerder van het object; keuzelijst [BEHEERDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEERDER.html); Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                       |String(255,0,0)           |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ONDERHOUDER.html); Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                          |String(255,0,0)           |PNH; Eigenaar van het object; keuzelijst [INSTANTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/INSTANTIE.html); Nullable: True; Default: None; Visible: Yes|
|BRONHOUDER                        |String(5,0,0)             |BGT; De bronhoudercode van het object; keuzelijst [bronhouder](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/bronhouder.html); Nullable: False; Default: None; Visible: No|
|TYPESPEC                          |String(255,0,0)           |PNH; Nadere typering van het object; keuzelijst [typeSpecWTD](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecWTD.html); Nullable: True; Default: None; Visible: Yes|
|BREEDTEINSTEKEN                   |String(255,0,0)           |PNH; Breedte tussen de twee kanten daar waar er een knik is tussen land en slootkant in meters (< 6 m of > 6 m); keuzelijst [BREEDTE_INSTEKEN](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BREEDTE_INSTEKEN.html); Nullable: True; Default: None; Visible: No|
|ZIJDE                             |String(10,0,0)            |PNH; Zijde; keuzelijst [ZIJDE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ZIJDE.html); Nullable: True; Default: None; Visible: No|
|AANLEGJAAR                        |SmallInteger(0,5,0)       |PNH; Aanlegjaar; ; Nullable: True; Default: None; Visible: No|
|BREEDTENATPROFIEL                 |Float(0,25,10)            |PNH; Breedte tussen de twee kanten van het water in centimeters; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                         |String(255,0,0)           |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|GEWENSTEDIEPTE                    |Float(0,25,10)            |PNH; Gewenste diepte van de waterloop in centimeters; ; Nullable: True; Default: None; Visible: Yes|
|HMBEGIN                           |Float(0,25,10)            |PNH; Begin Hectometrering; ; Nullable: True; Default: None; Visible: No|
|HMEIND                            |Float(0,25,10)            |PNH; Eind Hectometrering; ; Nullable: True; Default: None; Visible: No|
|KEURMAAT                          |Float(0,25,10)            |PNH; Minimale breedte volgens het Waterschap in centimeters; ; Nullable: True; Default: None; Visible: No|
|LENGTE                            |Float(0,10,0)             |PNH; Lengte in meters; ; Nullable: True; Default: None; Visible: Yes|
|CAT_WATERLOOP                     |String(255,0,0)           |PNH; Categorie waterloop; keuzelijst [CAT_WATERLOOP](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/CAT_WATERLOOP.html); Nullable: True; Default: None; Visible: No|
|JAAR_PLAATSING_AANLEG_GESCHAT     |String(1,0,0)             |PNH; Jaar plaatsing of aanleg is geschat: ja of nee; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.html); Nullable: True; Default: N; Visible: No|
|BODEMHOOGTE                       |Float(0,25,10)            |PNH; Hoogte t.o.v. NAP; ; Nullable: True; Default: None; Visible: Yes|
|LEVENSVERWACHTING                 |SmallInteger(0,5,0)       |PNH; Levensverwachting; ; Nullable: True; Default: None; Visible: No|
|BIJZONDEREWAARDE                  |String(255,0,0)           |PNH; Indicatie van bijzondere waarde; ; Nullable: True; Default: None; Visible: No|
|OPMERKINGMBTONDERH                |String(255,0,0)           |PNH; Opmerking met betrekking tot het onderhoud; ; Nullable: True; Default: None; Visible: No|
|PEILVAST                          |Float(0,25,10)            |PNH; Vaste peil; ; Nullable: True; Default: None; Visible: No|
|PEILWINTER                        |Float(0,25,10)            |PNH; Winter peil; ; Nullable: True; Default: None; Visible: No|
|PEILZOMER                         |Float(0,25,10)            |PNH; Zomer peil; ; Nullable: True; Default: None; Visible: No|
|PLANJAAR                          |SmallInteger(0,5,0)       |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|VERKANTINGTALUD                   |String(255,0,0)           |PNH; TODO; ; Nullable: True; Default: None; Visible: No|
|WATERBREEDTE                      |Float(0,25,10)            |PNH; Breedte Natte profiel in meters (2 decimalen); ; Nullable: True; Default: None; Visible: No|
|SLOOTVEGETATIE                    |String(1,0,0)             |PNH; Slootvegetatie dient verwerkt te worden: Ja/Nee; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.html); Nullable: True; Default: N; Visible: No|
|WATERDIEPTE                       |Float(0,25,10)            |PNH; TODO; ; Nullable: True; Default: None; Visible: Yes|
|WATERSCHAP                        |String(255,0,0)           |PNH; Naam Waterschap; keuzelijst [WATERSCHAP](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/WATERSCHAP.html); Nullable: True; Default: None; Visible: No|
|VAARWEGDEELTRAJECT                |String(255,0,0)           |PNH; Verwijzende sleutel naar vaarwegdeeltraject_v (simpel); ; Nullable: True; Default: None; Visible: Yes|
|TRAJECT                           |String(255,0,0)           |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/TRAJECT_NAAM.html); Nullable: True; Default: None; Visible: Yes|
|INONDERZOEK                       |String(1,0,0)             |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.html); Nullable: False; Default: N; Visible: No|
|TIJDSTIPREGISTRATIE               |Date(8,0,0)               |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|EINDREGISTRATIE                   |Date(8,0,0)               |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|LV_PUBLICATIEDATUM                |Date(8,0,0)               |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BERICHT_ID                        |String(128,0,0)           |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                   |String(255,0,0)           |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                      |String(255,0,0)           |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                      |Date(8,0,0)               |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                  |String(50,0,0)            |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                  |Date(8,0,0)               |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                             |Geometry(0,0,0)           |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                      |Double(0,0,0)             |PNH; Omtrek in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|SHAPE_Area                        |Double(0,0,0)             |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|OMTREK                            |Double(0,0,0)             |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|
|OPPERVLAKTE                       |Double(0,0,0)             |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Area; ; Nullable: False; Default: None; Visible: Yes|



***
