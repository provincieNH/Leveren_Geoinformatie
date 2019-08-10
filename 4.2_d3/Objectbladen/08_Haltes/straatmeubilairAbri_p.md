## AREAALDATA.straatmeubilairAbri_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMGEO/PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Een abri, gerepresenteerd als punt. 
![Abri illustratie](D:\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.2d3\Objectbladen\08_Haltes\abri.jpg)
* __Mapping_BGT:__ overigBouwwerk_v
* __Mapping_Gisib:__ Abri, Overig Bouwwerk


***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__(oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----          	        |-----    |
|OBJECTID                            |OID(38,0,0)               |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)          |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: No|
|AD_ID                               |String(255,0,0)           |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |Integer(0,10,0)           |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                       |String(255,0,0)           |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |String(255,0,0)           |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|STATUS                              |String(10,0,0)            |BGT; BGT status van het object; keuzelijst [status]; Nullable: False; Default: bestaand; Visible: No|
|OBJECTBEGINTIJD                     |Date(8,0,0)               |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)               |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING              |SmallInteger(0,5,0)       |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                           |String(255,0,0)           |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |String(255,0,0)           |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |String(255,0,0)           |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|BRONHOUDER                          |String(5,0,0)             |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None; Visible: No|
|TYPESPEC                            |String(255,0,0)           |PNH; Nadere typering van het object; keuzelijst [typeSpecSTMAbri]; Nullable: True; Default: None; Visible: Yes|
|BGTPLUSTYPE                         |String(50,0,0)            |BGT; Nadere type omschrijving in de BGT; ; Nullable: False; Default: niet-bgt:abri; Visible: No|
|HOOGTE                              |Float(0,10,0)             |PNH; Hoogte van het lichtpunt in meter; ; Nullable: True; Default: None; Visible: Yes|
|MATERIAALTYPE                       |String(255,0,0)           |PNH; Materiaalkeuze; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None; Visible: Yes|
|ZIJDE                               |String(10,0,0)            |PNH; Zijde; keuzelijst [ZIJDE]; Nullable: True; Default: None; Visible: No|
|HECTOMETER                          |String(255,0,0)           |PNH; Hectometrering; ; Nullable: True; Default: None; Visible: Yes|
|CONTACTPERSOON                      |String(255,0,0)           |PNH; Contactpersoon namens de herdenkers; ; Nullable: True; Default: None; Visible: No|
|DATUMAANLEG                         |Date(8,0,0)               |PNH; Datum Aanleg; ; Nullable: True; Default: None; Visible: No|
|FOTO                                |String(255,0,0)           |PNH; Locatie van de foto op de S schijf bij PNH. Deze hoeft niet gevuld te worden door de aannemer; ; Nullable: True; Default: None; Visible: No|
|DATUMPLAATSING                      |Date(8,0,0)               |PNH; Datum aanleg; ; Nullable: True; Default: None; Visible: No|
|CONTRACTNR                          |String(255,0,0)           |PNH; Numnmer van het contract; ; Nullable: True; Default: None; Visible: No|
|OVEREENKOMSTNR                      |String(255,0,0)           |PNH; Numnmer van de overeenkomst; ; Nullable: True; Default: None; Visible: No|
|FACTUURNR                           |String(255,0,0)           |PNH; Numnmer van de factuur; ; Nullable: True; Default: None; Visible: No|
|JAAR_PLAATSING_AANLEG_GESCHAT       |String(1,0,0)             |PNH; Jaar plaatsing of aanleg is geschat: ja of nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|OPMERKING                           |String(255,0,0)           |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|LEVENSVERWACHTING                   |SmallInteger(0,5,0)       |PNH; Levensverwachting in jaren jaar; ; Nullable: True; Default: None; Visible: No|
|PLANJAAR                            |SmallInteger(0,5,0)       |PNH; Planjaar; ; Nullable: True; Default: None; Visible: No|
|RESTLEVENSDUUR                      |SmallInteger(0,5,0)       |PNH; Restlevensduur in maanden; ; Nullable: True; Default: None; Visible: No|
|FABRIKANTTYPECODE                   |String(255,0,0)           |PNH; Fabrikanttypecode; ; Nullable: True; Default: None; Visible: Yes|
|LENGTE                              |Float(0,10,2)             |PNH; Lengte in Meters, 2 decimalen; ; Nullable: True; Default: None; Visible: Yes|
|BREEDTE                             |Float(0,10,2)             |PNH; Breedte in Meters, 2 decimalen; ; Nullable: True; Default: None; Visible: No|
|KWALITEITSNIVEAU                    |String(255,0,0)           |PNH; Kwaliteitsniveau; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|RECLAME_GEEXPLOITEERD               |String(1,0,0)             |PNH; Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|RECLAME_GEEXPL_ZWARTELIJST          |String(10,0,0)            |PNH; Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|RECLAME_VERLICHTING                 |String(1,0,0)             |PNH; Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|ZITMEUBILAIR_AANW                   |String(1,0,0)             |PNH; Zitmeubilair aanwezig Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|VERLICHTING_AANW                    |String(1,0,0)             |PNH; Verlichting aanwezig Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|VERLICHTING_TYPE                    |String(255,0,0)           |PNH; Type verlichting (led/../); ; Nullable: True; Default: None; Visible: No|
|VERLICHTING_FABRIKANT               |String(255,0,0)           |PNH; Naam van de verlichtingsfabrikant; ; Nullable: True; Default: None; Visible: No|
|ZONNEPANEEL                         |String(1,0,0)             |PNH; Zonnepaneel aanwezig Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|HALTE                               |String(255,0,0)           |PNH; Verwijzende sleutel naar halte_v (simpel); ; Nullable: True; Default: None; Visible: No|
|TRAJECT                             |String(255,0,0)           |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM]; Nullable: True; Default: None; Visible: Yes|
|INONDERZOEK                         |String(1,0,0)             |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible: No|
|TIJDSTIPREGISTRATIE                 |Date(8,0,0)               |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|EINDREGISTRATIE                     |Date(8,0,0)               |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|LV_PUBLICATIEDATUM                  |Date(8,0,0)               |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BERICHT_ID                          |String(128,0,0)           |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |String(255,0,0)           |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |String(255,0,0)           |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)               |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)            |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)               |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry(0,0,0)           |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|


***
