﻿## AREAALDATA.beheervak_v

* __Areaaldata model versie:__ 5.0
* __Herkomst Definitie:__ IMBOR/NEN3610
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Vlak
* __Definitie:__ Functioneel; Een functioneel gebied voor het beheren en inspecteren van de objecten binnen de begrenzing. Het beheervak kan ook uit meerdere vlakken bestaan (multivlak).
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
|beheer_en_onderhoud_status                |beheer en onderhoud status                        |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Nadere toelichting op het beheer en onderhoud van het gebied indien bekend
|beheerder                                 |beheerder                                         |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectBeheerder]; ; Default: None; Een publiekrechtelijke instantie of (rechts)persoon die toeziet op de instandhouding van o.a. een object, kunstwerk of waterstaatswerk. De typen beheerder zijn conform de indeling in bronhouders (BGT).
|beheergebied                              |gebiedscontractregio                              |TEXT(255,0)                            |IMBOR; Beheerd object; Vrij invoerveld; ; Verwijzende sleutel naar [gebiedscontractregio_v]; Default: None; Verwijzende sleutel naar gebiedscontractregio_v. Functionele laag. De provincie heeft haar gebied in 8 gebieden opgesplitst. Amsterdam (gebied 8) is zelfstandig.
|conversie_id                              |conversie id                                      |TEXT(255,0)                            |IMBOR; RuimtelijkGebied; Vrij invoerveld; ; ; Default: None; Uniek kenmerk van een beheerobject uit een oude beheerindeling.
|eigenaar                                  |eigenaar                                          |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectEigenaar]; ; Default: None; (Rechts)persoon die het meest omvattend recht op een zaak heeft. De typen eigenaren zijn conform de indeling in bronhouders (BGT).
|gedeeld_beheer                            |gedeeld beheer                                    |TEXT(3,0)                              |IMBOR; Beheerd object; Ja/Nee; ; ; Default: None; Aanduiding voor het registreren van gedeeld beheer van het object.
|gisib_id                                  |gisib_id                                          |TEXT(255,0)                            |PNH; Areaaldata; Waarde wordt automatisch bepaald; ; ; Default: None; wordt aangemaakt in GISIB
|objectnaam                                |objectnaam                                        |TEXT(255,0)                            |IMBOR; RuimtelijkGebied; Vrij invoerveld; ; ; Default: None; Naam van het beheerobject.
|objectnummer                              |objectnummer                                      |TEXT(255,0)                            |IMBOR; RuimtelijkGebied; Vrij invoerveld; ; ; Default: None; Het vervolgnummer van het object
|onderhoudsplichtige                       |onderhoudsplichtige                               |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectOnderhouder]; ; Default: None; Organisatie die verantwoordelijk is voor het onderhoud van het beheerobject.
|plus_type                                 |plustype_beheervak                                |TEXT(255,0)                            |IMBOR; Beheervak; Vrij invoerveld; ; ; Default: Beheergrens; Dit attribuut is door overerving vanuit de IMGeo aan IMBOR toegevoegd.

***
