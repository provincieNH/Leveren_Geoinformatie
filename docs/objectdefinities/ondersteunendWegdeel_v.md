## AREAALDATA.ondersteunendWegdeel_v

*Feature dataset: Opdelend*

* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ Bij FysiekVoorkomen: gesloten verharding en open verharding 7,5 cm (NB, groter dan BGT) Bij FysiekVoorkomen: onverhard, half verhard en groenvoorziening 25 cm (NB, groter dan BGT)
* __Geometrie:__ Vlak
* __Definitie:__ Een deel van de weg dat niet primair bedoeld is voor gebruik door het verkeer. Dit omvat o.a. verkeerseiland en berm daar waar de berm onderdeel uitmaakt van de constructie van de weg. Indien eeen berm geen onderdeel uitmaakt van de constructie van de weg, en verder dan 3 meter van een provinciale weg ligt, wordt deze vastgelegd in begroeidTerrteindeelBerm_v.
* __Mapping_BGT:__ ondersteunendWegdeel_v
* __Mapping_Gisib:__ Berm, Ondersteunend wegvakonderdeel

***

|__KOLOM__                             |__TYPE (length, precision, scale)__                      |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer; zichtbaar in Toetsviewer)|
|------                            |----                         |-----    |
|OBJECTID                           |OID(38,0,0)               |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes; Visible: No|
|GLOBALID                           |GlobalID(38,0,0)          |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: No; Visible: No|
|AD_ID                              |String(255,0,0)           |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes; Visible: Yes|
|GISIB_ID                           |Integer(0,10,0)           |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No; Visible: No|
|IDENTIFICATIE                      |String(255,0,0)           |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No; Visible: No|
|VERWERKINGSSTATUS                  |String(255,0,0)           |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.md); Nullable: False; Default: Nieuw; Visible: Yes; Visible: Yes|
|STATUS                             |String(10,0,0)            |BGT; BGT status van het object; keuzelijst [status](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/status.md); Nullable: False; Default: bestaand; Visible: No; Visible: No|
|OBJECTBEGINTIJD                    |Date(8,0,0)               |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes; Visible: Yes|
|OBJECTEINDTIJD                     |Date(8,0,0)               |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes; Visible: Yes|
|RELATIEVEHOOGTELIGGING             |SmallInteger(0,5,0)       |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes; Visible: Yes|
|BEHEERDER                          |String(255,0,0)           |PNH; Beheerder van het object; keuzelijst [BEHEERDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEERDER.md); Nullable: True; Default: None; Visible: Yes; Visible: No|
|ONDERHOUDER                        |String(255,0,0)           |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ONDERHOUDER.md); Nullable: True; Default: None; Visible: Yes; Visible: No|
|EIGENAAR                           |String(255,0,0)           |PNH; Eigenaar van het object; keuzelijst [INSTANTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/INSTANTIE.md); Nullable: True; Default: None; Visible: Yes; Visible: No|
|BRONHOUDER                         |String(5,0,0)             |BGT; De bronhoudercode van het object; keuzelijst [bronhouder](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/bronhouder.md); Nullable: False; Default: None; Visible: No; Visible: No|
|TYPESPEC                           |String(255,0,0)           |PNH; Nadere typering van het object; keuzelijst [typeSpecOWE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecOWE.md); Nullable: True; Default: None; Visible: Yes; Visible: Yes|
|FYSIEKVOORKOMEN                    |String(50,0,0)            |BGT; Fysieke omschrijving van het object; keuzelijst [fysiekVoorkomenOWG](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/fysiekVoorkomenOWG.md); Nullable: False; Default: None; Visible: Yes; Visible: Yes|
|OPTALUD                            |String(1,0,0)             |BGT; Ligt het object op een talud? Ja/Nee/Onbekend. Bij 'Ja', moet er een ondersteunendWegdeelKruin_l geregistreerd zijn; keuzelijst [OPTALUD](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/OPTALUD.md); Nullable: False; Default: N; Visible: No; Visible: Yes|
|FUNCTIE                            |String(50,0,0)            |PNH; Functionele beschrijving van het object; keuzelijst [functieOWG](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/functieOWG.md); Nullable: False; Default: None; Visible: Yes|
|BERMFUNCTIE                        |String(255,0,0)           |PNH; Berm functie; keuzelijst [BERM_FUNCTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BERM_FUNCTIE.md); Nullable: True; Default: None; Visible: No; Visible: Yes|
|TYPE_BEHEER                        |String(50,0,0)            |PNH; Type beheer (maaien, klepelen, uitzuigen etc); keuzelijst [TYPE_BEHEER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/TYPE_BEHEER.md); Nullable: True; Default: None; Visible: Yes; Visible: Yes|
|TYPEPLAAGINVASIESOORT              |String(255,0,0)           |PNH; Type plaagsoort. Indien op een bermperceel Japanse duizendknoop voor komt, dan wordt deze ingevuld, ongeacht het oppervlak of aantal ten opzichte van andere soorten uit de domeinlijst. Komt er geen Japanse duizendknoop voor op een perceel, dan wordt de soort ingevuld die geschat qua oppervlak het meeste voorkomt in dat perceel; keuzelijst [TYPE_PLAAGSOORT_LAND](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/TYPE_PLAAGSOORT_LAND.md); Nullable: True; Default: None; Visible: Yes; Visible: Yes|
|ZIJDE                              |String(10,0,0)            |PNH; Zijde; keuzelijst [ZIJDE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ZIJDE.md); Nullable: True; Default: None; Visible: No; Visible: Yes|
|BIJZONDEREWAARDE                   |String(255,0,0)           |PNH; Indicatie van bijzondere waarde; ; Nullable: True; Default: None; Visible: No; Visible: Yes|
|DATUMAANPLANTING                   |Date(8,0,0)               |PNH; Datum aanplanting; ; Nullable: True; Default: None; Visible: No; Visible: Yes|
|OPMERKING                          |String(255,0,0)           |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes; Visible: Yes|
|HMBEGIN                            |Float(0,25,10)            |PNH; Hectometrering begin berm; ; Nullable: True; Default: None; Visible: No; Visible: Yes|
|HMEIND                             |Float(0,25,10)            |PNH; Hectometrering eind berm; ; Nullable: True; Default: None; Visible: No; Visible: Yes|
|LENGTE                             |Float(0,10,0)             |PNH; Lengte in meter; ; Nullable: True; Default: None; Visible: Yes; Visible: Yes|
|PLANJAAR                           |SmallInteger(0,5,0)       |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No; Visible: Yes|
|GRONDSOORT                         |String(255,0,0)           |PNH; Grondsoort; keuzelijst [GRONDSOORT](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/GRONDSOORT.md); Nullable: True; Default: None; Visible: No; Visible: Yes|
|ZAADMENGSEL                        |String(255,0,0)           |PNH; Zaadmengsel; ; Nullable: True; Default: None; Visible: No; Visible: Yes|
|SITUERING                          |String(255,0,0)           |PNH; Situering conform CROW (L: Links, M: Midden en R: Rechts); keuzelijst [SITUERING](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/SITUERING.md); Nullable: True; Default: None; Visible: Yes; Visible: Yes|
|JAARAANLEG                         |SmallInteger(0,5,0)       |PNH; Jaar aanleg van de weg; ; Nullable: True; Default: None; Visible: No; Visible: Yes|
|VERHARDINGCATEGORIE                |String(255,0,0)           |PNH; Verharding categorie conform CROW; keuzelijst [VERHARDING_CATEGORIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERHARDING_CATEGORIE.md); Nullable: True; Default: None; Visible: No; Visible: Yes|
|VERHARDING                         |String(255,0,0)           |PNH; Verharding object conform CROW; keuzelijst [VERHARDING](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERHARDING.md); Nullable: True; Default: None; Visible: No; Visible: Yes|
|GEBRUIKSFUNCTIE                    |String(255,0,0)           |PNH; Gebruiksfunctie conform CROW; keuzelijst [GEBRUIKSFUNCTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/GEBRUIKSFUNCTIE.md); Nullable: True; Default: None; Visible: Yes; Visible: Yes|
|TRAJECT                            |String(255,0,0)           |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/TRAJECT_NAAM.md); Nullable: True; Default: None; Visible: Yes; Visible: Yes|
|WEGVAK                             |String(255,0,0)           |PNH; Verwijzende sleutel naar wegvak_v (simpel); ; Nullable: True; Default: None; Visible: No; Visible: Yes|
|INONDERZOEK                        |String(1,0,0)             |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.md); Nullable: False; Default: N; Visible: No; Visible: No|
|TIJDSTIPREGISTRATIE                |Date(8,0,0)               |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No; Visible: No|
|EINDREGISTRATIE                    |Date(8,0,0)               |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No; Visible: No|
|LV_PUBLICATIEDATUM                 |Date(8,0,0)               |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No; Visible: No|
|BERICHT_ID                         |String(128,0,0)           |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No; Visible: No|
|DATALEVERANCIER                    |String(255,0,0)           |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|TYPEPLANTVAK1                      |String(255,0,0)           |PNH; Type plantvak; keuzelijst [typeSpecOWEPlantvak](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecOWEPlantvak.md); Nullable: True; Default: None; Visible: No; Visible: Yes|
|TYPEPLANTVAK2                      |String(255,0,0)           |PNH; Type plantvak; keuzelijst [typeSpecOWEPlantvak](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecOWEPlantvak.md); Nullable: True; Default: None; Visible: No; Visible: Yes|
|TYPEPLANTVAK3                      |String(255,0,0)           |PNH; Type plantvak; keuzelijst [typeSpecOWEPlantvak](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecOWEPlantvak.md); Nullable: True; Default: None; Visible: No; Visible: Yes|
|TYPEPLANTVAK4                      |String(255,0,0)           |PNH; Type plantvak; keuzelijst [typeSpecOWEPlantvak](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecOWEPlantvak.md); Nullable: True; Default: None; Visible: No; Visible: Yes|
|CREATED_USER                       |String(255,0,0)           |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No; Visible: No|
|CREATED_DATE                       |Date(8,0,0)               |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No; Visible: No|
|LAST_EDITED_USER                   |String(50,0,0)            |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No; Visible: No|
|LAST_EDITED_DATE                   |Date(8,0,0)               |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No; Visible: No|
|SHAPE                              |Geometry(0,0,0)           |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes; Visible: Yes|
|SHAPE_Length                       |Double(0,0,0)             |PNH; Omtrek in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No; Visible: Yes|
|SHAPE_Area                         |Double(0,0,0)             |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No; Visible: Yes|
|OMTREK                             |Double(0,0,0)             |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes; Visible: Yes|
|OPPERVLAKTE                        |Double(0,0,0)             |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Area; ; Nullable: False; Default: None; Visible: Yes; Visible: Yes|


