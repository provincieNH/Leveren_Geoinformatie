## AREAALDATA.wegdeelPerron_v

*Feature dataset: Opdelend*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ BGT
* __Positionele nauwkeurigheid:__ 7,5 cm (NB, groter dan BGT)
* __Geometrie:__ Vlak
* __Definitie:__ Kleinste functioneel onafhankelijk stuk van een NEN 3610 Weg met gelijkblijvende, homogene eigenschappen
en relaties en primair bedoeld voor gebruik door weg-, spoor- en vliegverkeer te land. __LET OP:__ In dit objecttype worden die delen van een BGT Voetpad opgenomen die als perron bij een bushalte in gebruik zijn. 

***

|KOLOM                               |TYPE          	       |DEFINITIE|
|------                              |----          	       |-----    |
|OBJECTID                            |OID(38,0,0)              |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:Yes|
|GLOBALID                            |GlobalID(38,0,0)         |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:No|
|AD_ID                               |String(255,0,0)          |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None; Visible:Yes|
|GISIB_ID                            |Integer(0,10,0)          |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|IDENTIFICATIE                       |String(255,0,0)          |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None; Visible:No|
|VERWERKINGSSTATUS                   |String(255,0,0)          |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible:Yes|
|STATUS                              |String(10,0,0)           |BGT; BGT status van het object; keuzelijst [status]; Nullable: False; Default: bestaand; Visible:No|
|OBJECTBEGINTIJD                     |Date(8,0,0)              |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True; Visible:Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)              |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True; Visible:Yes|
|RELATIEVEHOOGTELIGGING              |SmallInteger(0,10,0)     |BGT; Aanduiding voor de relatieve hoogte van het object; Nullable: False; Default: 0; Visible:Yes|
|BEHEERDER                           |String(255,0,0)          |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible:Yes|
|ONDERHOUDER                         |String(255,0,0)          |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible:No|
|EIGENAAR                            |String(255,0,0)          |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible:No|
|BRONHOUDER                          |String(5,0,0)            |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None; Visible:No|
|FYSIEKVOORKOMEN                     |String(50,0,0)           |BGT; Fysieke omschrijving van het object; keuzelijst [fysiekVoorkomenWGD]; Nullable: False; Default: None; Visible:Yes|
|FUNCTIE                             |String(50,0,0)           |BGT; Functionele omschrijving van het object; keuzelijst [functieWGD]; Nullable: False; Default: None; Visible:No|
|OPTALUD                             |String(1,0,0)            |BGT; Ligt het object op een talud? Ja/Nee/Onbekend; keuzelijst [OPTALUD]; Nullable: False; Default: None; Visible:No|
|PERRONIDENTIFICATIE                 |String(255,0,0)          |PNH; Halte identificatie conform NDOV QUAY; Nullable: True; Default: None; Visible:No|
|VERLICHTING_AANW                    |String(1,0,0)            |PNH; Aanwezigheid van verlichting; keuzelijst [jaNee]; Nullable: False; Default: N; Visible:No|
|TOV                                 |String(1,0,0)            |PNH; Voldoet aan richtlijnen TOV : Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible:No|
|GLADHEIDSBESTRIJDING                |String(1,0,0)            |PNH; Gladheidsbestrijding uitgevoerd; keuzelijst [jaNeeOnbekend]; Nullable: False; Default: None; Visible:No|
|GLADHEIDSBESTRIJDING_PARTIJ         |String(255,0,0)          |PNH; Naam van de uitvoerende organisatie Gladheidsbestrijding; Nullable: True; Default: None; Visible:No|
|VERWARMING_AANW                     |String(1,0,0)            |PNH; Verwarming aanwezig : Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible:No|
|MATERIAALTYPE                       |String(20,0,0)           |PNH; Materiaaltype; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None|
|BLINDEGELEIDESTR_AANW               |String(1,0,0)            |PNH; Blindegeleidestrook aanwezig : Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible:No|
|HOOGTE                              |Float(0,10,2)            |PNH; Hoogte van het instappunt van het perron in meters, 2 decimalen; Nullable: True; Visible:Yes|
|LENGTE                              |Float(0,10,2)            |PNH; Lengte van de voorkant van het perron in meters, 2 decimalen; Nullable: True; Visible:Yes|
|BREEDTE                             |Float(0,10,2)            |PNH; Breedte in Meters, 2 decimalen; Nullable: True; Visible:No|
|HEKWERK_AANW                        |String(1,0,0)            |PNH; Hekwerk aanwezig : Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible:No|
|HALTEPAAL_AANW                      |String(1,0,0)            |PNH; Haltepaal aanwezig : Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible:No|
|AANPASSING_VISUEEL_BEPERKTEN        |String(1,0,0)            |PNH; Aanpassing visueel beperkten; keuzelijst [jaNeeOnbekend]; Nullable: False; Default: None; Visible:No|
|MARKERING_PERRONRAND                |String(1,0,0)            |PNH; Markering perronrand; keuzelijst [jaNeeOnbekend]; Nullable: False; Default: None; Visible:No|
|NIVEAU                              |SmallInteger(0,3,0)      |PNH; ToDo; Nullable: True; Visible:No|
|HALTE                               |String(255,0,0)          |PNH; FK naar halte_v; Nullable: True; Default: None; Visible:No|
|TRAJECT                             |String(255,0,0)          |PNH; FK naar traject_v; Nullable: True; Default: None; Visible:Yes|
|PAAL                                |String(255,0,0)          |PNH; FK naar paalDraagconstructie_p; Nullable: True; Default: None|
|INONDERZOEK                         |String(1,0,0)            |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible:No|
|TIJDSTIPREGISTRATIE                 |Date(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|EINDREGISTRATIE                     |Date(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|LV_PUBLICATIEDATUM                  |Date(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|BERICHT_ID                          |String(128,0,0)          |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer. Nullable: True; Default: None; Visible:No|
|DATALEVERANCIER                     |String(255,0,0)          |PNH; Leverancier van de data; Nullable: True; Default: None; Visible:No|
|CREATED_USER                        |String(255,0,0)          |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None; Visible:No|
|CREATED_DATE                        |Date(8,0,0)              |PNH; Aanmaakdatum; Nullable: True; Visible:No|
|LAST_EDITED_USER                    |String(50,0,0)           |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None; Visible:No|
|LAST_EDITED_DATE                    |Date(8,0,0)              |PNH; Datum van de laatste mutatie; Nullable: True; Visible:No|
|SHAPE                               |Geometry(0,0,0)          |PNH; Vlak; Visible:Yes|
|SHAPE_Length                        |Double(0,0,0)            |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None; Visible:Yes|
|SHAPE_Area                          |Double(0,0,0)            |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None; Visible:Yes|


***
