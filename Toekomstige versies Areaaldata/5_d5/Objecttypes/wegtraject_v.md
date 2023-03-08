ï»¿## AREAALDATA.wegtraject_v

* __Areaaldata model versie:__ 5.0
* __Herkomst Definitie:__ IMBOR/NEN3610
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Vlak
* __Definitie:__ Gebaand gedeelte van het terrein ten behoeve van het verkeer te land, in lengte- en dwarsrichting begrensd door weggrenzen. IMBOR: objecttype:weg
* __MappingBGT:__ x
* __Heeft Z-waarden:__ ENABLED
* __Heeft M-waarden:__ DISABLED

***

|__ATTRIBUUT__                             |__ALIAS__                                             |__DATATYPE (length, precision)__       |__DEFINITIE__ (Oorsprong; Superklasse; Attribuuttype; Enumeratie/Referentie; Verwijzende sleutel; Standaard waarde; Definitie)|
|------                                    |------                                                |------                                 |-----    |
|objectid                                  |objectid                                              |OID(0,0)                               |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ;Default: None; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS.
|globalid                                  |globalid                                              |Globalid(38,0)                         |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ;Default: None; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken.
|ad_id                                     |ad_id                                                 |TEXT(255,0)                            |PNH; AREAALDATA; GUID; ; ;Default: None; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer.
|created_user                              |created_user                                          |TEXT(255,0)                            |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ;Default: None; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS.
|created_date                              |created_date                                          |DATE(15,0)                             |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ;Default: None; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS.
|last_edited_user                          |last_edited_user                                      |TEXT(255,0)                            |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ;Default: None; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS.
|last_edited_date                          |last_edited_date                                      |DATE(15,0)                             |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ;Default: None; Datum van de laatste mutatie, gegenereerd door ArcGIS.
|objectbegintijd                           |objectbegintijd                                       |DATE(9,0)                              |PNH; AREAALDATA; Vrij invoerveld; ; ;Default: None; Datum waarop het object bij de bronhouder is ontstaan.
|objecteindtijd                            |objecteindtijd                                        |DATE(9,0)                              |PNH; AREAALDATA; Vrij invoerveld; ; ;Default: None; Datum waarop het object bij de bronhouder niet meer geldig is.
|verwerkingsstatus                         |verwerkingsstatus                                     |TEXT(255,0)                            |PNH; AREAALDATA; Enumeratie; keuzelijst [verwerkingsstatus]; ;Default: None; Status van de gegevens.
|dataleverancier                           |dataleverancier                                       |TEXT(255,0)                            |PNH; AREAALDATA; Vrij invoerveld; ; ;Default: None; Leverancier van de data.
|opmerking                                 |opmerking                                             |TEXT(3000,0)                           |PNH; AREAALDATA; Vrij invoerveld; ; ;Default: None; Algemene opmerking voor het object, zoals een omschrijving of toelichting.
|beheerder                                 |beheerder                                             |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerObjectBeheerder]; ; Default: None; Een publiekrechtelijke instantie of (rechts)persoon die toeziet op de instandhouding van o.a. een object, kunstwerk of waterstaatswerk. De typen beheerder zijn conform de indeling in bronhouders (BGT).
|beheerder_ad4                             |beheerder ad4                                         |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerObjectBeheerderAD4]; ; Default: None; Een publiekrechtelijke instantie of (rechts)persoon die toeziet op de instandhouding van o.a. een object, kunstwerk of waterstaatswerk. De typen beheerder zijn conform de indeling in bronhouders (BGT).
|beheerder_detail                          |beheerder gedetailleerd                               |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerObjectBeheerderDetail]; ; Default: None; Nadere aanduiding van de beheerder van het beheerobject.
|beheergebied                              |beheergebied                                          |TEXT(255,0)                            |IMBOR; Gebiedsindeling; Enumeratie/Referentie; keuzelijst [Beheergebied]; Verwijzende sleutel naar [gebiedscontractregio_v]; Default: None; Verwijzende sleutel naar gebiedscontractregio_v. Functionele laag. De provincie heeft haar gebied in 8 gebieden opgesplitst. Amsterdam (gebied 8) is zelfstandig.
|conversie_id                              |conversie id                                          |TEXT(255,0)                            |IMBOR; ReÃ«elObject; Vrij invoerveld; ; ; Default: None; Uniek kenmerk van een beheerobject uit een oude beheerindeling.
|gebiedscontractregio                      |gebiedscontractregio                                  |TEXT(255,0)                            |PNH; Gebiedsindeling; Enumeratie/Referentie; keuzelijst [GCRnaam]; ; Default: None; De provincie heeft haar gebied in 8 gebieden opgesplitst. Amsterdam (gebied 8) is zelfstandig. Er zijn geen beheerobjecten in Areaaldata.
|gisib_id                                  |gisib_id                                              |TEXT(255,0)                            |PNH; Areaaldata; Waarde wordt automatisch bepaald; ; ; Default: None; wordt aangemaakt in GISIB
|objectnaam                                |objectnaam                                            |TEXT(255,0)                            |IMBOR; ReÃ«elObject; Vrij invoerveld; ; ; Default: None; Naam van het beheerobject.
|omtrek                                    |omtrek                                                |DOUBLE(10,3)                           |PNH; Geo-object; Vrij invoerveld; ; ; Default: None; Omtrek in meters, dit wordt automatisch gevuld uit SHAPE_Length
|oppervlakte                               |oppervlakte                                           |DOUBLE(10,3)                           |PNH; Geo-object; Vrij invoerveld; ; ; Default: None; Oppervlakte in m2, dit wordt automatisch gevuld uit SHAPE_Area
|traject_nummer                            |traject nummer                                        |TEXT(255,0)                            |PNH; Gebiedsindeling; Enumeratie/Referentie; keuzelijst [Trajectnummer]; ; Default: None; traject; N-nummer
|trajectwegen                              |trajectwegen                                          |TEXT(255,0)                            |PNH; Gebiedsindeling; Enumeratie/Referentie; keuzelijst [Trajectwegen]; ; Default: None; Omschrijving van de verharde/weg-trajecten
|tweede_beheerder                          |tweede beheerder                                      |TEXT(255,0)                            |IMBOR; Beheerd object; Vrij invoerveld; ; ; Default: None; Registratie van de tweede beheerder in geval van gedeeld beheer.
|typespec                                  |typespec                                              |TEXT(255,0)                            |PNH; Gebruik; Enumeratie/Referentie; keuzelijst [TypespecTraject]; ; Default: None; Omschrijving van de type traject
|wegtype                                   |wegtype                                               |TEXT(255,0)                            |IMBOR; Gebruik; Enumeratie/Referentie; keuzelijst [Wegtype]; ; Default: None; Classificatie van een weg naar verkeersfunctie binnen het totale netwerk van wegen, die als zodanig voor de weggebruiker goed herkenbaar zijn.
|wegtype_ad4                               |wegtype ad4                                           |TEXT(255,0)                            |PNH; Gebruik; Enumeratie/Referentie; keuzelijst [WegtypeAD4]; ; Default: None; Classificatie van een weg naar verkeersfunctie binnen het totale netwerk van wegen, die als zodanig voor de weggebruiker goed herkenbaar zijn.

***