### Illustraties van verschillende fysieke voorkomens:


 |__Fysiek voorkomen__ | __Illustratie__ |
 |---------------------------------- |---- |
 |gesloten verharding asfalt A en C |![gesloten verharding asfalt A en C](D:\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.2d3\Objectbladen\00_Illustraties\illustraties_ondersteunendWegdeel_v\gesloten verharding asfalt A en C\asfalt.jpg)
 |
 |groenvoorziening bodembedekkers|![groenvoorziening bodembedekkers](D:\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.2d3\Objectbladen\00_Illustraties\illustraties_ondersteunendWegdeel_v\groenvoorziening bodembedekkers\BTDl_fysiekvoorkomen_groenvoorziening_plusbodembedekkers.jpg)
 |
 |groenvoorziening bosplantsoen | ![groenvoorziening bosplantsoen ](D:\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.2d3\Objectbladen\00_Illustraties\illustraties_ondersteunendWegdeel_v\groenvoorziening bosplantsoen\BTD_fysiekvoorkomen_groenvoorziening_plusbosplantsoen.jpg)
 |
 |groenvoorziening heesters |![groenvoorziening heesters](D:\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.2d3\Objectbladen\00_Illustraties\illustraties_ondersteunendWegdeel_v\groenvoorziening heesters\BTD_fysiekvoorkomen_groenvoorziening_plusheesters.png)
 |
 |groenvoorziening planten | ![groenvoorziening planten](D:\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.2d3\Objectbladen\00_Illustraties\illustraties_ondersteunendWegdeel_v\groenvoorziening planten\BTD_fysiekvoorkomen_groenvoorziening_plusplanten.jpg)
 |
 |groenvoorziening struikrozen | ![groenvoorziening struikrozen](D:\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.2d3\Objectbladen\00_Illustraties\illustraties_ondersteunendWegdeel_v\groenvoorziening struikrozen\BTD_fysiekvoorkomen_groenvoorziening_plusstruikrozen.jpg)
 |
 |half verhard grasklinkers | ![half verhard grasklinkers](D:\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.2d3\Objectbladen\00_Illustraties\illustraties_ondersteunendWegdeel_v\half verhard grasklinkers\WGD_fysiekvoorkomen_halfverhard_plusgrasklinkers.jpg)
 |
 |open verharding beton element B | ![open verharding beton element B ](D:\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.2d3\Objectbladen\00_Illustraties\illustraties_ondersteunendWegdeel_v\open verharding beton element B\betonelement.jpg)
 |
 |open verharding sierbestrating B en D | ![open verharding sierbestrating B en D ](D:\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.2d3\Objectbladen\00_Illustraties\illustraties_ondersteunendWegdeel_v\open verharding sierbestrating B en D\sierbestrating.jpg)
 |
 |open verharding tegels A | ![open verharding tegels A](D:\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.2d3\Objectbladen\00_Illustraties\illustraties_ondersteunendWegdeel_v\open verharding tegels A\WGD_fysiekvoorkomen_openverharding.jpg)
 |

***
