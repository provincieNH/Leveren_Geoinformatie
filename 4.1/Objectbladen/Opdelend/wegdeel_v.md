## AREAALDATA.wegdeel_v

*Feature dataset: Opdelend*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ BGT
* __Positionele nauwkeurigheid:__ 7,5 cm (NB, groter dan BGT)
* __Geometrie:__ Vlak
* __Definitie:__ Kleinste functioneel onafhankelijk stuk van een NEN 3610 Weg met gelijkblijvende, homogene eigenschappen
en relaties en primair bedoeld voor gebruik door weg-, spoor- en vliegverkeer te land.


***

|KOLOM                             |TYPE          	          |DEFINITIE|
|------                            |----          	          |-----    |
|OBJECTID                          |OID(38,0,0)               |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:Yes|
|GLOBALID                          |GlobalID(38,0,0)          |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:No|
|AD_ID                             |String(255,0,0)           |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None; Visible:Yes|
|GISIB_ID                          |Integer(0,10,0)           |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|IDENTIFICATIE                     |String(255,0,0)           |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None; Visible:No|
|VERWERKINGSSTATUS                 |String(255,0,0)           |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible:Yes|
|STATUS                            |String(10,0,0)            |BGT; BGT status van het object; keuzelijst [status]; Nullable: False; Default: bestaand; Visible:No|
|OBJECTBEGINTIJD                   |Date(8,0,0)               |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True; Visible:Yes|
|OBJECTEINDTIJD                    |Date(8,0,0)               |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True; Visible:Yes|
|RELATIEVEHOOGTELIGGING            |SmallInteger(0,10,0)      |BGT; Aanduiding voor de relatieve hoogte van het object; Nullable: False; Default: 0; Visible:Yes|
|BEHEERDER                         |String(255,0,0)           |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible:Yes|
|ONDERHOUDER                       |String(255,0,0)           |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible:No|
|EIGENAAR                          |String(255,0,0)           |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible:No|
|BRONHOUDER                        |String(5,0,0)             |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None; Visible:No|
|TYPESPEC                          |String(255,0,0)           |PNH; Nadere typering van het object; keuzelijst [typeSpecWGD]; Nullable: True; Default: None; Visible:Yes|
|FYSIEKVOORKOMEN                   |String(50,0,0)            |BGT; Fysieke omschrijving van het object; keuzelijst [fysiekVoorkomenWGD]; Nullable: False; Default: None; Visible:Yes|
|FUNCTIE                           |String(50,0,0)            |BGT; Functionele omschrijving van het object; keuzelijst [functieWGD]; Nullable: False; Default: None; Visible:Yes|
|OPTALUD                           |String(1,0,0)             |BGT; Ligt het object op een talud? Ja/Nee/Onbekend. Bij 'Ja', moet er een wegdeelKruin_l geregistreerd zijn; keuzelijst [OPTALUD]; Nullable: False; Default: None; Visible:No|
|BREEDTE                           |Float(0,25,10)            |PNH; Breedte van het wegvakonderdeel (m, 2 decimalen); Nullable: True; Visible:No|
|COMFORT                           |String(255,0,0)           |PNH; Comfort waarde; Nullable: True; Default: None; Visible:No|
|COMFORT_DATE                      |Date(8,0,0)               |PNH; Datum comfort meting; Nullable: True; Visible:No|
|DEFLECTIE                         |String(255,0,0)           |PNH; Deflectie waarde; Nullable: True; Default: None; Visible:No|
|DEFLECTIE_DATE                    |Date(8,0,0)               |PNH; Datum deflectie meting; Nullable: True; Visible:No|
|OMSCHRIJVING                      |String(255,0,0)           |PNH; Extra toelichting; Nullable: True; Default: None; Visible:Yes|
|KOMGRENS                          |String(255,0,0)           |PNH; Komgrens ; Nullable: True; Default: None; Visible:Yes|
|WEGTYPE                           |String(255,0,0)           |PNH; Wegtype; keuzelijst [WEGTYPE]; Nullable: True; Default: None; Visible:Yes|
|WEGINDELING                       |String(255,0,0)           |PNH; Wegindeling; keuzelijst [WEGINDELING]; Nullable: True; Default: None; Visible:No|
|JAARAANLEG                        |SmallInteger(0,10,0)      |PNH; Jaar aanleg van de weg; Nullable: True; Visible:No|
|JAARDEKLAAG                       |SmallInteger(0,10,0)      |PNH; Jaar deklaag gelegd; Nullable: True; Visible:No|
|JAARHERSTRATEN                    |SmallInteger(0,10,0)      |PNH; Jaar Herbestrating gelegd; Nullable: True; Visible:No|
|JAARVERNIEUWEN                    |SmallInteger(0,10,0)      |PNH; TODO; Nullable: True; Visible:No|
|LANGSONVLAKHEID                   |String(255,0,0)           |PNH; Waarde van langsonvlakheidmeting; Nullable: True; Default: None; Visible:No|
|LANGSONVLAKHEID_DATE              |Date(8,0,0)               |PNH; Datum langsonvlakheid meting; Nullable: True; Visible:No|
|DWARSONVLAKHEID                   |String(255,0,0)           |PNH; Dwarsonvlakheid meting; Nullable: True; Default: None; Visible:No|
|DWARSONVLAKHEID_DATE              |Date(8,0,0)               |PNH; Datum dwarsonvlakheid meting; Nullable: True; Visible:No|
|INSPECTEUR                        |String(255,0,0)           |PNH; Inspecterende partij spoorvorming, langsonvlakheid, dwarsonvlakheid; Nullable: True; Default: None; Visible:No|
|LENGTE                            |Float(0,10,0)             |PNH; Lengte van het wegvakonderdeel (hele meters); Nullable: True; Visible:Yes|
|LENGTEVOEGEN                      |SmallInteger(0,10,0)      |PNH; Lengte van de voegen (m); Nullable: True; Visible:Yes|
|SPOORVORMING                      |String(20,0,0)            |PNH; Waarde van de spoorvormingmeting; Nullable: True; Default: None; Visible:No|
|SPOORVORMING_DATE                 |Date(8,0,0)               |PNH; Datum spoorvorming meting; Nullable: True; Visible:No|
|GEBRUIKSFUNCTIE                   |String(255,0,0)           |PNH; Gebruiksfunctie conform CROW; keuzelijst [GEBRUIKSFUNCTIE]; Nullable: True; Default: None; Visible:Yes|
|SITUERING                         |String(255,0,0)           |PNH; Situering conform CROW (L: Links, M: Midden en R: Rechts); keuzelijst [SITUERING]; Nullable: True; Default: None; Visible:Yes|
|STROEFHEID                        |String(20,0,0)            |PNH; Waarde van de stroefheidmeting; Nullable: True; Default: None; Visible:No|
|STROEFHEID_DATE                   |Date(8,0,0)               |PNH; Datum stroefheid meting; Nullable: True; Visible:No|
|VERHARDING                        |String(255,0,0)           |PNH; Verharding object conform CROW; keuzelijst [VERHARDING]; Nullable: True; Default: None; Visible:No|
|VERHARDINGCATEGORIE               |String(255,0,0)           |PNH; Verharding categorie conform CROW; keuzelijst [VERHARDING_CATEGORIE]; Nullable: True; Default: None; Visible:Yes|
|WGV_AFSTANDTOT                    |Float(0,25,10)            |PNH; Wegvak, Aanduiding bij welk wegindexeringspaal (hectometerpaal) het inspectievak eindigt ; Nullable: True; Visible:No|
|WGV_AFSTANDVAN                    |Float(0,25,10)            |PNH; Wegvak, Aanduiding bij welk wegindexeringspaal (hectometerpaal) het inspectievak begint ; Nullable: True; Visible:No|
|WGV_NUMMER                        |SmallInteger(0,10,0)      |PNH; Wegvak, Wegvak nummer, uniek per weg; Nullable: True; Visible:Yes|
|VERLICHT                          |String(10,0,0)            |PNH; Verlicht: Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: O ; Visible:No|
|HECTOMETER                        |String(255,0,0)           |PNH; Hectometrering ; Nullable: True; Default: None; Visible:Yes|
|HALTE                             |String(255,0,0)           |PNH; FK naar halte_v; Nullable: True; Default: None; Visible:No|
|WEGVAK                            |String(255,0,0)           |PNH; FK naar wegvak_v; Nullable: True; Default: None; Visible:No|
|TRAJECT                           |String(255,0,0)           |PNH; FK naar traject_v; Nullable: True; Default: None; Visible:Yes|
|INONDERZOEK                       |String(1,0,0)             |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: None; Visible:No|
|TIJDSTIPREGISTRATIE               |Date(8,0,0)               |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|EINDREGISTRATIE                   |Date(8,0,0)               |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|LV_PUBLICATIEDATUM                |Date(8,0,0)               |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|BERICHT_ID                        |String(128,0,0)           |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|DATALEVERANCIER                   |String(255,0,0)           |PNH; Leverancier van de data; Nullable: True; Default: None; Visible:No|
|CREATED_USER                      |String(255,0,0)           |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None; Visible:No|
|CREATED_DATE                      |Date(8,0,0)               |PNH; Aanmaakdatum; Nullable: True; Visible:No|
|LAST_EDITED_USER                  |String(50,0,0)            |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None; Visible:No|
|LAST_EDITED_DATE                  |Date(8,0,0)               |PNH; Datum van de laatste mutatie; Nullable: True; Visible:No|
|SHAPE                             |Geometry(0,0,0)           |PNH; Vlak; Visible:Yes|
|SHAPE_Length                      |Double(0,0,0)             |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None; Visible:Yes|
|SHAPE_Area                        |Double(0,0,0)             |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None; Visible:Yes|


***
