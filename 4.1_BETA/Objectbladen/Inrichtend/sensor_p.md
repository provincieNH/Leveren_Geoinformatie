## AREAALDATA.sensor_p

$ Feature dataset: Inrichtend

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Apparaat voor de meting van een fysieke grootheid (bijv. temperatuur, licht, druk, elektriciteit). __LET OP:__ Snelheids camera's/roodlicht camera's zijn niet van de Provincie en worden NIET geregistreerd.

***

|KOLOM                               |TYPE          	      |DEFINITIE|
|------                              |----          	      |-----    |
|OBJECTID                            |OID(38,0,0)             |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None|
|GLOBALID                            |GlobalID(38,0,0)        |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None|
|AD_ID                               |String(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None|
|GISIB_ID                            |Integer(0,10,0)         |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None|
|IDENTIFICATIE                       |String(255,0,0)         |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)         |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|STATUS                              |String(10,0,0)          |BGT; BGT status van het object; keuzelijst [status]; Nullable: False; Default: bestaand|
|OBJECTBEGINTIJD                     |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|RELATIEVEHOOGTELIGGING              |SmallInteger(0,10,0)    |BGT; Aanduiding voor de relatieve hoogte van het object; Nullable: False; Default: 0|
|BEHEERDER                           |String(255,0,0)         |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None|
|ONDERHOUDER                         |String(255,0,0)         |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None|
|EIGENAAR                            |String(255,0,0)         |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None|
|BRONHOUDER                          |String(5,0,0)           |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None|
|TYPESPEC                            |String(255,0,0)         |PNH; Nadere typering van het object; keuzelijst [typeSpecSNSPunt]; Nullable: True; Default: None|
|BGTPLUSTYPE                         |String(50,0,0)          |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeSNSPunt]; Nullable: False; Default: None|
|DATUMPLAATSING                      |Date(8,0,0)             |PNH; Datum plaatsing; Nullable: True|
|FABRIKANTTYPECODE                   |String(255,0,0)         |PNH; Fabrikanttypecode; keuzelijst [FABRIKANT_TYPECODE]; Nullable: True; Default: None|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)    |PNH; Levensverwachting; Nullable: True; Default: None|
|PLANJAAR                            |SmallInteger(0,10,0)    |PNH; Planjaar; Nullable: True|
|TOPDESK_ID                          |String(255,0,0)         |PNH; Verwijzing naar ObjectID TOPdesk ; Nullable: True; Default: None|
|MATERIAALTYPE                       |String(255,0,0)         |PNH; Materiaalkeuze; keuzelijst [MATERIAALTYPE] ; Nullable: True; Default: None|
|ZIJDE                               |String(255,0,0)         |PNH; Zijde; keuzelijst [ZIJDE] ; Nullable: True; Default: None|
|HECTOMETER                          |String(255,0,0)         |PNH; Hectometrering; Nullable: True; Default: None|
|HOOGTE                              |Float(0,10,1)           |PNH; Hoogte in meters, 1 decimaal; Nullable: True; Default: None|
|HECTOMETER                          |String(255,0,0)         |PNH; Hectometrering; Nullable: True; Default: None|
|DETECTIENUMMER                      |String(255,0,0)         |PNH; Bestaat over het algemeen uit een hoofdletter, gevolgd door een cijfer (combinatie) met eventueel een decimaal die als punt wordt weergegeven. Voorbeeld: D2.1 of DM1; Nullable: True; Default: None|
|UITLEGGERPORTAAL                    |String(255,0,0)         |PNH; FK naar uitleggerPortaal_l; als camera of schemerschakelaar daarop bevestigd is; Nullable: True; Default: None|
|ELEKTRICITEITSKABEL                 |String(255,0,0)         |PNH; FK naar electriciteitskabel_l; Nullable: True; Default: None|
|PAAL                                |String(255,0,0)         |PNH; FK naar mastDraagconstructie_p; Nullable: True; Default: None|
|INNETWERK                           |String(255,0,0)         |PNH; FK naar utiliteitsNet_tbl; Nullable: True; Default: None|
|INONDERZOEK                         |String(1,0,0)           |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible:No|
|TIJDSTIPREGISTRATIE                 |Date(8,0,0)             |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|EINDREGISTRATIE                     |Date(8,0,0)             |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|LV_PUBLICATIEDATUM                  |Date(8,0,0)             |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|BERICHT_ID                          |String(128,0,0)         |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|DATALEVERANCIER                     |String(255,0,0)         |PNH; Leverancier van de data; Nullable: True; Default: None|
|CREATED_USER                        |String(255,0,0)         |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)             |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)          |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)             |PNH; Datum van de laatste mutatie; Nullable: True|
|SHAPE                               |Geometry(0,0,0)         |PNH; Punt|


***
