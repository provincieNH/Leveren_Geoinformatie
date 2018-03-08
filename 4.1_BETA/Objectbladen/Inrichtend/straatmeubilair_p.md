 ## AREAALDATA.straatmeubilair_p

$ Feature dataset: Inrichtend

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMGEO
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Een ruimtelijk object ter inrichting van de openbare ruimte. __LET OP:__ in afwijking op de BGT/IMGEO indeling worden abri's als vlak geadministreerd in overigBouwwerk_v en lichtpunten in straatmeubilairLichtpunt_p.

***

|KOLOM                               |TYPE                    	|DEFINITIE|
|------                              |----          	        |-----    |
|OBJECTID                            |OID(38,0,0)               |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None|
|GLOBALID                            |GlobalID(38,0,0)          |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None|
|AD_ID                               |String(255,0,0)           |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None|
|GISIB_ID                            |Integer(0,10,0)           |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None|
|IDENTIFICATIE                       |String(255,0,0)           |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)           |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|STATUS                              |String(10,0,0)            |BGT; BGT status van het object; keuzelijst [status]; Nullable: False; Default: bestaand|
|OBJECTBEGINTIJD                     |Date(8,0,0)               |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)               |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|RELATIEVEHOOGTELIGGING              |SmallInteger(0,10,0)      |BGT; Aanduiding voor de relatieve hoogte van het object; Nullable: False; Default: 0|
|BEHEERDER                           |String(255,0,0)           |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None|
|ONDERHOUDER                         |String(255,0,0)           |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None|
|EIGENAAR                            |String(255,0,0)           |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None|
|BRONHOUDER                          |String(5,0,0)             |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None|
|TYPESPEC                            |String(255,0,0)           |PNH; Nadere typering van het object; keuzelijst [typeSpecSTM]; Nullable: True; Default: None|
|BGTPLUSTYPE                         |String(50,0,0)            |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeSTM]; Nullable: False; Default: None|
|HOOGTE                              |SmallInteger(0,10,0)      |PNH; Hoogte van het lichtpunt (m; Nullable: True|
|MATERIAALTYPE                       |String(20,0,0)            |PNH; Materiaalkeuze; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None|
|ZIJDE                               |String(10,0,0)            |PNH; Zijde; keuzelijst [ZIJDE]; Nullable: True; Default: None|
|HECTOMETER                          |String(255,0,0)           |PNH; Hectometrering; Nullable: True; Default: None|
|MAXIMALEKRACHT                      |String(255,0,0)           |PNH; Maximale toegestaan kracht op de bolder (Newton? TODO); Nullable: True; Default: None|
|CONTACTPERSOON                      |String(255,0,0)           |PNH; Contactpersoon namens de herdenkers; Nullable: True; Default: None|
|DATUMAANLEG                         |Date(8,0,0)               |PNH; Datum Aanleg; Nullable: True|
|FOTO                                |String(255,0,0)           |PNH; Locatie van de foto op de S schijf bij PNH. Deze hoeft niet gevuld te worden door de aannemer. Nullable: True; Default: None
|LOCATIE                             |String(255,0,0)           |PNH; Zijweg; Nullable: True; Default: None|
|OPMERKING                           |String(255,0,0)           |PNH; Toevoeging van subjectieve informatie met betrekking tot opmerkelijke waarnemingen; Nullable: True; Default: None|
|DATUMGARANTIE                       |Date(8,0,0)               |PNH; Datum en jaartal tot wanneer de garantie geldig is; Nullable: True; Default: None|
|DATUMPLAATSING                      |Date(8,0,0)               |PNH; Datum aanleg; Nullable: True; Default: None|
|JAAR_PLAATSING_AANLEG_GESCHAT       |String(1,0,0)             |PNH; Jaar plaatsing of aanleg is geschat: ja of nee; keuzelijst [jaNee]; Nullable: True; Default: N|
|OMSCHRIJVING                        |String(255,0,0)           |PNH; Extra toelichting; Nullable: True; Default: None|
|MATERIAALTYPE                       |String(20,0,0)            |PNH; Materiaaltype; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None|
|LENGTE                              |SmallInteger(0,10,0)      |PNH; Lengte van de boom (m); Nullable: True|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)      |PNH; Levensverwachting (jaar TODO); Nullable: True|
|PLANJAAR                            |SmallInteger(0,10,0)      |PNH; Planjaar; Nullable: True|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0)      |PNH; Restlevensduur in maanden; Nullable: True; Default: None|
|FABRIKANTTYPECODE                   |String(255,0,0)           |PNH; Fabrikanttypecode; keuzelijst [FABRIKANT_TYPECODE]; Nullable: True; Default: None|
|RECREATIEPLEK                       |String(255,0,0)           |PNH; FK naar recreatieplek_v; Nullable: True; Default: None
|TRAJECT                             |String(255,0,0)           |PNH; FK naar traject_v; Nullable: True; Default: None|
|WEG                                 |GUID(38,0,0)              |PNH; FK naar weg_l; Nullable: True; Default: None|
|GEBIEDSCONTRACTREGIO                |String(255,0,0)           |PNH; FK naar gebiedscontractregio_v; Nullable: True; Default: None|
|INONDERZOEK                         |String(1,0,0)             |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible:No|
|TIJDSTIPREGISTRATIE                 |Date(8,0,0)               |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|EINDREGISTRATIE                     |Date(8,0,0)               |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|LV_PUBLICATIEDATUM                  |Date(8,0,0)               |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|BERICHT_ID                          |String(128,0,0)           |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|DATALEVERANCIER                     |String(255,0,0)           |PNH; Leverancier van de data; Nullable: True; Default: None|
|CREATED_USER                        |String(255,0,0)           |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)               |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)            |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)               |PNH; Datum van de laatste mutatie; Nullable: True|
|SHAPE                               |Geometry(0,0,0)           |PNH; Punt|


***
