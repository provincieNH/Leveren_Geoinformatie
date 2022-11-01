## AREAALDATA.vegetatieObject_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Een opgaande beplanting met een stam en boomkroon. Verschijningsvorm: vrijuit groeiend, geknot of in gesnoeide vorm. Hoogte groter dan 1 meter en/of stamdikte groter dan 5 centimeter

***

|KOLOM                              |TYPE (length, precision, scale)          	          |DEFINITIE (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                          	|----                     |-----    |
|OBJECTID                           |OID(38,0,0)              |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                           |GlobalID(38,0,0)         |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                              |String(255,0,0)          |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                           |Integer(0,10,0)          |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                      |String(255,0,0)          |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                  |String(255,0,0)          |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|STATUS                             |String(10,0,0)           |BGT; BGT status van het object; keuzelijst [status]; Nullable: False; Default: bestaand; Visible: No|
|OBJECTBEGINTIJD                    |Date(8,0,0)              |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                     |Date(8,0,0)              |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING             |SmallInteger(0,10,0)     |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                          |String(255,0,0)          |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                        |String(255,0,0)          |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                           |String(255,0,0)          |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|BRONHOUDER                         |String(5,0,0)            |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None; Visible: No|
|TYPESPEC                           |String(255,0,0)          |PNH; Nadere typering van het object; keuzelijst [typeSpecVGOPunt]; Nullable: True; Default: None; Visible: Yes|
|BGTPLUSTYPE                        |String(50,0,0)           |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeVGOPunt]; Nullable: False; Default: None; Visible: No|
|AFSTANDVERHARDING                  |Float(0,25,10)           |PNH; Afstand tot de verharding in meters, 2 decimalen; ; Nullable: True; Default: None; Visible: Yes|
|BIJZONDERHEID                      |String(255,0,0)          |PNH; TODO; ; Nullable: True; Default: None; Visible: No|
|BOOMSITUERING                      |String(255,0,0)          |PNH; Situering van de boom; keuzelijst [PLANT_SITUERING]; Nullable: True; Default: None; Visible: Yes|
|BOOMSOORT                          |String(255,0,0)          |PNH; Boomsoort; keuzelijst [BOOMSOORT]; Nullable: True; Default: None; Visible: Yes|
|DATUMAANPLANTING                   |Date(8,0,0)              |PNH; Jaar aanplanting; ; Nullable: True; Default: None; Visible: No|
|DATUM_LAATSTE_ONDERH               |Date(8,0,0)              |PNH; Datum laatst onderhoud; ; Nullable: True; Default: None; Visible: No|
|DIAMETER                           |SmallInteger(0,10,0)     |PNH; Diameter op 1.30m; ; Nullable: True; Default: None; Visible: Yes|
|STREEFBEELD                        |String(255,0,0)          |PNH; Concrete visuele doelstelling; ; Nullable: True; Default: None; Visible: No|
|HECTOMETER                         |String(255,0,0)          |PNH; Hectometrering; ; Nullable: True; Default: None; Visible: Yes|
|INSPECTEUR                         |String(255,0,0)          |PNH; Naam van de inspecteur die laatste inspectie heeft uitgevoerd; ; Nullable: True; Default: None; Visible: No|
|DATUM_INSPECTIE                    |Date(8,0,0)              |PNH; Datum laatste inspectie; ; Nullable: True; Default: None; Visible: No|
|MONUMENT                           |String(20,0,0)           |PNH; Monumentale status; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: None; Visible: No|
|OMSCHRIJVING                       |String(255,0,0)          |PNH; Extra toelichting; ; Nullable: True; Default: None; Visible: Yes|
|PLANJAAR                           |SmallInteger(0,10,0)     |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|SNOEIFASE                          |String(255,0,0)          |PNH; Snoeifase; keuzelijst [SNOEIFASE]; Nullable: True; Default: None; Visible: No|
|TERMIJN_UITVOERING                 |String(255,0,0)          |PNH; Termijn waarbinnen de geadviseerde maatregelen uitgevoerd dienen te worden; keuzelijst [TERMIJN_UITVOERING]; Nullable: True; Default: None; Visible: No|
|ZIJDE                              |String(10,0,0)           |PNH; Zijde; keuzelijst [ZIJDE]; Nullable: True; Default: None; Visible: Yes|
|JAAR_PLAATSING_AANLEG_GESCHAT      |String(1,0,0)            |PNH; Jaar plaatsing of aanleg is geschat: Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|TRAJECT                            |String(255,0,0)          |PNH; FK naar traject_v; keuzelijst [TRAJECT_NAAM] ; Nullable: True; Default: None; Visible: Yes|
|INONDERZOEK                        |String(1,0,0)            |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible: No|
|TIJDSTIPREGISTRATIE                |Date(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|EINDREGISTRATIE                    |Date(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|LV_PUBLICATIEDATUM                 |Date(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BERICHT_ID                         |String(128,0,0)          |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                    |String(255,0,0)          |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                       |String(255,0,0)          |PNH; Naam van gebruiker die de rij heeft aangemaakt; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                       |Date(8,0,0)              |PNH; Aanmaakdatum; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                   |String(50,0,0)           |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                   |Date(8,0,0)              |PNH; Datum van de laatste mutatie; ; Nullable: True; Default: None; Visible: No|
|SHAPE                              |Geometry(0,0,0)          |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|


***
