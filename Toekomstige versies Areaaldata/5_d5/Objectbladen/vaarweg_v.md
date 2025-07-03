## AREAALDATA.vaarweg_v

* __Areaaldata model versie:__ 5.0
* __Herkomst Definitie:__ IMBOR/NEN3610
* __Positionele nauwkeurigheid:__ 7,5 cm (NB, groter dan BGT)
* __Geometrie:__ Vlak
* __Definitie:__ Vaarweg is een abstract functioneel gebied waarvan de afmetingen zijn bepaald aan de hand van het geografisch bereik van de geldende beperking en de geldende functie zoals die is aangegeven door de beheerder of vanuit het beheerplan. Het heeft geen vaste afmetingen maar past altijd binnen het vaarwegtraject.
* __MappingBGT:__ n.v.t.
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
|begin_linker_oever                        |begin linker oever (km)                              |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Begin Linker Oever
|beheerder                                 |beheerder                                            |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectBeheerder]; ; Default: None; Een publiekrechtelijke instantie of (rechts)persoon die toeziet op de instandhouding van o.a. een object, kunstwerk of waterstaatswerk. De typen beheerder zijn conform de indeling in bronhouders (BGT).
|beheergebied                              |beheergebied                                         |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [GCR_NAAM]; Verwijzende sleutel naar [gebiedscontractregio_v]; Default: None; Verwijzende sleutel naar gebiedscontractregio_v; Aanduiding van het beheergebied waarbinnen het beheerobject ligt. Indeling in beheergebieden is organisatiespecifiek.
|beign_rechter_oever                       |begin rechter oever (km)                             |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Begin Rechter Oever
|besluitnummer                             |besluitnummer                                        |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Besluitnummer waarde
|eigenaar                                  |eigenaar                                             |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectEigenaar]; ; Default: None; (Rechts)persoon die het meest omvattend recht op een zaak heeft. De typen eigenaren zijn conform de indeling in bronhouders (BGT).
|eind_linker_oever                         |eind linker oever (km)                               |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Eind Linker Oever
|eind_rechter_oever                        |eind rechter oever (km)                              |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Eind Rechter Oever
|geldende_beperking                        |geldende beperking                                   |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Waar een vaarwegdeeltraject niet voldoet aan een streefbeeld worden beperking opgelegd qua gebruik
|gewenste_bagger_kwaliteit                 |gewenste bagger kwaliteit                            |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Gewenste baggerkwaliteit
|hoofdroute                                |hoofdroute                                           |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [Hoofdroute]; Verwijzende sleutel naar [weg_v]; Default: None; Verwijzende sleutel naar weg_v; AD_ID foreign key
|lengte_linker_oever                       |lengte linker oever (m)                              |FLOAT(6,2)                             |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Lengte linkeroever (m)
|lengte_rechter_oever                      |lengte rechter oever (m)                             |FLOAT(6,2)                             |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Lengte rechteroever (m)
|objectnaam                                |objectnaam                                           |TEXT(255,0)                            |IMBOR; ReëelObject; Vrij invoerveld; ; ; Default: None; Naam van het beheerobject; Deeltraject-naam, bijvoorbeeld k20n-d
|objectnummer                              |deeltrajectnummer                                    |SHORT(5,0)                             |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Deeltraject nummer
|omtrek                                    |omtrek (m)                                           |DOUBLE(10,3)                           |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Omtrek
|onderhoudsplichtige                       |onderhoudsplichtige                                  |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectOnderhoudsplichtige]; ; Default: None; Organisatie die verantwoordelijk is voor het onderhoud van het beheerobject.
|oppervlakte                               |oppervlakte (m2)                                     |DOUBLE(10,3)                           |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Oppervlakte
|waterschapnaam                            |waterschapnaam                                       |TEXT(255,0)                            |IMBOR; Gebiedsindeling; Enumeratie/Referentie; keuzelijst [Waterschap]; ; Default: None; Aanduiding van het beheergebied waarbinnen het beheerobject ligt. Indeling in beheergebieden is organisatiespecifiek.

***

