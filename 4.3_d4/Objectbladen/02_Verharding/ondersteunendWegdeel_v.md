## AREAALDATA.ondersteunendWegdeel_v

*Feature dataset: Opdelend*

* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ Bij FysiekVoorkomen: gesloten verharding en open verharding 7,5 cm (NB, groter dan BGT) Bij FysiekVoorkomen: onverhard, half verhard en groenvoorziening 25 cm (NB, groter dan BGT)
* __Geometrie:__ Vlak
* __Definitie:__ Een deel van de weg dat niet primair bedoeld is voor gebruik door het verkeer. Dit omvat o.a. verkeerseiland en berm daar waar de berm onderdeel uitmaakt van de constructie van de weg. Indien eeen berm geen onderdeel uitmaakt van de constructie van de weg, en verder dan 3 meter van een provinciale weg ligt, wordt deze vastgelegd in begroeidTerrteindeelBerm_v.
* __Mapping_BGT:__ ondersteunendWegdeel_v
* __Mapping_Gisib:__ Berm, Ondersteunend wegvakonderdeel
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__                      |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                            |----                         |-----    |
|OBJECTID                           |OID(38,0,0)                 |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                           |GlobalID(38,0,0)            |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: No|
|AD_ID                              |TEXT(255,0,0)               |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                           |LONG(0,10,0)                |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                      |TEXT(255,0,0)               |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                  |TEXT(255,0,0)               |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|STATUS                             |TEXT(10,0,0)                |BGT; BGT status van het object; keuzelijst [Status]; Nullable: False; Default: bestaand; Visible: No|
|OBJECTBEGINTIJD                    |DATE(8,0,0)                 |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                     |DATE(8,0,0)                 |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING             |SHORT(0,5,0)                |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                          |TEXT(255,0,0)               |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                        |TEXT(255,0,0)               |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                           |TEXT(255,0,0)               |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|BRONHOUDER                         |TEXT(5,0,0)                 |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None; Visible: No|
|TYPESPEC                           |TEXT(255,0,0)               |PNH; Nadere typering van het object; keuzelijst [typeSpecOWG]; Nullable: True; Default: None; Visible: Yes|
|FYSIEKVOORKOMEN                    |TEXT(50,0,0)                |BGT; Fysieke omschrijving van het object; keuzelijst [fysiekVoorkomenOWG]; Nullable: False; Default: None; Visible: Yes|
|OPTALUD                            |TEXT(1,0,0)                 |BGT; Ligt het object op een talud? Ja/Nee/Onbekend. Bij 'Ja', moet er een ondersteunendWegdeelKruin_l geregistreerd zijn; keuzelijst [OPTALUD]; Nullable: False; Default: N; Visible: No|
|FUNCTIE                            |TEXT(50,0,0)                |PNH; Functionele beschrijving van het object; keuzelijst [functieOWG]; Nullable: False; Default: None; Visible: Yes|
|BERMFUNCTIE                        |TEXT(255,0,0)               |PNH; Berm functie; keuzelijst [BERM_FUNCTIE]; Nullable: True; Default: None; Visible: No|
|TYPE_BEHEER                        |TEXT(50,0,0)                |PNH; Type beheer (maaien, klepelen, uitzuigen etc); keuzelijst [TYPE_BEHEER]; Nullable: True; Default: None; Visible: Yes|
|TYPEPLAAGINVASIESOORT              |TEXT(255,0,0)               |PNH; Type plaagsoort. Indien op een bermperceel Japanse duizendknoop voor komt, dan wordt deze ingevuld, ongeacht het oppervlak of aantal ten opzichte van andere soorten uit de domeinlijst. Komt er geen Japanse duizendknoop voor op een perceel, dan wordt de soort ingevuld die geschat qua oppervlak het meeste voorkomt in dat perceel; keuzelijst [TYPE_PLAAGSOORT_LAND]; Nullable: True; Default: None; Visible: Yes|
|ZIJDE                              |TEXT(10,0,0)                |PNH; Zijde; keuzelijst [Zijde]; Nullable: True; Default: None; Visible: No|
|BIJZONDEREWAARDE                   |TEXT(255,0,0)               |PNH; Indicatie van bijzondere waarde; ; Nullable: True; Default: None; Visible: No|
|DATUMAANPLANTING                   |DATE(8,0,0)                 |PNH; Datum aanplanting; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                          |TEXT(255,0,0)               |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|HMBEGIN                            |FLOAT(0,25,10)              |PNH; Hectometrering begin berm; ; Nullable: True; Default: None; Visible: No|
|HMEIND                             |FLOAT(0,25,10)              |PNH; Hectometrering eind berm; ; Nullable: True; Default: None; Visible: No|
|LENGTE_VLAK                        |FLOAT(0,10,0)               |PNH; Lengte in meter, scriptmatig bepaald obv lengterichting wegdeel; ; Nullable: True; Default: None; Visible: Yes|
|PLANJAAR                           |SHORT(0,5,0)                |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|GRONDSOORT                         |TEXT(255,0,0)               |PNH; Grondsoort; keuzelijst [GRONDSOORT]; Nullable: True; Default: None; Visible: No|
|ZAADMENGSEL                        |TEXT(255,0,0)               |PNH; Zaadmengsel; ; Nullable: True; Default: None; Visible: No|
|SITUERING                          |TEXT(255,0,0)               |PNH; Situering conform CROW (L: Links, M: Midden en R: Rechts); keuzelijst [SITUERING]; Nullable: True; Default: None; Visible: Yes|
|JAARAANLEG                         |SHORT(0,5,0)                |PNH; Jaar aanleg van de weg; ; Nullable: True; Default: None; Visible: No|
|VERHARDINGCATEGORIE                |TEXT(255,0,0)               |PNH; Verharding categorie conform CROW; keuzelijst [VERHARDING_CATEGORIE]; Nullable: True; Default: None; Visible: No|
|VERHARDING                         |TEXT(255,0,0)               |PNH; Verharding object conform CROW; keuzelijst [VERHARDING]; Nullable: True; Default: None; Visible: No|
|GEBRUIKSFUNCTIE                    |TEXT(255,0,0)               |PNH; Gebruiksfunctie conform CROW; keuzelijst [GEBRUIKSFUNCTIE]; Nullable: True; Default: None; Visible: Yes|
|TRAJECT                            |TEXT(255,0,0)               |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM]; Nullable: True; Default: None; Visible: Yes|
|WEGVAK                             |TEXT(255,0,0)               |PNH; Verwijzende sleutel naar wegvak_v (simpel); ; Nullable: True; Default: None; Visible: No|
|INONDERZOEK                        |TEXT(1,0,0)                 |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible: No|
|TIJDSTIPREGISTRATIE                |DATE(8,0,0)                 |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|EINDREGISTRATIE                    |DATE(8,0,0)                 |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|LV_PUBLICATIEDATUM                 |DATE(8,0,0)                 |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BERICHT_ID                         |TEXT(128,0,0)               |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                    |TEXT(255,0,0)               |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|TYPEPLANTVAK1                      |TEXT(255,0,0)               |PNH; Type plantvak; keuzelijst [typeSpecOWGPlantvak]; Nullable: True; Default: None; Visible: No|
|TYPEPLANTVAK2                      |TEXT(255,0,0)               |PNH; Type plantvak; keuzelijst [typeSpecOWGPlantvak]; Nullable: True; Default: None; Visible: No|
|TYPEPLANTVAK3                      |TEXT(255,0,0)               |PNH; Type plantvak; keuzelijst [typeSpecOWGPlantvak]; Nullable: True; Default: None; Visible: No|
|TYPEPLANTVAK4                      |TEXT(255,0,0)               |PNH; Type plantvak; keuzelijst [typeSpecOWGPlantvak]; Nullable: True; Default: None; Visible: No|
|CREATED_USER                       |TEXT(255,0,0)               |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                       |DATE(8,0,0)                 |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                   |TEXT(50,0,0)                |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                   |DATE(8,0,0)                 |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                              |Geometry(0,0,0)             |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                       |DOUBLE(0,0,0)               |PNH; Omtrek in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|SHAPE_Area                         |DOUBLE(0,0,0)               |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|OMTREK                             |DOUBLE(0,0,0)               |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|
|OPPERVLAKTE                        |DOUBLE(0,0,0)               |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Area; ; Nullable: False; Default: None; Visible: Yes|


