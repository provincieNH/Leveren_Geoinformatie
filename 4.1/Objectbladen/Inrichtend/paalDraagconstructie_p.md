## AREAALDATA.paalDraagconstructie_p

$ Feature dataset: Inrichtend


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Hoge draagconstructie, vervaardigd van metaal, hout, steen of kunststof dat dient om iets te dragen. __LET OP:__ In dit objecttype worden de IMGEO palen geadministreerd die primair een dragende functie hebben, zoals lichtmast, verkeersregelinstallatiepaal, verkeersbordpaal en haltepaal.



***

|KOLOM                               |TYPE          	       |DEFINITIE|
|------                         	 |----          	       |-----    |
|OBJECTID                            |OID(38,0,0)              |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None|
|GLOBALID                            |GlobalID(38,0,0)         |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None|
|AD_ID                               |String(255,0,0)          |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None|
|GISIB_ID                            |Integer(0,10,0)          |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None|
|BGTPLUSTYPE                         |String(50,0,0)           |PNH; Nadere type omschrijving in de BGT; keuzelijst [typePAL]; Nullable: False; Default: None|
|IDENTIFICATIE                       |String(255,0,0)          |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)          |BGT; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|STATUS                              |String(10,0,0)           |BGT; BGT status van het object; keuzelijst [status]; Nullable: False; Default: bestaand|
|OBJECTBEGINTIJD                     |Date(8,0,0)              |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)              |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|RELATIEVEHOOGTELIGGING              |SmallInteger(0,10,0)     |BGT; Aanduiding voor de relatieve hoogte van het object; Nullable: False; Default: 0|
|BEHEERDER                           |String(255,0,0)          |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None|
|ONDERHOUDER                         |String(255,0,0)          |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None|
|EIGENAAR                            |String(255,0,0)          |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None|
|BRONHOUDER                          |String(5,0,0)            |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None|
|TYPESPEC                            |String(255,0,0)          |PNH; Nadere typering van het object; keuzelijst [typeSpecPALDraagconstructie]; Nullable: True; Default: None|
|FABRIKANTTYPECODE                   |String(255,0,0)          |PNH; Fabrikanttypecode; keuzelijst [FABRIKANT_TYPECODE]; Nullable: True; Default: None|
|MATERIAALTYPE                       |String(20,0,0)           |PNH; Type materiaal; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None|
|HECTOMETER                          |String(255,0,0)          |PNH; Hectometrering; Nullable: True; Default: None|
|AANTALLUIKEN                        |SmallInteger(0,10,0)     |PNH; Aantal luiken; Nullable: True|
|DATUMGARANTIE                       |Date(8,0,0)              |PNH; Datum en jaartal tot wanneer de garantie geldig is; Nullable: True; Default: None|
|DATUMPLAATSING                      |Date(8,0,0)              |PNH; Datum plaatsing; Nullable: True|
|ELEVATIEHOEK                        |SmallInteger(0,10,0)     |PNH; Hoek van de uithouder indien aanwezig ; Nullable: True|
|HOOGTE                              |Float(0,10,1)            |PNH; Lichtpunt hoogte in meters, 1 decimaal achter de komma; Nullable: True; Default: none|
|LENGTEUITHOUDER1                    |Float(0,25,10)           |PNH; De lengte van de uithouder indien aanwezig in meters, 2 decimalen achter de komma; Nullable: True; Default: none|
|PAALNUMMER                          |String(255,0,0)          |PNH; Paalnummer; Nullable: True; Default: None|
|OPMERKING                           |String(3000,0,0)         |PNH; Extra toelichting; Nullable: True; Default: None|
|RALKLEUR                            |String(30,0,0)           |PNH; De RAL-kleur(en) die gebruikt zijn voor het object. Eerst de kleurcode gevolgd door de naam van de kleur; keuzelijst [RALKLEUR]; Nullable: True; Default: None|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)     |PNH; Levensverwachting; Nullable: True|
|PLANJAAR                            |SmallInteger(0,10,0)     |PNH; Het jaar dat nu gepland staat om item te vervangen; Nullable True; Default: None|
|LENGTEUITHOUDER2                    |Float(0,25,10)           |PNH; De lengte van de uithouder indien aanwezig in meters, 2 decimalen achter de komma; Nullable: True; Default: none|
|INNETWERK                           |String(255,0,0)          |PNH; FK naar utiliteitsNet_tbl; Nullable: True; Default: None
|TRAJECT                             |String(255,0,0)          |PNH; FK naar traject_v; Nullable: True; Default: None|
|UITLEGGERPORTAAL                    |String(255,0,0)          |PNH; FK naar uitleggerPortaal_l; als armatuur daarop is gemonteerd; Nullable: True; Default: None|
|DATALEVERANCIER                     |String(255,0,0)          |PNH; Leverancier van de data; Nullable: True; Default: None|
|INONDERZOEK                         |String(1,0,0)            |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible:No|
|TIJDSTIPREGISTRATIE                 |Date(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|EINDREGISTRATIE                     |Date(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|LV_PUBLICATIEDATUM                  |Date(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|BERICHT_ID                          |String(128,0,0)          |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|CREATED_USER                        |String(255,0,0)          |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)              |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)           |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)              |PNH; Datum van de laatste mutatie; Nullable: True|
|SHAPE                               |Geometry(0,0,0)          |PNH; Punt|


***
