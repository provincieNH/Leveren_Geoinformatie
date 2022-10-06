## AREAALDATA.overigBouwwerk_v

*Feature dataset: Opdelend*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ BGT
* __Positionele nauwkeurigheid:__ 5 cm
* __Geometrie:__ Vlak
* __Definitie:__ Met de aarde verbonden duurzaam bouwwerk, dat niet valt onder de definities van een pand of kunstwerk. __LET OP:__ De vlakgeometrie van Abri wordt in dit objecttype opgenomen en NIET als puntobject in Straatmeubilair. Ondanks dat dit objecttype in de featuredataset Opdelend zit, hoeven deze objecten niet opdelend te zijn.

***

|KOLOM                              |TYPE (length, precision, scale)          	           |DEFINITIE (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                          	|----          	           |-----    |
|OBJECTID                           |OID(38,0,0)               |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                           |GlobalID(38,0,0)          |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: No|
|AD_ID                              |String(255,0,0)           |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                           |Integer(0,10,0)           |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BGTPLUSTYPE                        |String(50,0,0)            |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeOBWVlak]; Nullable: False; Default: None; Visible: Yes|
|IDENTIFICATIE                      |String(255,0,0)           |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                  |String(255,0,0)           |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|STATUS                             |String(10,0,0)            |BGT; BGT status van het object; keuzelijst [status]; Nullable: False; Default: bestaand; Visible: No|
|OBJECTBEGINTIJD                    |Date(8,0,0)               |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                     |Date(8,0,0)               |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING             |SmallInteger(0,10,0)      |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                          |String(255,0,0)           |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                        |String(255,0,0)           |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                           |String(255,0,0)           |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|BRONHOUDER                         |String(5,0,0)             |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None; Visible: No|
|TYPESPEC                           |String(255,0,0)           |PNH; Nadere typering van het object; keuzelijst [typeSpecOBWVlak]; Nullable: True; Default: None; Visible: Yes|
|FABRIKANT                          |String(255,0,0)           |PNH; Naam vd Fabrikant; ; Nullable: True; Default: None; Visible: No|
|LENGTE                             |Float(0,10,2)             |PNH; Lengte in Meters, 2 decimalen; ; Nullable: True; Default: None; Visible: Yes|
|BREEDTE                            |Float(0,10,2)             |PNH; Breedte in Meters, 2 decimalen; ; Nullable: True; Default: None; Visible: No|
|KWALITEITSNIVEAU                   |String(255,0,0)           |PNH; Kwaliteitsniveau; ; Nullable: True; Default: None; Visible: Yes|
|RECLAME_GEEXPLOITEERD              |String(1,0,0)             |PNH; Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|RECLAME_GEEXPL_ZWARTELIJST         |String(10,0,0)            |PNH; Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|RECLAME_VERLICHTING                |String(1,0,0)             |PNH; Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|ZITMEUBILAIR_AANW                  |String(1,0,0)             |PNH; Zitmeubilair aanwezig Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|VERLICHTING_AANW                   |String(1,0,0)             |PNH; Verlichting aanwezig Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|VERLICHTING_TYPE                   |String(255,0,0)           |PNH; Type verlichting (led/../); ; Nullable: True; Default: None; Visible: No|
|VERLICHTING_FABRIKANT              |String(255,0,0)           |PNH; Naam van de verlichtingsfabrikant; ; Nullable: True; Default: None; Visible: No|
|ZONNEPANEEL                        |String(1,0,0)             |PNH; Zonnepaneel aanwezig Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|HALTE                              |String(255,0,0)           |PNH; FK naar halte_v; ; Nullable: True; Default: None; Visible: No|
|TRAJECT                            |String(255,0,0)           |PNH; FK naar traject_v; keuzelijst [TRAJECT_NAAM] ; Nullable: True; Default: None; Visible: Yes|
|INONDERZOEK                        |String(1,0,0)             |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible: No|
|TIJDSTIPREGISTRATIE                |Date(8,0,0)               |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|EINDREGISTRATIE                    |Date(8,0,0)               |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|LV_PUBLICATIEDATUM                 |Date(8,0,0)               |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BERICHT_ID                         |String(128,0,0)           |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                    |String(255,0,0)           |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                       |String(255,0,0)           |PNH; Naam van gebruiker die de rij heeft aangemaakt; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                       |Date(8,0,0)               |PNH; Aanmaakdatum; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                   |String(50,0,0)            |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                   |Date(8,0,0)               |PNH; Datum van de laatste mutatie; ; Nullable: True; Default: None; Visible: No|
|SHAPE                              |Geometry(0,0,0)           |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                       |Double(0,0,0)             |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld; ; Nullable: False; Default: None; Visible: Yes|
|SHAPE_Area                         |Double(0,0,0)             |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld; ; Nullable: False; Default: None; Visible: Yes|



***
