## AREAALDATA.begroeidTerreindeelBerm_v

*Feature dataset: Opdelend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 25 cm
* __Geometrie:__ Vlak
* __Definitie:__ Een ecologische berm met een vegetatie van grassen en kruiden. BGT Begroeid Terreindeel, verbijzonderd naar fysiek voorkomen groenvoorziening: gras- en kruidachtigen. Deze berm ligt verder dan 3 meter van een provinciale weg. Bermen dichter dan 3 meter bij een provinciale weg worden vastgelegd in ondersteunendWegdeel_v.
* __Mapping_BGT:__ begroeidTerreindeel_v
* __Mapping_Gisib:__ Berm
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                         |__TYPE (length, precision, scale)__      |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                            |----          	                         |-----    |
|OBJECTID                          |OID(38,0,0)                              |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                          |GlobalID(38,0,0)                         |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                             |TEXT(255,0,0)                            |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                          |LONG(0,10,0)                             |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                     |TEXT(255,0,0)                            |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                 |TEXT(255,0,0)                            |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|STATUS                            |TEXT(10,0,0)                             |BGT; BGT status van het object; keuzelijst [Status]; Nullable: False; Default: bestaand; Visible: No|
|OBJECTBEGINTIJD                   |DATE(8,0,0)                              |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                    |DATE(8,0,0)                              |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING            |SHORT(0,5,0)                             |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                         |TEXT(255,0,0)                            |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                       |TEXT(255,0,0)                            |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                          |TEXT(255,0,0)                            |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|BRONHOUDER                        |TEXT(5,0,0)                              |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None; Visible: No|
|TYPESPEC                          |TEXT(255,0,0)                            |PNH; Nadere typering van het object; keuzelijst [typeSpecBTDBerm]; Nullable: True; Default: None; Visible: Yes|
|FYSIEKVOORKOMEN                   |TEXT(50,0,0)                             |PNH; Fysieke omschrijving van het object; keuzelijst [fysiekVoorkomenBTDB]; Nullable: False; Default: groenvoorziening:gras- en kruidachtigen; Visible: No|
|OPTALUD                           |TEXT(1,0,0)                              |PNH; Ligt het object op een talud? Ja/Nee/Onbekend. Bij 'Ja', moet er een begroeidTerreindeelBermKr_l geregistreerd zijn; keuzelijst [OPTALUD]; Nullable: True; Default: N; Visible: No|
|TYPE_BEHEER                       |TEXT(50,0,0)                             |PNH; Type beheer (maaien, klepelen, uitzuigen etc); keuzelijst [TYPE_BEHEER]; Nullable: True; Default: None; Visible: No|
|ZIJDE                             |TEXT(10,0,0)                             |PNH; Zijde (vd weg); keuzelijst [ZIJDE]; Nullable: True; Default: None; Visible: No|
|ACTUEELBEELD                      |TEXT(255,0,0)                            |PNH; Huidig beeld van begroeiing; ; Nullable: True; Default: None; Visible: No|
|BIJZONDEREWAARDE                  |TEXT(255,0,0)                            |PNH; Indicatie van bijzondere waarde; ; Nullable: True; Default: None; Visible: No|
|JAARAANPLANTING                   |LONG(0,4,0)                              |PNH; Jaar van aanplanting; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                         |TEXT(255,0,0)                            |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|HMBEGIN                           |FLOAT(0,25,10)                           |PNH; Hectometrering begin berm; ; Nullable: True; Default: None; Visible: No|
|HMEIND                            |FLOAT(0,25,10)                           |PNH; Hectometrering eind berm; ; Nullable: True; Default: None; Visible: No|
|STREEFBEELD                       |TEXT(255,0,0)                            |PNH; Concrete visuele doelstelling; ; Nullable: True; Default: None; Visible: No|
|GRONDSOORT                        |TEXT(255,0,0)                            |PNH; Grondsoort; keuzelijst [GRONDSOORT]; Nullable: True; Default: None; Visible: No|
|ZAADMENGSEL                       |TEXT(255,0,0)                            |PNH; Zaadmengsel; ; Nullable: True; Default: None; Visible: No|
|OEVERVAK                          |TEXT(255,0,0)                            |PNH; Verwijzende sleutel naar oevervak_v (simpel); ; Nullable: True; Default: None; Visible: Yes|
|TRAJECT                           |TEXT(255,0,0)                            |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM]; Nullable: True; Default: None; Visible: Yes|
|INONDERZOEK                       |TEXT(1,0,0)                              |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible: No|
|TIJDSTIPREGISTRATIE               |DATE(8,0,0)                              |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|EINDREGISTRATIE                   |DATE(8,0,0)                              |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|LV_PUBLICATIEDATUM                |DATE(8,0,0)                              |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BERICHT_ID                        |TEXT(128,0,0)                            |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                   |TEXT(255,0,0)                            |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                      |TEXT(255,0,0)                            |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                      |DATE(8,0,0)                              |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                  |TEXT(50,0,0)                             |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                  |DATE(8,0,0)                              |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LENGTE_VLAK                       |FLOAT(0,10,0)                            |PNH; Lengte in meters, scriptmatig bepaald obv lengterichting bermdeel; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE                             |Geometry(0,0,0)                          |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                      |DOUBLE(0,0,0)                            |PNH; Omtrek in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|SHAPE_Area                        |DOUBLE(0,0,0)                            |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|OMTREK                            |DOUBLE(0,0,0)                            |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|
|OPPERVLAKTE                       |DOUBLE(0,0,0)                            |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Area; ; Nullable: False; Default: None; Visible: Yes|



***