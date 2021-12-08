## AREAALDATA.wegdeel_v

*Feature dataset: Opdelend*


* __Areaaldata model versie:__ 4.2
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
|GLOBALID                          |GlobalID(38,0,0)                               |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: No|
|AD_ID                             |String(255,0,0)                                |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                          |Integer(0,10,0)                                |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                     |String(255,0,0)                                |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                 |String(255,0,0)                                |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.html); Nullable: False; Default: Nieuw; Visible: Yes|
|STATUS                            |String(10,0,0)                                 |BGT; BGT status van het object; keuzelijst [status](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/status.html); Nullable: False; Default: bestaand; Visible: No|
|OBJECTBEGINTIJD                   |Date(8,0,0)                                    |PNH; Datum waarop het object voor het eerst volgens het areaaldata datamodel wordt vastgelegd ; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                    |Date(8,0,0)                                    |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING            |SmallInteger(0,5,0)                            |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                         |String(255,0,0)                                |PNH; Beheerder van het object; keuzelijst [BEHEERDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEERDER.html); Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                       |String(255,0,0)                                |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ONDERHOUDER.html); Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                          |String(255,0,0)                                |PNH; Eigenaar van het object; keuzelijst [INSTANTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/INSTANTIE.html); Nullable: True; Default: None; Visible: Yes|
|BRONHOUDER                        |String(5,0,0)                                  |BGT; De bronhoudercode van het object; keuzelijst [bronhouder](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/bronhouder.html); Nullable: False; Default: None; Visible: No|
|TYPESPEC                          |String(255,0,0)                                |PNH; Nadere typering van het object; keuzelijst [typeSpecWGD](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecWGD.html); Nullable: True; Default: None; Visible: Yes|
|FYSIEKVOORKOMEN                   |String(50,0,0)                                 |BGT; Fysieke omschrijving van het object; keuzelijst [fysiekVoorkomenWGD](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/fysiekVoorkomenWGD.html); Nullable: False; Default: None; Visible: Yes|
|FUNCTIE                           |String(50,0,0)                                 |BGT; Functionele omschrijving van het object; keuzelijst [functieWGD](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/functieWGD.html); Nullable: False; Default: None; Visible: Yes|
|OPTALUD                           |String(1,0,0)                                  |BGT; Ligt het object op een talud? Ja/Nee/Onbekend. Bij 'Ja', moet er een wegdeelKruin_l geregistreerd zijn; keuzelijst [OPTALUD](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/OPTALUD.html); Nullable: False; Default: N; Visible: No|
|BREEDTE                           |Float(0,25,10)                                 |PNH; Breedte van het wegvakonderdeel (m, 2 decimalen); ; Nullable: True; Default: None; Visible: No|
|COMFORT                           |String(255,0,0)                                |PNH; Dit attribuut wordt automatisch afgeleid uit de laatste crowmeting. Zie crowMeting_tbl; ; Nullable: True; Default: None; Visible: No|
|COMFORT_DATE                      |Date(8,0,0)                                    |PNH; Dit attribuut wordt automatisch afgeleid uit de laatste crowmeting. Zie crowMeting_tbl; ; Nullable: True; Default: None; Visible: No|
|DEFLECTIE                         |String(255,0,0)                                |PNH; Dit attribuut wordt automatisch afgeleid uit de laatste crowmeting. Zie crowMeting_tbl; ; Nullable: True; Default: None; Visible: No|
|DEFLECTIE_DATE                    |Date(8,0,0)                                    |PNH; Dit attribuut wordt automatisch afgeleid uit de laatste crowmeting. Zie crowMeting_tbl; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                         |String(255,0,0)                                |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|KOMGRENS                          |String(255,0,0)                                |PNH; Komgrens o.b.v. de wegenverkeerswet; ; Nullable: True; Default: None; Visible: Yes|
|WEGTYPE                           |String(255,0,0)                                |PNH; Wegtype; keuzelijst [WEGTYPE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/WEGTYPE.html); Nullable: True; Default: None; Visible: Yes|
|WEGINDELING                       |String(255,0,0)                                |PNH; Wegindeling; keuzelijst [WEGINDELING](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/WEGINDELING.html); Nullable: True; Default: None; Visible: No|
|JAARAANLEG                        |SmallInteger(0,5,0)                            |PNH; Jaar aanleg van de weg; ; Nullable: True; Default: None; Visible: No|
|JAARDEKLAAG                       |SmallInteger(0,5,0)                            |PNH; Jaar deklaag gelegd; ; Nullable: True; Default: None; Visible: No|
|JAARHERSTRATEN                    |SmallInteger(0,5,0)                            |PNH; Jaar Herbestrating gelegd; ; Nullable: True; Default: None; Visible: No|
|JAARVERNIEUWEN                    |SmallInteger(0,5,0)                            |PNH; TODO; ; Nullable: True; Default: None; Visible: No|
|LANGSONVLAKHEID                   |String(255,0,0)                                |PNH; Dit attribuut wordt automatisch afgeleid uit de laatste crowmeting. Zie crowMeting_tbl; ; Nullable: True; Default: None; Visible: No|
|LANGSONVLAKHEID_DATE              |Date(8,0,0)                                    |PNH; Dit attribuut wordt automatisch afgeleid uit de laatste crowmeting. Zie crowMeting_tbl; ; Nullable: True; Default: None; Visible: No|
|DWARSONVLAKHEID                   |String(255,0,0)                                |PNH; Dit attribuut wordt automatisch afgeleid uit de laatste crowmeting. Zie crowMeting_tbl; ; Nullable: True; Default: None; Visible: No|
|DWARSONVLAKHEID_DATE              |Date(8,0,0)                                    |PNH; Dit attribuut wordt automatisch afgeleid uit de laatste crowmeting. Zie crowMeting_tbl; ; Nullable: True; Default: None; Visible: No|
|INSPECTEUR                        |String(255,0,0)                                |PNH; Dit attribuut wordt automatisch afgeleid uit de laatste crowmeting. Inspecterende partij spoorvorming, langsonvlakheid, dwarsonvlakheid.; ; Nullable: True; Default: None; Visible: No|
|LENGTE                            |Float(0,10,0)                                  |PNH; Lengte van het wegvakonderdeel (hele meters); ; Nullable: True; Default: None; Visible: Yes|
|LENGTEVOEGEN                      |SmallInteger(0,5,0)                            |PNH; Lengte van de voegen (m); ; Nullable: True; Default: None; Visible: Yes|
|SPOORVORMING                      |String(20,0,0)                                 |PNH; Dit attribuut wordt automatisch afgeleid uit de laatste crowmeting. Waarde van de spoorvormingmeting; ; Nullable: True; Default: None; Visible: No|
|SPOORVORMING_DATE                 |Date(8,0,0)                                    |PNH; Dit attribuut wordt automatisch afgeleid uit de laatste crowmeting. Datum spoorvorming meting; ; Nullable: True; Default: None; Visible: No|
|GEBRUIKSFUNCTIE                   |String(255,0,0)                                |PNH; Gebruiksfunctie conform CROW; keuzelijst [GEBRUIKSFUNCTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/GEBRUIKSFUNCTIE.html); Nullable: True; Default: None; Visible: Yes|
|SITUERING                         |String(255,0,0)                                |PNH; Situering conform CROW (L: Links, M: Midden en R: Rechts); keuzelijst [SITUERING](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/SITUERING.html); Nullable: True; Default: None; Visible: Yes|
|STROEFHEID                        |String(20,0,0)                                 |PNH; Dit attribuut wordt automatisch afgeleid uit de laatste crowmeting; ; Nullable: True; Default: None; Visible: No|
|STROEFHEID_DATE                   |Date(8,0,0)                                    |PNH; Dit attribuut wordt automatisch afgeleid uit de laatste crowmeting; ; Nullable: True; Default: None; Visible: No|
|VERHARDING                        |String(255,0,0)                                |PNH; Verharding object conform CROW; keuzelijst [VERHARDING](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERHARDING.html); Nullable: True; Default: None; Visible: No|
|VERHARDINGCATEGORIE               |String(255,0,0)                                |PNH; Verharding categorie conform CROW; keuzelijst [VERHARDING_CATEGORIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERHARDING_CATEGORIE.html); Nullable: True; Default: None; Visible: Yes|
|WGV_AFSTANDTOT                    |Float(0,25,10)                                 |PNH; Wegvak, Aanduiding bij welk wegindexeringspaal (hectometerpaal) het inspectievak eindigt; ; Nullable: True; Default: None; Visible: No|
|WGV_AFSTANDVAN                    |Float(0,25,10)                                 |PNH; Wegvak, Aanduiding bij welk wegindexeringspaal (hectometerpaal) het inspectievak begint; ; Nullable: True; Default: None; Visible: No|
|WGV_NUMMER                        |SmallInteger(0,5,0)                            |PNH; Wegvak, Wegvak nummer, uniek per weg; ; Nullable: True; Default: None; Visible: Yes|
|VERLICHT                          |String(10,0,0)                                 |PNH; Verlicht: Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNeeOnbekend.html); Nullable: True; Default: O ; Visible: No|
|HECTOMETER                        |String(255,0,0)                                |PNH; Hectometrering; ; Nullable: True; Default: None; Visible: Yes|
|HALTE                             |String(255,0,0)                                |PNH; Verwijzende sleutel naar halte_v (simpel); ; Nullable: True; Default: None; Visible: No|
|WEGVAK                            |String(255,0,0)                                |PNH; Verwijzende sleutel naar wegvak_v (simpel); ; Nullable: True; Default: None; Visible: No|
|TRAJECT                           |String(255,0,0)                                |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/TRAJECT_NAAM.html); Nullable: True; Default: None; Visible: Yes|
|INONDERZOEK                       |String(1,0,0)                                  |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.html); Nullable: False; Default: None; Visible: No|
|TIJDSTIPREGISTRATIE               |Date(8,0,0)                                    |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|EINDREGISTRATIE                   |Date(8,0,0)                                    |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|LV_PUBLICATIEDATUM                |Date(8,0,0)                                    |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BERICHT_ID                        |String(128,0,0)                                |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                   |String(255,0,0)                                |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                      |String(255,0,0)                                |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                      |Date(8,0,0)                                    |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                  |String(50,0,0)                                 |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                  |Date(8,0,0)                                    |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                             |Geometry(0,0,0)                                |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                      |Double(0,0,0)                                  |PNH; Omtrek in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|SHAPE_Area                        |Double(0,0,0)                                  |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|OMTREK                            |Double(0,0,0)                                  |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|
|OPPERVLAKTE                       |Double(0,0,0)                                  |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Area; ; Nullable: False; Default: None; Visible: Yes|

