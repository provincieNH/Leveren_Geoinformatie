## AREAALDATA.weg_v

* __Areaaldata model versie:__ 5
* __Herkomst Definitie:__ IMBOR/NEN3610
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Vlak
* __Definitie:__ Functioneel; Gebaand gedeelte van het terrein ten behoeve van het verkeer te land, in lengte- en dwarsrichting begrensd door weggrenzen. IMBOR zegt weg (traject)  en water (vaarwegdeeltraject)
* __MappingBGT:__ x
* __Heeft Z-waarden:__ ENABLED
* __Heeft M-waarden:__ DISABLED

***

|__ATTRIBUUT__                             |__ALIAS__                                            |__DATATYPE (length, precision)__       |__DEFINITIE__ (Oorsprong; Superklasse; Attribuuttype; Enumeratie/Referentie; Verwijzende sleutel; Standaard waarde; Definitie)|
|------                                    |------                                               |------                                 |-----    |
|objectid                                  |objectid                                             |OID(0,0)                               |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS.
|globalid                                  |globalid                                             |Globalid(38,0)                         |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken.
|ad_id                                     |ad_id                                                |TEXT(255,0)                            |PNH; AREAALDATA; GUID; ; ; Default: None; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer.
|created_user                              |created_user                                         |TEXT(255,0)                            |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS.
|created_date                              |created_date                                         |DATE(15,0)                             |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS.
|last_edited_user                          |last_edited_user                                     |TEXT(255,0)                            |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS.
|last_edited_date                          |last_edited_date                                     |DATE(15,0)                             |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Datum van de laatste mutatie, gegenereerd door ArcGIS.
|objectbegintijd                           |objectbegintijd                                      |DATE(9,0)                              |PNH; AREAALDATA; Vrij invoerveld; ; ; Default: None; Datum waarop het object bij de bronhouder is ontstaan.
|objecteindtijd                            |objecteindtijd                                       |DATE(9,0)                              |PNH; AREAALDATA; Vrij invoerveld; ; ; Default: None; Datum waarop het object bij de bronhouder niet meer geldig is.
|verwerkingsstatus                         |verwerkingsstatus                                    |TEXT(255,0)                            |PNH; AREAALDATA; Enumeratie; keuzelijst [Verwerkingsstatus]; ; Default: None; Status van de gegevens.
|dataleverancier                           |dataleverancier                                      |TEXT(255,0)                            |PNH; AREAALDATA; Vrij invoerveld; ; ; Default: None; Leverancier van de data.
|opmerking                                 |opmerking                                            |TEXT(3000,0)                           |PNH; AREAALDATA; Vrij invoerveld; ; ; Default: None; Algemene opmerking voor het object, zoals een omschrijving of toelichting.
|st_area(shape)                            |st_area                                              |DOUBLE(0,0)                            |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Oppervlakte van het beheerobject in m2.
|st_perimeter(shape)                       |st_perimeter                                         |DOUBLE(0,0)                            |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Omtrek van het beheerobject in meters.
|aanlegjaar                                |aanlegjaar                                           |SHORT(5,0)                             |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Het Is het jaar van aanleg van de (vaar)weg
|beheerder                                 |beheerder                                            |TEXT(255,0)                            |IMBOR; Areaaldata; Enumeratie/Referentie; keuzelijst [BeheerdObjectBeheerder]; ; Default: None; Een publiekrechtelijke instantie of (rechts)persoon die toeziet op de instandhouding van o.a. een object, kunstwerk of waterstaatswerk. De typen beheerder zijn conform de indeling in bronhouders (BGT).
|beheergebied                              |beheergebied                                         |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [GCR_NAAM]; Verwijzende sleutel naar [gebiedscontractregio_v]; Default: None; Verwijzende sleutel naar gebiedscontractregio_v. Functionele laag. De provincie heeft haar gebied in 8 gebieden opgesplitst. Amsterdam (gebied 8) is zelfstandig.
|breedte                                   |breedte (m)                                          |FLOAT(6,2)                             |IMBOR; Areaaldata; Vrij invoerveld; ; ; Default: None; Breedte van het beheerobject.
|geldende_beeldkwaliteit                   |geldende beeldkwaliteit                              |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [Beeldkwaliteit]; ; Default: None; Concrete visuele doelstelling
|gisib_id                                  |gisib_id                                             |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; wordt aangemaakt in GISIB
|hoofdroute_deelcode                       |hoofdroute deelcode                                  |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [Hoofdroute deelcode]; ; Default: None; Uniek code ter identificatie van een deeltraject; bijvoorbeeld N196a of N242b_1
|lengte                                    |lengte (m)                                           |FLOAT(6,2)                             |IMBOR; Areaaldata; Vrij invoerveld; ; ; Default: None; Lengte van het beheerobject.
|theoretisch_eindjaar                      |theoretisch eindjaar                                 |SHORT(5,0)                             |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Jaar dat het beheerobject aan het theoretische einde van haar levensduur is.
|type                                      |type hoofdroute                                      |TEXT(255,0)                            |IMBOR; Areaaldata; Enumeratie/Referentie; keuzelijst [WegcategorieDuurzaamVeilig]; ; Default: None; Typering van het beheerobject
|type_gedetailleerd                        |type hoofdroute gedetailleerd                        |TEXT(255,0)                            |IMBOR; Areaaldata; Enumeratie/Referentie; keuzelijst [WegcategorieDuurzaamVeiligGedetailleerd]; ; Default: None; Nader typering van het type beheerobject
|wegindeling                               |wegindeling                                          |TEXT(255,0)                            |IMBOR; Areaaldata; Enumeratie/Referentie; keuzelijst [Wegindeling]; ; Default: None; Aanduiding voor de indeling van de weg rijbanen en rijstroken.
|wegnummer                                 |wegnummer                                            |TEXT(255,0)                            |IMBOR; Areaaldata; Enumeratie/Referentie; keuzelijst [Wegnummer]; ; Default: None; Aanduiding van de weg, bijvoorbeeld N505 voor een provinciale weg.

***

