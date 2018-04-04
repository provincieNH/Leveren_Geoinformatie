## AREAALDATA.weginrichtingselement_l

$ Feature dataset: Inrichtend

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH/IMGEO
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ lijn
* __Definitie:__ Een ruimtelijk object dat dient voor de inrichting van de openbare weg. __LET OP:__ Voornamelijk bedoelt om Geleideconstructies te administreren. Molgoten worden als vlak in ondersteunendWegdeel geadministreerd.
Een geleiderail of vangrail is een barrière die naast wegen wordt geplaatst om te voorkomen dat voertuigen de weg in zijdelingse richting verlaten, kantelen of de middenberm doorkruisen

***

|KOLOM                             |TYPE          	         |DEFINITIE|
|------                            |----          	         |-----    |
|OBJECTID                          |OID(38,0,0)              |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None|
|GLOBALID                          |GlobalID(38,0,0)         |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None|
|AD_ID                             |String(255,0,0)          |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None|
|GISIB_ID                          |Integer(0,10,0)          |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None|
|IDENTIFICATIE                     |String(255,0,0)          |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None|
|VERWERKINGSSTATUS                 |String(255,0,0)          |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|STATUS                            |String(10,0,0)           |BGT; BGT status van het object; keuzelijst [status]; Nullable: False; Default: bestaand|
|OBJECTBEGINTIJD                   |Date(8,0,0)              |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                    |Date(8,0,0)              |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|RELATIEVEHOOGTELIGGING            |SmallInteger(0,10,0)     |BGT; Aanduiding voor de relatieve hoogte van het object; Nullable: False; Default: 0|
|BEHEERDER                         |String(255,0,0)          |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None|
|ONDERHOUDER                       |String(255,0,0)          |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None|
|EIGENAAR                          |String(255,0,0)          |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None|
|BRONHOUDER                        |String(5,0,0)            |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None|
|TYPESPEC                          |String(255,0,0)          |PNH; Nadere typering van het object; keuzelijst [typeSpecWGILijn]; Nullable: True; Default: None|
|BGTPLUSTYPE                       |String(50,0,0)           |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeWGILijn]; Nullable: False; Default: None|
|ZIJDE                             |String(10,0,0)           |PNH; Zijde; keuzelijst [ZIJDE]; Nullable: True; Default: None|
|ANTIVERBLINDINGSSC                |String(1,0,0)            |PNH; AntiVerblindingsScherm: Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N|
|BEVESTIGING                       |String(255,0,0)          |PNH; Bevestiging; Nullable: True; Default: None|
|DATUMPLAATSING                    |Date(8,0,0)              |PNH; Datum Plaatsing; Nullable: True|
|OMSCHRIJVING                      |String(255,0,0)          |PNH; Klasse geleiderail (W1-W8); Nullable: True; Default: None|
|FUNDERING                         |String(255,0,0)          |PNH; Fundering; Nullable: True; Default: None|
|HMBEGIN                           |Float(0,25,10)           |PNH; Hectometrering in kilometers; Nullable: True|
|HMEIND                            |Float(0,25,10)           |PNH; Hectometrering in kilometers; Nullable: True|
|HOOGTESCHILD                      |String(30,0,0)           |PNH; Hoogte van het schild: kort 600mm / middel 900mm . Hoog 1200mm; Nullable: True; Default: None|
|MOTORVRIENDELIJK                  |String(1,0,0)            |PNH; MotorVriendelijk: Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N|
|PLANJAAR                          |SmallInteger(0,10,0)     |PNH; Het geplande jaar dat het object vervangen wordt; Nullable: True; Default: None|
|REFLECTOR                         |String(1,0,0)            |PNH; Reflector: Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N|
|RESTLEVENSDUUR                    |SmallInteger(0,10,0)     |PNH; Restlevensduur in maanden; Nullable: True; Default: None
|MATERIAALTYPE                     |String(20,0,0)           |PNH; Materiaalkeuze; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None|
|CEKEUR                            |String(255,0,0)          |PNH; CE-Keurmerk aanwezig; Nullable: True; Default: None|
|FOTO                              |String(255,0,0)          |PNH; Locatie van de foto op de S schijf bij PNH. Deze hoeft niet gevuld te worden door de aannemer. Nullable: True; Default: None|
|FABRIKANT                         |String(255,0,0)          |PNH; Fabrikant; Nullable: True; Default: None|
|TRAJECT                           |String(255,0,0)          |PNH; FK naar traject_v; Nullable: True; Default: None|
|INONDERZOEK                       |String(1,0,0)            |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible:No|
|TIJDSTIPREGISTRATIE               |Date(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|EINDREGISTRATIE                   |Date(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|LV_PUBLICATIEDATUM                |Date(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|BERICHT_ID                        |String(128,0,0)          |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|DATALEVERANCIER                   |String(255,0,0)          |PNH; Leverancier van de data; Nullable: True; Default: None|
|CREATED_USER                      |String(255,0,0)          |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                      |Date(8,0,0)              |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                  |String(50,0,0)           |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                  |Date(8,0,0)              |PNH; Datum van de laatste mutatie; Nullable: True|
|SHAPE                             |Geometry                 |PNH; Lijn|
|SHAPE_Length                      |Double(0,0,0)            |PNH; Lengte in meters, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None|

***
