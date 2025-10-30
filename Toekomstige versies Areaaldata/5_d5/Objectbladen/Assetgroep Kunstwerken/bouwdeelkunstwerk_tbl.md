## AREAALDATA.bouwdeelkunstwerk_tbl

* __Areaaldata model versie:__ 5
* __Herkomst Definitie:__ IMBOR/NEN3610
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ n.v.t.
* __Definitie:__ de individuele bouwdelen die bij een kunstwerkelement horen
* __MappingBGT:__ n.v.t.
* __Heeft Z-waarden:__ ENABLED
* __Heeft M-waarden:__ DISABLED

***

|__ATTRIBUUT__                             |__ALIAS__                                     |__DATATYPE (length, precision)__       |__DEFINITIE__ (Oorsprong; Superklasse; Attribuuttype; Enumeratie/Referentie; Verwijzende sleutel; Standaard waarde; Definitie)|
|------                                    |------                                        |------                                 |-----    |
|objectid                                  |objectid                                      |OID(0,0)                               |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS.
|globalid                                  |globalid                                      |Globalid(38,0)                         |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken.
|ad_id                                     |ad_id                                         |TEXT(255,0)                            |PNH; AREAALDATA; GUID; ; ; Default: None; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer.
|created_user                              |created_user                                  |TEXT(255,0)                            |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS.
|created_date                              |created_date                                  |DATE(15,0)                             |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS.
|last_edited_user                          |last_edited_user                              |TEXT(255,0)                            |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS.
|last_edited_date                          |last_edited_date                              |DATE(15,0)                             |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Datum van de laatste mutatie, gegenereerd door ArcGIS.
|objectbegintijd                           |objectbegintijd                               |DATE(9,0)                              |PNH; AREAALDATA; Vrij invoerveld; ; ; Default: None; Datum waarop het object bij de bronhouder is ontstaan.
|objecteindtijd                            |objecteindtijd                                |DATE(9,0)                              |PNH; AREAALDATA; Vrij invoerveld; ; ; Default: None; Datum waarop het object bij de bronhouder niet meer geldig is.
|verwerkingsstatus                         |verwerkingsstatus                             |TEXT(255,0)                            |PNH; AREAALDATA; Enumeratie; keuzelijst [Verwerkingsstatus]; ; Default: None; Status van de gegevens.
|dataleverancier                           |dataleverancier                               |TEXT(255,0)                            |PNH; AREAALDATA; Vrij invoerveld; ; ; Default: None; Leverancier van de data.
|opmerking                                 |opmerking                                     |TEXT(3000,0)                           |PNH; AREAALDATA; Vrij invoerveld; ; ; Default: None; Algemene opmerking voor het object, zoals een omschrijving of toelichting.
|aantal_bouwdelen                          |aantal bouwdelen                              |SHORT(5,0)                             |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Indien een of meer dezelfde bouwdelen als een enkel bouwdeel mogen worden opgenomen, kan in dit attribuut worden aangegeven hoeveel bouwdelen het betreft. Let op: Enkel door PNH in te vullen
|beheerder                                 |beheerder                                     |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectBeheerder]; ; Default: None; Een publiekrechtelijke instantie of (rechts)persoon die toeziet op de instandhouding van o.a. een object, kunstwerk of waterstaatswerk. De typen beheerder zijn conform de indeling in bronhouders (BGT).
|beheerder_gedetailleerd                   |beheerder gedetailleerd                       |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectBeheerderGedetailleerd]; ; Default: None; Nadere aanduiding van de beheerder van het beheerobject.
|cad_code                                  |cad code                                      |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [CAD_code]; ; Default: None; Afkorting van het bouwdeel zoals opgenomen in bijbehorende CAD-tekeningen
|eigenaar                                  |eigenaar                                      |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectEigenaar]; ; Default: None; (Rechts)persoon die het meest omvattend recht op een zaak heeft. De typen eigenaren zijn conform de indeling in bronhouders (BGT).
|eigenaar_gedetailleerd                    |eigenaar gedetailleerd                        |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectEigenaarGedetailleerd]; ; Default: None; Nadere aanduiding van de eigenaar van het beheerobject.
|gisib_id                                  |gisib id                                      |LONG(10,0)                             |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer.
|locatieaanduiding                         |locatieaanduiding                             |TEXT(255,0)                            |PNH; Kunstwerk; Enumeratie/Referentie; keuzelijst [Locatieaanduiding]; ; Default: None; Nadere specificatie van de locatie van het object aanvullend op de registratie van openbare ruimte en huisnummer.
|nen_materiaalsoort                        |nen materiaalsoort                            |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [Materiaaltype]; ; Default: None; NENMateriaalsoort
|onderdeel_van_element                     |onderdeel van element                         |TEXT(255,0)                            |PNH; Decompositie; Vrij invoerveld; ; Verwijzende sleutel naar [kwelement_tbl]; Default: None; Verwijzende sleutel naar kwelement_tbl; AD_ID foreign key.
|onderhoudsplichtige                       |onderhoudsplichtige                           |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectOnderhoudsplichtige]; ; Default: None; Organisatie die verantwoordelijk is voor het onderhoud van het beheerobject.
|type_bouwdeel                             |type bouwdeel                                 |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [typeKWbouwdeel]; ; Default: None; NEN kunstwerk bouwdelen.
|volgnummer                                |volgnummer                                    |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [VOLGNUMMER]; ; Default: None; Indien een reeks van dezelfde bouwdelen voorkomen dan dienen deze worden met een volgnummer te worden geduid. De nummering dient logischerwijs te worden gestart met noord georiënteerde item als eerste te benoemen en vervolgens de daaropvolgende items door te nummeren met de klok mee
|windrichting                              |windrichting                                  |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [WINDRICHTING]; ; Default: None; Om de locatie van verschillende bouwdelen aan te duiden

***

