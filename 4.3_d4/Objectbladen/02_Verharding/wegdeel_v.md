## AREAALDATA.wegdeel_v

*Feature dataset: Opdelend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ BGT
* __Positionele nauwkeurigheid:__ 7,5 cm (NB, groter dan BGT)
* __Geometrie:__ Vlak
* __Definitie:__ Kleinste functioneel onafhankelijk stuk van een NEN 3610 Weg met gelijkblijvende, homogene eigenschappen
en relaties en primair bedoeld voor gebruik door weg-, spoor- en vliegverkeer te land.
* __Mapping_BGT:__ wegdeel_v
* __Mapping_Gisib:__ Wegvakonderdeel, Ondersteunend wegvakonderdeel
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                         |__TYPE (length, precision, scale)__            |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                            |----          	                               |-----    |
|OBJECTID                          |OID(38,0,0)                                    |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                          |GlobalID(38,0,0)                               |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: No|
|AD_ID                             |TEXT(255,0,0)                                  |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                          |LONG(0,10,0)                                   |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                     |TEXT(255,0,0)                                  |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                 |TEXT(255,0,0)                                  |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|STATUS                            |TEXT(10,0,0)                                   |BGT; BGT status van het object; keuzelijst [Status]; Nullable: False; Default: bestaand; Visible: No|
|OBJECTBEGINTIJD                   |DATE(8,0,0)                                    |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                    |DATE(8,0,0)                                    |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING            |SHORT(0,5,0)                                   |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                         |TEXT(255,0,0)                                  |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                       |TEXT(255,0,0)                                  |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                          |TEXT(255,0,0)                                  |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|BRONHOUDER                        |TEXT(5,0,0)                                    |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None; Visible: No|
|TYPESPEC                          |TEXT(255,0,0)                                  |PNH; Nadere typering van het object; keuzelijst [typeSpecWGD]; Nullable: True; Default: None; Visible: Yes|
|FYSIEKVOORKOMEN                   |TEXT(50,0,0)                                   |BGT; Fysieke omschrijving van het object; keuzelijst [fysiekVoorkomenWGD]; Nullable: False; Default: None; Visible: Yes|
|FUNCTIE                           |TEXT(50,0,0)                                   |BGT; Functionele omschrijving van het object; keuzelijst [functieWGD]; Nullable: False; Default: None; Visible: Yes|
|OPTALUD                           |TEXT(1,0,0)                                    |BGT; Ligt het object op een talud? Ja/Nee/Onbekend. Bij 'Ja', moet er een wegdeelKruin_l geregistreerd zijn; keuzelijst [OPTALUD]; Nullable: False; Default: N; Visible: No|
|BREEDTE                           |FLOAT(0,25,10)                                 |PNH; Breedte van het wegvakonderdeel (m, 2 decimalen); ; Nullable: True; Default: None; Visible: No|
|OPMERKING                         |TEXT(255,0,0)                                  |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|KOMGRENS                          |TEXT(255,0,0)                                  |PNH; Komgrens obv de wegenverkeerswet; ; Nullable: True; Default: None; Visible: Yes|
|WEGTYPE                           |TEXT(255,0,0)                                  |PNH; Wegtype; keuzelijst [WEGTYPE]; Nullable: True; Default: None; Visible: Yes|
|WEGINDELING                       |TEXT(255,0,0)                                  |PNH; Wegindeling; keuzelijst [WEGINDELING]; Nullable: True; Default: None; Visible: No|
|JAARAANLEG                        |SHORT(0,5,0)                                   |PNH; Jaar aanleg van de weg; ; Nullable: True; Default: None; Visible: No|
|JAARDEKLAAG                       |SHORT(0,5,0)                                   |PNH; Jaar deklaag gelegd; ; Nullable: True; Default: None; Visible: No|
|JAARHERSTRATEN                    |SHORT(0,5,0)                                   |PNH; Jaar Herbestrating gelegd; ; Nullable: True; Default: None; Visible: No|
|JAARVERNIEUWEN                    |SHORT(0,5,0)                                   |PNH; TODO; ; Nullable: True; Default: None; Visible: No|
|LENGTE_VLAK                       |FLOAT(0,10,0)                                  |PNH; Lengte van het wegvakonderdeel (hele meters), scriptmatig bepaald obv lengterichting wegdeel; ; Nullable: True; Default: None; Visible: Yes|
|LENGTEVOEGEN                      |SHORT(0,5,0)                                   |PNH; Lengte van de voegen (m). De lengte voeg wordt alleen bij betonplaten ingevuld. Hier wordt vermeld hoe lang de voegen van het totale vlak zijn, inclusief de buitenrand; ; Nullable: True; Default: None; Visible: Yes|
|GEBRUIKSFUNCTIE                   |TEXT(255,0,0)                                  |PNH; Gebruiksfunctie conform CROW; keuzelijst [GEBRUIKSFUNCTIE]; Nullable: True; Default: None; Visible: Yes|
|SITUERING                         |TEXT(255,0,0)                                  |PNH; Situering conform CROW (L: Links, M: Midden en R: Rechts); keuzelijst [SITUERING]; Nullable: True; Default: None; Visible: Yes|
|VERHARDING                        |TEXT(255,0,0)                                  |PNH; Verharding object conform CROW; keuzelijst [VERHARDING]; Nullable: True; Default: None; Visible: No|
|VERHARDINGCATEGORIE               |TEXT(255,0,0)                                  |PNH; Verharding categorie conform CROW; keuzelijst [VERHARDING_CATEGORIE]; Nullable: True; Default: None; Visible: Yes|
|WGV_AFSTANDTOT                    |FLOAT(0,25,10)                                 |PNH; Wegvak, Aanduiding bij welk wegindexeringspaal (hectometerpaal) het inspectievak eindigt; ; Nullable: True; Default: None; Visible: No|
|WGV_AFSTANDVAN                    |FLOAT(0,25,10)                                 |PNH; Wegvak, Aanduiding bij welk wegindexeringspaal (hectometerpaal) het inspectievak begint; ; Nullable: True; Default: None; Visible: No|
|WGV_NUMMER                        |SHORT(0,5,0)                                   |PNH; Wegvak, Wegvak nummer, uniek per weg; ; Nullable: True; Default: None; Visible: Yes|
|VERLICHT                          |TEXT(10,0,0)                                   |PNH; Verlicht: Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: O ; Visible: No|
|HECTOMETER                        |TEXT(255,0,0)                                  |PNH; Hectometrering; ; Nullable: True; Default: None; Visible: Yes|
|HALTE                             |TEXT(255,0,0)                                  |PNH; Verwijzende sleutel naar halte_v (simpel); ; Nullable: True; Default: None; Visible: No|
|WEGVAK                            |TEXT(255,0,0)                                  |PNH; Verwijzende sleutel naar wegvak_v (simpel); ; Nullable: True; Default: None; Visible: No|
|TRAJECT                           |TEXT(255,0,0)                                  |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM]; Nullable: True; Default: None; Visible: Yes|
|INONDERZOEK                       |TEXT(1,0,0)                                    |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: None; Visible: No|
|TIJDSTIPREGISTRATIE               |DATE(8,0,0)                                    |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|EINDREGISTRATIE                   |DATE(8,0,0)                                    |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|LV_PUBLICATIEDATUM                |DATE(8,0,0)                                    |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BERICHT_ID                        |TEXT(128,0,0)                                  |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                   |TEXT(255,0,0)                                  |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                      |TEXT(255,0,0)                                  |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                      |DATE(8,0,0)                                    |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                  |TEXT(50,0,0)                                   |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                  |DATE(8,0,0)                                    |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                             |Geometry(0,0,0)                                |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                      |DOUBLE(0,0,0)                                  |PNH; Omtrek in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|SHAPE_Area                        |DOUBLE(0,0,0)                                  |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|OMTREK                            |DOUBLE(0,0,0)                                  |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|
|OPPERVLAKTE                       |DOUBLE(0,0,0)                                  |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Area; ; Nullable: False; Default: None; Visible: Yes|

