## AREAALDATA.waterdeel_v

*Feature dataset: Opdelend*


* __Areaaldata model versie:__ 4.3
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
|GLOBALID                          |GlobalID(38,0,0)          |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                             |TEXT(255,0,0)             |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                          |LONG(0,10,0)              |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BGTPLUSTYPE                       |TEXT(50,0,0)              |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeWTD]; Nullable: False; Default: None; Visible: No|
|IDENTIFICATIE                     |TEXT(255,0,0)             |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|STATUS                            |TEXT(10,0,0)              |BGT; BGT status van het object; keuzelijst [Status]; Nullable: False; Default: bestaand; Visible: No|
|VERWERKINGSSTATUS                 |TEXT(255,0,0)             |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                   |DATE(8,0,0)               |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                    |DATE(8,0,0)               |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING            |SHORT(0,5,0)              |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                         |TEXT(255,0,0)             |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                       |TEXT(255,0,0)             |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                          |TEXT(255,0,0)             |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|BRONHOUDER                        |TEXT(5,0,0)               |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None; Visible: No|
|TYPESPEC                          |TEXT(255,0,0)             |PNH; Nadere typering van het object; keuzelijst [typeSpecWTD]; Nullable: True; Default: None; Visible: Yes|
|BREEDTEINSTEKEN                   |TEXT(255,0,0)             |PNH; Breedte tussen de twee kanten daar waar er een knik is tussen land en slootkant in meters (< 6 m of > 6 m); keuzelijst [BREEDTE_INSTEKEN]; Nullable: True; Default: None; Visible: No|
|ZIJDE                             |TEXT(10,0,0)              |PNH; Zijde; keuzelijst [Zijde]; Nullable: True; Default: None; Visible: No|
|AANLEGJAAR                        |SHORT(0,5,0)              |PNH; Aanlegjaar; ; Nullable: True; Default: None; Visible: No|
|BREEDTENATPROFIEL                 |FLOAT(0,25,10)            |PNH; Breedte tussen de twee kanten van het water in centimeters; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                         |TEXT(255,0,0)             |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|GEWENSTEDIEPTE                    |FLOAT(0,25,10)            |PNH; Gewenste diepte van de waterloop in centimeters; ; Nullable: True; Default: None; Visible: Yes|
|HMBEGIN                           |FLOAT(0,25,10)            |PNH; Begin Hectometrering; ; Nullable: True; Default: None; Visible: No|
|HMEIND                            |FLOAT(0,25,10)            |PNH; Eind Hectometrering; ; Nullable: True; Default: None; Visible: No|
|KEURMAAT                          |FLOAT(0,25,10)            |PNH; Minimale breedte volgens het Waterschap in centimeters; ; Nullable: True; Default: None; Visible: No|
|LENGTE_VLAK                       |FLOAT(0,10,0)             |PNH; Lengte in meters, scriptmatig bepaald obv lengterichting waterdeel; ; Nullable: True; Default: None; Visible: Yes|
|CAT_WATERLOOP                     |TEXT(255,0,0)             |PNH; Categorie waterloop; keuzelijst [CAT_WATERLOOP]; Nullable: True; Default: None; Visible: No|
|JAAR_PLAATSING_AANLEG_GESCHAT     |TEXT(1,0,0)               |PNH; Jaar plaatsing of aanleg is geschat: ja of nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|BODEMHOOGTE                       |FLOAT(0,25,10)            |PNH; Hoogte t.o.v. NAP; ; Nullable: True; Default: None; Visible: Yes|
|LEVENSVERWACHTING                 |SHORT(0,5,0)              |PNH; Levensverwachting; ; Nullable: True; Default: None; Visible: No|
|BIJZONDEREWAARDE                  |TEXT(255,0,0)             |PNH; Indicatie van bijzondere waarde; ; Nullable: True; Default: None; Visible: No|
|PLANJAAR                          |SHORT(0,5,0)              |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|VERKANTINGTALUD                   |TEXT(255,0,0)             |PNH; TODO; ; Nullable: True; Default: None; Visible: No|
|WATERBREEDTE                      |FLOAT(0,25,10)            |PNH; Breedte Natte profiel in meters (2 decimalen); ; Nullable: True; Default: None; Visible: No|
|SLOOTVEGETATIE                    |TEXT(1,0,0)               |PNH; Slootvegetatie dient verwerkt te worden: Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|STREEFPEIL                        |FLOAT(0,25,1)             |PNH; Peil tov NAP in meters, 1 decimaal nauwkeurig; ; Nullable: True; Default: None; Visible: Yes|
|WATERSCHAP                        |TEXT(255,0,0)             |PNH; Naam Waterschap; keuzelijst [WATERSCHAP]; Nullable: True; Default: None; Visible: No|
|VAARWEGDEELTRAJECT                |TEXT(255,0,0)             |PNH; Verwijzende sleutel naar vaarwegdeeltraject_v (simpel); ; Nullable: True; Default: None; Visible: Yes|
|TRAJECT                           |TEXT(255,0,0)             |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM]; Nullable: True; Default: None; Visible: Yes|
|INONDERZOEK                       |TEXT(1,0,0)               |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible: No|
|TIJDSTIPREGISTRATIE               |DATE(8,0,0)               |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|EINDREGISTRATIE                   |DATE(8,0,0)               |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|LV_PUBLICATIEDATUM                |DATE(8,0,0)               |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BERICHT_ID                        |TEXT(128,0,0)             |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                   |TEXT(255,0,0)             |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                      |TEXT(255,0,0)             |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                      |DATE(8,0,0)               |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                  |TEXT(50,0,0)              |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                  |DATE(8,0,0)               |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                             |Geometry(0,0,0)           |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                      |DOUBLE(0,0,0)             |PNH; Omtrek in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|SHAPE_Area                        |DOUBLE(0,0,0)             |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|OMTREK                            |DOUBLE(0,0,0)             |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|
|OPPERVLAKTE                       |DOUBLE(0,0,0)             |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Area; ; Nullable: False; Default: None; Visible: Yes|



***
