﻿## AREAALDATA.wegmarkering_tbl

* __Areaaldata model versie:__ 5.0
* __Herkomst Definitie:__ IMBOR/NEN3610
* __Positionele nauwkeurigheid:__ 7,5 cm (NB, groter dan BGT)
* __Geometrie:__ n.v.t.
* __Definitie:__ Tabel; Wegmarkering is het geheel aan tekens die op het wegdek staan aangegeven en het verkeer door middel van de visuele informatie geleiden. Wegmarkering omvat onder meer pijlen, strepen, doorgetrokken en onderbroken lijnen, haaientanden.
* __MappingBGT:__ x
* __Heeft Z-waarden:__ ENABLED
* __Heeft M-waarden:__ DISABLED

***

|__ATTRIBUUT__                             |__ALIAS__                                         |__DATATYPE (length, precision)__       |__DEFINITIE__ (Oorsprong; Superklasse; Attribuuttype; Enumeratie/Referentie; Verwijzende sleutel; Standaard waarde; Definitie)|
|------                                    |------                                            |------                                 |-----    |
|objectid                                  |objectid                                          |OID(0,0)                               |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS.
|globalid                                  |globalid                                          |Globalid(38,0)                         |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken.
|ad_id                                     |ad_id                                             |TEXT(255,0)                            |PNH; AREAALDATA; GUID; ; ; Default: None; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer.
|created_user                              |created_user                                      |TEXT(255,0)                            |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS.
|created_date                              |created_date                                      |DATE(15,0)                             |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS.
|last_edited_user                          |last_edited_user                                  |TEXT(255,0)                            |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS.
|last_edited_date                          |last_edited_date                                  |DATE(15,0)                             |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Datum van de laatste mutatie, gegenereerd door ArcGIS.
|objectbegintijd                           |objectbegintijd                                   |DATE(9,0)                              |PNH; AREAALDATA; Vrij invoerveld; ; ; Default: None; Datum waarop het object bij de bronhouder is ontstaan.
|objecteindtijd                            |objecteindtijd                                    |DATE(9,0)                              |PNH; AREAALDATA; Vrij invoerveld; ; ; Default: None; Datum waarop het object bij de bronhouder niet meer geldig is.
|verwerkingsstatus                         |verwerkingsstatus                                 |TEXT(255,0)                            |PNH; AREAALDATA; Enumeratie; keuzelijst [Verwerkingsstatus]; ; Default: None; Status van de gegevens.
|dataleverancier                           |dataleverancier                                   |TEXT(255,0)                            |PNH; AREAALDATA; Vrij invoerveld; ; ; Default: None; Leverancier van de data.
|opmerking                                 |opmerking                                         |TEXT(3000,0)                           |PNH; AREAALDATA; Vrij invoerveld; ; ; Default: None; Algemene opmerking voor het object, zoals een omschrijving of toelichting.
|beheerafspraak                            |beheerafspraak                                    |TEXT(255,0)                            |IMBOR; Beheerd object; Vrij invoerveld; ; ; Default: None; Attribuut voor het vermelden van aanvullende afspraken over het beheer van een object of voor het vermelden van specificaties van de beheersituatie van een object.
|beheerder                                 |beheerder                                         |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectBeheerder]; ; Default: None; Een publiekrechtelijke instantie of (rechts)persoon die toeziet op de instandhouding van o.a. een object, kunstwerk of waterstaatswerk. De typen beheerder zijn conform de indeling in bronhouders (BGT).
|bouwjaar                                  |bouwjaar                                          |SHORT(5,0)                             |IMBOR; Constructie; Vrij invoerveld; ; ; Default: None; Bouwjaar van het object. Deze kan afwijken van het jaar van aanleg, bijvoorbeeld wanneer een beheerobject hergebruikt wordt.
|eigenaar                                  |eigenaar                                          |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectEigenaar]; ; Default: None; (Rechts)persoon die het meest omvattend recht op een zaak heeft. De typen eigenaren zijn conform de indeling in bronhouders (BGT).
|fabrikant                                 |fabrikant                                         |TEXT(255,0)                            |IMBOR; Constructie; Vrij invoerveld; ; ; Default: None; Fabrikant van het beheerobject.
|gisib_id                                  |gisib_id                                          |TEXT(255,0)                            |PNH; Areaaldata; Waarde wordt automatisch bepaald; ; ; Default: None; wordt aangemaakt in GISIB
|jaar_van_aanleg                           |jaar van aanleg                                   |SHORT(5,0)                             |IMBOR; ReëelObject; Vrij invoerveld; ; ; Default: None; Jaar waarin het beheerobject is aangelegd (kan ook voor de plaatsingsdatum gebruikt worden).
|kleur                                     |kleur                                             |TEXT(255,0)                            |IMBOR; Constructie; Enumeratie/Referentie; keuzelijst [ConstructieKleur]; ; Default: None; Kleur van het beheerobject.
|leverancier                               |leverancier                                       |TEXT(255,0)                            |IMBOR; Constructie; Vrij invoerveld; ; ; Default: None; Leverancier van het beheerobject.
|markering_toepassing                      |markering toepassing                              |TEXT(255,0)                            |IMBOR; Wegmarkering; Enumeratie/Referentie; keuzelijst [WegmarkeringMarkeringToepassing]; ; Default: None; Registratie van de toepassing van de wegmarkering.
|markeringbreedte                          |markeringbreedte                                  |TEXT(255,0)                            |IMBOR; Wegmarkering; Enumeratie/Referentie; keuzelijst [WegmarkeringMarkeringsbreedte]; ; Default: None; Standaardbreedtes van lijnmarkeringen.
|markeringspatroon                         |markeringspatroon                                 |TEXT(255,0)                            |IMBOR; Wegmarkering; Enumeratie/Referentie; keuzelijst [WegmarkeringMarkeringspatroon]; ; Default: None; Patronen van dwars- en lengtemarkeringen.
|materiaal                                 |materiaal                                         |TEXT(255,0)                            |PNH; Wegmarkering; Enumeratie/Referentie; keuzelijst [Markeringsmateriaal]; ; Default: None; Het materiaal van de belijning
|onderhoudsplichtige                       |onderhoudsplichtige                               |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectOnderhouder]; ; Default: None; Organisatie die verantwoordelijk is voor het onderhoud van het beheerobject.
|reflectie                                 |reflectie                                         |TEXT(3,0)                              |IMBOR; Wegmarkering; Ja/Nee; ; ; Default: None; is de belijning reflecterend?
|theoretiche_eindjaar                      |theoretische eindjaar                             |SHORT(5,0)                             |IMBOR; ReëelObject; Vrij invoerveld; ; ; Default: None; Jaar dat het beheerobject aan het theoretische einde van haar levensduur is.
|tijdelijk                                 |tijdelijk                                         |TEXT(3,0)                              |PNH; Wegmarkering; Ja/Nee; ; ; Default: None; is de belijning tijdelijk aangebracht?
|type                                      |markeringstype                                    |TEXT(255,0)                            |IMBOR; Wegmarkering; Enumeratie/Referentie; keuzelijst [WegmarkeringType]; ; Default: None; Typering van het beheerobject.
|type_extra_gedetailleerd                  |markeringstype extra gedetailleerd                |TEXT(255,0)                            |IMBOR; Wegmarkering; Enumeratie/Referentie; keuzelijst [WegmarkeringTypeExtraGedetailleerd]; ; Default: None; Extra typering van het beheerobject, nadere typering van type gedetailleerd.
|type_gedetailleerd                        |markeringstype gedetailleerd                      |TEXT(255,0)                            |IMBOR; Wegmarkering; Enumeratie/Referentie; keuzelijst [WegmarkeringTypeGedetailleerd]; ; Default: None; Nadere typering van het type beheerobject.
|wegdeel                                   |wegdeel                                           |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; Verwijzende sleutel naar [verharding_v]; Default: None; Verwijzende sleutel naar verharding_v. De wegdeel waarop de belijning is aangebracht

***