### Illustraties van verschillende fysieke voorkomens:


 |__Fysiek voorkomen__ | __Illustratie__ |
 |---------------------------------- |---- |
 |gesloten verharding asfalt A en C |![gesloten verharding asfalt A en C](D:\git\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.3d4\Objectbladen\00_Illustraties\illustraties_ondersteunendWegdeel_v\gesloten verharding asfalt A en C\asfalt.jpg)
 |
 |groenvoorziening bodembedekkers|![groenvoorziening bodembedekkers](D:\git\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.3d4\Objectbladen\00_Illustraties\illustraties_ondersteunendWegdeel_v\groenvoorziening bodembedekkers\BTDl_fysiekvoorkomen_groenvoorziening_plusbodembedekkers.jpg)
 |
 |groenvoorziening bosplantsoen | ![groenvoorziening bosplantsoen ](D:\git\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.3d4\Objectbladen\00_Illustraties\illustraties_ondersteunendWegdeel_v\groenvoorziening bosplantsoen\BTD_fysiekvoorkomen_groenvoorziening_plusbosplantsoen.jpg)
 |
 |groenvoorziening heesters |![groenvoorziening heesters](D:\git\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.3d4\Objectbladen\00_Illustraties\illustraties_ondersteunendWegdeel_v\groenvoorziening heesters\BTD_fysiekvoorkomen_groenvoorziening_plusheesters.png)
 |
 |groenvoorziening planten | ![groenvoorziening planten](D:\git\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.3d4\Objectbladen\00_Illustraties\illustraties_ondersteunendWegdeel_v\groenvoorziening planten\BTD_fysiekvoorkomen_groenvoorziening_plusplanten.jpg)
 |
 |groenvoorziening struikrozen | ![groenvoorziening struikrozen](D:\git\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.3d4\Objectbladen\00_Illustraties\illustraties_ondersteunendWegdeel_v\groenvoorziening struikrozen\BTD_fysiekvoorkomen_groenvoorziening_plusstruikrozen.jpg)
 |
 |half verhard grasklinkers | ![half verhard grasklinkers](D:\git\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.3d4\Objectbladen\00_Illustraties\illustraties_ondersteunendWegdeel_v\half verhard grasklinkers\WGD_fysiekvoorkomen_halfverhard_plusgrasklinkers.jpg)
 |
 |open verharding beton element B | ![open verharding beton element B ](D:\git\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.3d4\Objectbladen\00_Illustraties\illustraties_ondersteunendWegdeel_v\open verharding beton element B\betonelement.jpg)
 |
 |open verharding sierbestrating B en D | ![open verharding sierbestrating B en D ](D:\git\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.3d4\Objectbladen\00_Illustraties\illustraties_ondersteunendWegdeel_v\open verharding sierbestrating B en D\sierbestrating.jpg)
 |
 |open verharding tegels A | ![open verharding tegels A](D:\git\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.3d4\Objectbladen\00_Illustraties\illustraties_ondersteunendWegdeel_v\open verharding tegels A\WGD_fysiekvoorkomen_openverharding.jpg)
 |

***
