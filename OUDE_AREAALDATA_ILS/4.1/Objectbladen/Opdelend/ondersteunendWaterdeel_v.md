## AREAALDATA.ondersteunendWaterdeel_v

*Feature dataset: Opdelend*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ BGT/PNH
* __Positionele nauwkeurigheid:__ 25 cm
* __Geometrie:__ Vlak
* __Definitie:__ Object dat in het kader van de waterhuishouding periodiek gedeeltelijk of geheel met water is bedekt. Een vegetatie van voornamelijk riet en andere soorten langs een waterloop. In breedte variabel van 0,50 tot 3,00 meter. 

***

|KOLOM                              |TYPE          	          |DEFINITIE|
|------                          	|----          	          |-----    |
|OBJECTID                           |OID(38,0,0)              |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:Yes|
|GLOBALID                           |GlobalID(38,0,0)         |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:No|
|AD_ID                              |String(255,0,0)          |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None; Visible:Yes|
|GISIB_ID                           |Integer(0,10,0)          |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|IDENTIFICATIE                      |String(255,0,0)          |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None; Visible:No|
|VERWERKINGSSTATUS                  |String(255,0,0)          |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible:Yes|
|STATUS                             |String(10,0,0)           |BGT; BGT status van het object; keuzelijst [status]; Nullable: False; Default: bestaand; Visible:No|
|OBJECTBEGINTIJD                    |Date(8,0,0)              |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True; Visible:Yes|
|OBJECTEINDTIJD                     |Date(8,0,0)              |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True; Visible:Yes|
|RELATIEVEHOOGTELIGGING             |SmallInteger(0,10,0)     |BGT; Aanduiding voor de relatieve hoogte van het object; Nullable: False; Default: 0; Visible:Yes|
|BEHEERDER                          |String(255,0,0)          |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible:Yes|
|ONDERHOUDER                        |String(255,0,0)          |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible:No|
|EIGENAAR                           |String(255,0,0)          |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible:No|
|BRONHOUDER                         |String(5,0,0)            |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None; Visible:No|
|TYPESPEC                           |String(255,0,0)          |PNH; Nadere typering van het object; keuzelijst [typeSpecOWA]; Nullable: True; Default: None; Visible:Yes|
|BGTPLUSTYPE                        |String(50,0,0)           |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeOWT]; Nullable: False; Default: None; Visible:No|
|TYPE_BEHEER                        |String(50,0,0)           |PNH; Type beheer (maaien, klepelen, uitzuigen etc); keuzelijst [TYPE_BEHEER]; Nullable: True; Default: None|
|TYPEBODEM                          |String(255,0,0)          |PNH; Type bodem; keuzelijst [TYPE_BODEM]; Nullable: True; Default: None; Visible:No|
|TYPEPLAAGSOORT                     |String(255,0,0)          |PNH; Type plaagsoort. De soort wordt  ingevuld die geschat qua oppervlak het meeste voorkomt in dat perceel; keuzelijst [TYPE_PLAAG_INVASIESOORT]; Nullable: True; Default: None|
|ACTUEELBEELD                       |String(255,0,0)          |PNH; Huidige beeld; Nullable: True; Default: None; Visible:No|
|BREEDTE                            |Float(0,25,10)           |PNH; Breedte van de plasberm in m, 2 decimalen; Nullable: True; Default: None; Visible:No|
|OPPERVLAKTE                        |Float(0,10,2)            |PNH; Oppervlakte in m2, afgerond op 2 decimalen; Nullable: True; Default: None; Visible:No|
|JAAR_PLAATSING_AANLEG_GESCHAT      |String(1,0,0)            |PNH; Jaar plaatsing of aanleg is geschat: ja of nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible:No|
|OMSCHRIJVING                       |String(255,0,0)          |PNH; Extra toelichting; Nullable: True; Default: None; Visible:Yes|
|HMBEGIN                            |Float(0,25,10)           |PNH; Hectometrering begin ondersteunendWaterdeel; Nullable: True; Default: None; Visible:No|
|HMEIND                             |Float(0,25,10)           |PNH; Hectometrering eind ondersteunendWaterdeel; Nullable: True; Default: None; Visible:No|
|LENGTE                             |Float(0,10,0)            |PNH; Lengte plantvak in hele meters; Nullable: True; Default: None; Visible:Yes|
|LEVENSVERWACHTING                  |SmallInteger(0,10,0)     |PNH; Levensverwachting; Nullable: True; Default: None; Visible:No|
|OPMERKINGMBTONDERH                 |String(255,0,0)          |PNH; Opmerking met betrekking tot het onderhoud; Nullable: True; Default: None; Visible:No|
|PLANJAAR                           |SmallInteger(0,10,0)     |PNH; Het geplande jaar dat het object vervangen wordt; Nullable: True; Default: None; Visible:No|
|RESTLEVENSDUUR                     |SmallInteger(0,10,0)     |PNH; Restlevensduur in maanden; Nullable: True; Default: None; Visible:No|
|STREEFBEELD                        |String(255,0,0)          |PNH; Concrete visuele doelstelling; Nullable: True; Default: None; Visible:No|
|ZIJDE                              |String(10,0,0)           |PNH; Zijde; keuzelijst [ZIJDE]; Nullable: True; Default: None; Visible:No|
|OEVERVAK                           |String(255,0,0)          |PNH; FK naar oevervak_v; Nullable: True; Default: None; Visible:Yes|
|TRAJECT                            |String(255,0,0)          |PNH; FK naar traject_v; Nullable: True; Default: None; Visible:Yes|
|INONDERZOEK                        |String(1,0,0)            |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible:No|
|TIJDSTIPREGISTRATIE                |Date(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|EINDREGISTRATIE                    |Date(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|LV_PUBLICATIEDATUM                 |Date(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|BERICHT_ID                         |String(128,0,0)          |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|DATALEVERANCIER                    |String(255,0,0)          |PNH; Leverancier van de data; Nullable: True; Default: None; Visible:No|
|CREATED_USER                       |String(255,0,0)          |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None; Visible:No|
|CREATED_DATE                       |Date(8,0,0)              |PNH; Aanmaakdatum; Nullable: True; Visible:No|
|LAST_EDITED_USER                   |String(50,0,0)           |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None; Visible:No|
|LAST_EDITED_DATE                   |Date(8,0,0)              |PNH; Datum van de laatste mutatie; Nullable: True; Visible:No|
|SHAPE                              |Geometry(0,0,0)          |PNH; Vlak; Visible:Yes|
|SHAPE_Length                       |Double(0,0,0)            |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None; Visible:Yes|
|SHAPE_Area                         |Double(0,0,0)            |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None; Visible:Yes|



***
