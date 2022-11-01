## AREAALDATA.ondersteunendWegdeel_v

*Feature dataset: Opdelend*

* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ Bij FysiekVoorkomen: gesloten verharding en open verharding 7,5 cm (NB, groter dan BGT) Bij FysiekVoorkomen: onverhard, half verhard en groenvoorziening 25 cm (NB, groter dan BGT)
* __Geometrie:__ Vlak
* __Definitie:__ Een deel van de weg dat niet primair bedoeld is voor gebruik door het verkeer. Dit omvat o.a. verkeerseiland en berm daar waar de berm onderdeel uitmaakt van de constructie van de weg.

***

|KOLOM                              |TYPE (length, precision, scale)          	           |DEFINITIE (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                          	|----          	           |-----    |
|OBJECTID                           |OID(38,0,0)               |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                           |GlobalID(38,0,0)          |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: No|
|AD_ID                              |String(255,0,0)           |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                           |Integer(0,10,0)           |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
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
|TYPESPEC                           |String(255,0,0)           |PNH; Nadere typering van het object; keuzelijst [typeSpecOWE]; Nullable: True; Default: None; Visible: Yes|
|FYSIEKVOORKOMEN                    |String(50,0,0)            |BGT; Fysieke omschrijving van het object; keuzelijst [fysiekVoorkomenOWG]; Nullable: False; Default: None; Visible: Yes|
|OPTALUD                            |String(1,0,0)             |BGT; Ligt het object op een talud? Ja/Nee/Onbekend. Bij 'Ja', moet er een ondersteunendWegdeelKruin_l geregistreerd zijn; keuzelijst [OPTALUD]; Nullable: False; Default: None; Visible: No|
|FUNCTIE                            |String(50,0,0)            |PNH; Functionele beschrijving van het object; keuzelijst [functieOWG]; Nullable: False; Default: None; Visible: Yes|
|BERMFUNCTIE                        |String(255,0,0)           |PNH; Berm functie; keuzelijst [BERM_FUNCTIE]; Nullable: True; Default: None; Visible: No|
|TYPE_BEHEER                        |String(50,0,0)            |PNH; Type beheer (maaien, klepelen, uitzuigen etc); keuzelijst [TYPE_BEHEER]; Nullable: True; Default: None; Visible: Yes|
|TYPEPLAAGINVASIESOORT              |String(255,0,0)           |PNH; Type plaagsoort. Indien op een bermperceel Japanse duizendknoop voor komt, dan wordt deze ingevuld, ongeacht het oppervlak of aantal ten opzichte van andere soorten uit de domeinlijst. Komt er geen Japanse duizendknoop voor op een perceel, dan wordt de soort ingevuld die geschat qua oppervlak het meeste voorkomt in dat perceel; keuzelijst [TYPE_PLAAG_INVASIESOORT]; Nullable: True; Default: None; Visible: No|
|ZIJDE                              |String(10,0,0)            |PNH; Zijde; keuzelijst [ZIJDE]; Nullable: True; Default: None; Visible: No|
|ACTUEELBEELD                       |String(255,0,0)           |PNH; Huidig beeld van begroeiing; ; Nullable: True; Default: None; Visible: No|
|BIJZONDEREWAARDE                   |String(255,0,0)           |PNH; Indicatie van bijzondere waarde; ; Nullable: True; Default: None; Visible: No|
|DATUMAANPLANTING                   |Date(8,0,0)               |PNH; Datum aanplanting; ; Nullable: True; Default: None; Visible: No|
|OMSCHRIJVING                       |String(255,0,0)           |PNH; Extra toelichting; ; Nullable: True; Default: None; Visible: Yes|
|HMBEGIN                            |Float(0,25,10)            |PNH; Hectometrering begin berm; ; Nullable: True; Default: None; Visible: No|
|HMEIND                             |Float(0,25,10)            |PNH; Hectometrering eind berm; ; Nullable: True; Default: None; Visible: No|
|LENGTE                             |Float(0,10,0)             |PNH; Lengte in meter; ; Nullable: True; Default: None; Visible: Yes|
|OPMERKINGMBTONDERH                 |String(255,0,0)           |PNH; Opmerking met betrekking tot het onderhoud; ; Nullable: True; Default: None; Visible: No|
|PLANJAAR                           |SmallInteger(0,10,0)      |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|RESTLEVENSDUUR                     |SmallInteger(0,10,0)      |PNH; Restlevensduur in maanden; ; Nullable: True; Default: None; Visible: No|
|STREEFBEELD                        |String(255,0,0)           |PNH; Concrete visuele doelstelling; ; Nullable: True; Default: None; Visible: No|
|GRONDSOORT                         |String(255,0,0)           |PNH; Grondsoort; keuzelijst [GRONDSOORT]; Nullable: True; Default: None; Visible: No|
|ZAADMENGSEL                        |String(255,0,0)           |PNH; Zaadmengsel; ; Nullable: True; Default: None; Visible: No|
|SITUERING                          |String(255,0,0)           |PNH; Situering conform CROW (L: Links, M: Midden en R: Rechts); keuzelijst [SITUERING]; Nullable: True; Default: None; Visible: Yes|
|JAARAANLEG                         |SmallInteger(0,10,0)      |PNH; Jaar aanleg van de weg; ; Nullable: True; Default: None; Visible: No|
|VERHARDINGCATEGORIE                |String(255,0,0)           |PNH; Verharding categorie conform CROW; keuzelijst [VERHARDING_CATEGORIE]; Nullable: True; Default: None; Visible: No|
|VERHARDING                         |String(255,0,0)           |PNH; Verharding object conform CROW; keuzelijst [VERHARDING]; Nullable: True; Default: None; Visible: No|
|GEBRUIKSFUNCTIE                    |String(255,0,0)           |PNH; Gebruiksfunctie conform CROW; keuzelijst [GEBRUIKSFUNCTIE]; Nullable: True; Default: None; Visible: Yes|
|TRAJECT                            |String(255,0,0)           |PNH; FK naar traject_v; keuzelijst [TRAJECT_NAAM] ; Nullable: True; Default: None; Visible: Yes|
|WEGVAK                             |String(255,0,0)           |PNH; FK naar wegvak_v; ; Nullable: True; Default: None; Visible: No|
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