### Illustraties van verschillende fysieke voorkomens:

 
 |__Fysiek voorkomen__ | __Illustratie__ |
 |-----------------------------------------|----|
 |gesloten verharding asfalt A en C |![gesloten verharding asfalt A en C ](https://github.com/provincieNH/Leveren_Geoinformatie/raw/master/4.3_d4/Objectbladen\00_Illustraties\illustraties_wegdeel_v\fysiekVoorkomenWGD\gesloten verharding asfalt A en C\asfalt.jpg)
 |
 |half verhard grasklinkers |![half verhard grasklinkers](https://github.com/provincieNH/Leveren_Geoinformatie/raw/master/4.3_d4/Objectbladen\00_Illustraties\illustraties_wegdeel_v\fysiekVoorkomenWGD\half verhard grasklinkers\wegdeel_fysiekvoorkomen_halfverhard_plusgrasklinkers.jpg)
 |
 |open verharding beton element C | ![open verharding beton element C](https://github.com/provincieNH/Leveren_Geoinformatie/raw/master/4.3_d4/Objectbladen\00_Illustraties\illustraties_wegdeel_v\fysiekVoorkomenWGD\open verharding beton element C\wegdeel_fysiekvoorkomen_openverharding.jpg)
 |
 |open verharding sierbestrating B en C |![open verharding sierbestrating B en C ](https://github.com/provincieNH/Leveren_Geoinformatie/raw/master/4.3_d4/Objectbladen\00_Illustraties\illustraties_wegdeel_v\fysiekVoorkomenWGD\open verharding sierbestrating B en D\sierbestrating.jpg)
 |
 |open verharding tegels A | ![open verharding tegels A](https://github.com/provincieNH/Leveren_Geoinformatie/raw/master/4.3_d4/Objectbladen\00_Illustraties\illustraties_wegdeel_v\fysiekVoorkomenWGD\open verharding tegels A\wegdeel_fysiekvoorkomen_openverharding.jpg)
 |
 |gecombineerd fietspad rijstrook | ![gecombineerd fietspad rijstrook](https://github.com/provincieNH/Leveren_Geoinformatie/raw/master/4.3_d4/Objectbladen\00_Illustraties\illustraties_wegdeel_v\fysiekVoorkomenWGD\gecombineerd fietspad rijstrook\gecombineerd_fietspad_rijstrook.PNG)
 |
 
 ### Illustratie van Situering
 |Situering | ![Situering](https://github.com/provincieNH/Leveren_Geoinformatie/raw/master/4.3_d4/Objectbladen\00_Illustraties\illustraties_wegdeel_v\Situering\Situering.jpg)
 |
***

