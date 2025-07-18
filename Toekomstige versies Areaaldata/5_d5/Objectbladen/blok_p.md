﻿## AREAALDATA.blok_p

* __Areaaldata model versie:__ 5
* __Herkomst Definitie:__ IMBOR/NEN3610
* __Positionele nauwkeurigheid:__ 7,5 cm (NB, groter dan BGT)
* __Geometrie:__ Punt
* __Definitie:__ Blokvormig element, meestal van beton of steen, bedoeld om een openbare ruimte te verfraaien, achterliggende gebieden te beschermen of te dienen als zit- of speelelement.
* __MappingBGT:__ geen
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
|shape                                     |shape                                                |DOUBLE(0,0)                            |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Locatie van het beheerobject.
|beheerder                                 |beheerder                                            |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectBeheerder]; ; Default: None; Een publiekrechtelijke instantie of (rechts)persoon die toeziet op de instandhouding van o.a. een object, kunstwerk of waterstaatswerk. De typen beheerder zijn conform de indeling in bronhouders (BGT).
|beheerder_gedetailleerd                   |beheerder gedetailleerd                              |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectBeheerderGedetailleerd]; ; Default: None; Nadere aanduiding van de beheerder van het beheerobject.
|beheergebied                              |beheergebied                                         |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [GCR_NAAM]; Verwijzende sleutel naar [gebiedscontractregio_v]; Default: None; Verwijzende sleutel naar gebiedscontractregio_v; Aanduiding van het beheergebied waarbinnen het beheerobject ligt. Indeling in beheergebieden is organisatiespecifiek.
|bgt_objecttype                            |bgtplustype                                          |TEXT(255,0)                            |IMBOR; Geo-object; Enumeratie/Referentie; ; ; Default: None; Specificatie van het BGT/IMGeo-object.
|bouwjaar                                  |bouwjaar                                             |SHORT(5,0)                             |IMBOR; Constructie; Vrij invoerveld; ; ; Default: None; Bouwjaar van het object. Deze kan afwijken van het jaar van aanleg, bijvoorbeeld wanneer een beheerobject hergebruikt wordt.
|eigenaar                                  |eigenaar                                             |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectEigenaar]; ; Default: None; (Rechts)persoon die het meest omvattend recht op een zaak heeft. De typen eigenaren zijn conform de indeling in bronhouders (BGT).
|eigenaar_gedetailleerd                    |eigenaar gedetailleerd                               |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectEigenaarGedetailleerd]; ; Default: None; Nadere aanduiding van de eigenaar van het beheerobject.
|fabrikant                                 |fabrikant                                            |TEXT(255,0)                            |IMBOR; Constructie; Vrij invoerveld; ; ; Default: None; Fabrikant van het beheerobject.
|gisib_id                                  |gisib_id                                             |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; wordt aangemaakt in GISIB
|hoofdroute                                |hoofdroute                                           |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [Hoofdroute]; Verwijzende sleutel naar [weg_v]; Default: None; Verwijzende sleutel naar weg_v; AD_ID foreign key
|leverancier                               |leverancier                                          |TEXT(255,0)                            |IMBOR; Constructie; Vrij invoerveld; ; ; Default: None; Leverancier van het beheerobject.
|ligging                                   |ligging                                              |TEXT(255,0)                            |IMBOR; Gebiedsindeling; Enumeratie/Referentie; keuzelijst [GebiedsindelingLigging]; ; Default: None; Aanduiding van de ligging van het beheerobject binnen of buiten de bebouwde kom.
|onderhoudsplichtige                       |onderhoudsplichtige                                  |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectOnderhoudsplichtige]; ; Default: None; Organisatie die verantwoordelijk is voor het onderhoud van het BeheerdObject.
|plaatsorientatie                          |plaatsorientatie                                     |TEXT(255,0)                            |IMBOR; Asfaltverharding; Enumeratie/Referentie; keuzelijst [Plaatsorientatie]; ; Default: None; Positie van het wegobject binnen het wegvak.
|theoretisch_eindjaar                      |theoretisch eindjaar                                 |SHORT(5,0)                             |IMBOR; Reëel object; Vrij invoerveld; ; ; Default: None; Jaar dat het beheerobject aan het theoretische einde van haar levensduur is.
|type                                      |blok type                                            |TEXT(255,0)                            |IMBOR; Blok; Enumeratie/Referentie; keuzelijst [BlokType]; ; Default: None; Typering van het beheerobject.

***

