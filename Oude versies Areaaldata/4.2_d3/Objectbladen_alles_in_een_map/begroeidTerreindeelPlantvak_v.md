## AREAALDATA.begroeidTerreindeelPlantvak_v

*Feature dataset: Opdelend*


* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 25 cm
* __Geometrie:__ Vlak
* __Definitie:__ Terreindeel met aangelegde beplanting, meestal planten, heesters of struiken. BGT Begroeid Terreindeel. 
* __Mapping_BGT:__ begroeidTerreindeel_v
* __Mapping_Gisib:__ Plantvak

***

|__KOLOM__                         |__TYPE (length, precision, scale)__          	|__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                            |----          	                                |-----    |
|OBJECTID                          |OID(38,0,0)                                     |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                          |GlobalID(38,0,0)                                |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: No|
|AD_ID                             |String(255,0,0)                                 |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                          |Integer(0,10,0)                                 |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                     |String(255,0,0)                                 |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                 |String(255,0,0)                                 |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|STATUS                            |String(10,0,0)                                  |BGT; BGT status van het object; keuzelijst [status]; Nullable: False; Default: bestaand; Visible: No|
|OBJECTBEGINTIJD                   |Date(8,0,0)                                     |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                    |Date(8,0,0)                                     |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING            |SmallInteger(0,5,0)                             |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                         |String(255,0,0)                                 |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                       |String(255,0,0)                                 |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                          |String(255,0,0)                                 |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|BRONHOUDER                        |String(5,0,0)                                   |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None; Visible: No|
|TYPESPEC                          |String(255,0,0)                                 |PNH; Nadere typering van het object; keuzelijst [typeSpecBTDPlantvak]; Nullable: True; Default: None; Visible: Yes|
|FYSIEKVOORKOMEN                   |String(50,0,0)                                  |BGT; Fysieke omschrijving van het object; keuzelijst [fysiekVoorkomenBTDP]; Nullable: False; Default: groenvoorziening:bosplantsoen; Visible: No|
|OPTALUD                           |String(1,0,0)                                   |BGT; Ligt het object op een talud? Ja/Nee/Onbekend. Bij 'Ja', moet er een begroeidTerreindeelPlKr_l geregistreerd zijn; keuzelijst [OPTALUD]; Nullable: False; Default: N; Visible: No|
|GRONDSOORT                        |String(255,0,0)                                 |PNH; Grondsoort; keuzelijst [GRONDSOORT]; Nullable: True; Default: None; Visible: No|
|HMBEGIN                           |Float(0,25,10)                                  |PNH; Hectometrering begin heg; ; Nullable: True; Default: None; Visible: No|
|HMEIND                            |Float(0,25,10)                                  |PNH; Hectometrering eind heg; ; Nullable: True; Default: None; Visible: No|
|ACTUEELBEELD                      |String(255,0,0)                                 |PNH; Huidige beeld; ; Nullable: True; Default: None; Visible: No|
|STREEFBEELD                       |String(255,0,0)                                 |PNH; Concrete visuele doelstelling; ; Nullable: True; Default: None; Visible: No|
|PLANJAAR                          |SmallInteger(0,5,0)                             |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|DATUMAANPLANTING                  |Date(8,0,0)                                     |PNH; Jaar aanplanting; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                         |String(255,0,0)                                 |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|TYPEPLAAGINVASIESOORT             |String(255,0,0)                                 |PNH; Type plaagsoort. Indien op een bermperceel Japanse duizendknoop voor komt, dan wordt deze ingevuld, ongeacht het oppervlak of aantal ten opzichte van andere soorten uit de domeinlijst. Komt er geen Japanse duizendknoop voor op een perceel, dan wordt de soort ingevuld die geschat qua oppervlak het meeste voorkomt in dat perceel; keuzelijst [TYPE_PLAAGSOORT_LAND]; Nullable: True; Default: None; Visible: Yes|
|TRAJECT                           |String(255,0,0)                                 |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM]; Nullable: True; Default: None; Visible: Yes|
|OEVERVAK                          |String(255,0,0)                                 |PNH; Verwijzende sleutel naar oevervak_v (simpel), als deze aan een vaarweg ligt; ; Nullable: True; Default: None; Visible: Yes|
|INONDERZOEK                       |String(1,0,0)                                   |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible: No|
|TIJDSTIPREGISTRATIE               |Date(8,0,0)                                     |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|EINDREGISTRATIE                   |Date(8,0,0)                                     |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|LV_PUBLICATIEDATUM                |Date(8,0,0)                                     |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BERICHT_ID                        |String(128,0,0)                                 |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                   |String(255,0,0)                                 |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                      |String(255,0,0)                                 |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                      |Date(8,0,0)                                     |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                  |String(50,0,0)                                  |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                  |Date(8,0,0)                                     |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                             |Geometry(0,0,0)                                 |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                      |Double(0,0,0)                                   |PNH; Omtrek in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|SHAPE_Area                        |Double(0,0,0)                                   |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|OMTREK                            |Double(0,0,0)                                   |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|
|OPPERVLAKTE                       |Double(0,0,0)                                   |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Area; ; Nullable: False; Default: None; Visible: Yes|


### Illustraties van verschillende fysieke voorkomens:

 
 |__Fysiek voorkomen__ | __Illustratie__ |
 |-----------------------------------------|----|
 |groenvoorziening bodembedekkers|![groenvoorziening bodembedekkers](D:\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.2d3\Objectbladen\00_Illustraties\illustraties_begroeidTerreindeelPlantvak_v\FysiekVoorkomenBTD\groenvoorziening_bodembedekkers\BTD_fysvoork_groenvoorz_plusbodembedekkers.jpg)
 |
 |groenvoorziening bosplantsoen | ![groenvoorziening bosplantsoen ](D:\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.2d3\Objectbladen\00_Illustraties\illustraties_begroeidTerreindeelPlantvak_v\FysiekVoorkomenBTD\groenvoorziening_bosplantsoen\BTD_fysvoork_groenvoorz_plusbosplantsoen.jpg)
 |
 |groenvoorziening heesters |![groenvoorziening heesters](D:\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.2d3\Objectbladen\00_Illustraties\illustraties_begroeidTerreindeelPlantvak_v\FysiekVoorkomenBTD\groenvoorziening_heesters\BTD_fysvoork_groenvoorz_plusheesters.png)
 |
 |groenvoorziening planten | ![groenvoorziening planten](D:\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.2d3\Objectbladen\00_Illustraties\illustraties_begroeidTerreindeelPlantvak_v\FysiekVoorkomenBTD\groenvoorziening_planten\BTD_fysvoork_groenvoorz_plusplanten.jpg)
 |
 |groenvoorziening struikrozen | ![groenvoorziening struikrozen](D:\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.2d3\Objectbladen\00_Illustraties\illustraties_begroeidTerreindeelPlantvak_v\FysiekVoorkomenBTD\groenvoorziening_struikrozen\BTD_fysvoork_groenvoorz_plusstruikrozen.jpg)
 


***