### Illustraties van verschillende fysieke voorkomens:

 
 |__Fysiek voorkomen__ | __Illustratie__ |
 |-----------------------------------------|----|
 |gesloten verharding asfalt A en C |[gesloten verharding asfalt A en C ](c:\git\bu_geodata_beheer_43d4\gereedschap\documentatie\areaaldata_datamodel\4.3d4\Objectbladen\00_Illustraties\illustraties_wegdeel_v\fysiekVoorkomenWGD\gesloten verharding asfalt A en C\asfalt.jpg)
 |
 |half verhard grasklinkers |![half verhard grasklinkers](c:\git\bu_geodata_beheer_43d4\gereedschap\documentatie\areaaldata_datamodel\4.3d4\Objectbladen\00_Illustraties\illustraties_wegdeel_v\fysiekVoorkomenWGD\half verhard grasklinkers\wegdeel_fysiekvoorkomen_halfverhard_plusgrasklinkers.jpg)
 |
 |open verharding beton element C | ![open verharding beton element C](c:\git\bu_geodata_beheer_43d4\gereedschap\documentatie\areaaldata_datamodel\4.3d4\Objectbladen\00_Illustraties\illustraties_wegdeel_v\fysiekVoorkomenWGD\open verharding beton element C\wegdeel_fysiekvoorkomen_openverharding.jpg)
 |
 |open verharding sierbestrating B en C |![open verharding sierbestrating B en C ](c:\git\bu_geodata_beheer_43d4\gereedschap\documentatie\areaaldata_datamodel\4.3d4\Objectbladen\00_Illustraties\illustraties_wegdeel_v\fysiekVoorkomenWGD\open verharding sierbestrating B en D\sierbestrating.jpg)
 |
 |open verharding tegels A | ![open verharding tegels A](c:\git\bu_geodata_beheer_43d4\gereedschap\documentatie\areaaldata_datamodel\4.3d4\Objectbladen\00_Illustraties\illustraties_wegdeel_v\fysiekVoorkomenWGD\open verharding tegels A\wegdeel_fysiekvoorkomen_openverharding.jpg)
 |
 |gecombineerd fietspad rijstrook | ![gecombineerd fietspad rijstrook](c:\git\bu_geodata_beheer_43d4\gereedschap\documentatie\areaaldata_datamodel\4.3d4\Objectbladen\00_Illustraties\illustraties_wegdeel_v\fysiekVoorkomenWGD\gecombineerd fietspad rijstrook\gecombineerd_fietspad_rijstrook.png)
 |
### Illustratie van Situering
 |Situering | ![Situering](c:\git\bu_geodata_beheer_43d4\gereedschap\documentatie\areaaldata_datamodel\4.3d4\Objectbladen\00_Illustraties\illustraties_wegdeel_v\Situering\Situering.jpg)
 |
***
