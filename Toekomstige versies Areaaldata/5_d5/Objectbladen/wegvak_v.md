## AREAALDATA.wegvak_v

* __Areaaldata model versie:__ 5
* __Herkomst Definitie:__ IMBOR/NEN3610
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Vlak
* __Definitie:__ Functioneel; Administratief afgebakend gedeelte van een weg waarbinnen de inspectiemetingen uitgevoerd worden. Een wegvak is doorgaands 100 meter en loopt in de meeste gevallen gelijk aan de wegindexering (hectometerpalen). In de breedte dient een wegvak alle wegdelen en ondersteunende wegdelen te omvatten.
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
|beheerder                                 |beheerder                                            |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectBeheerder]; ; Default: None; Een publiekrechtelijke instantie of (rechts)persoon die toeziet op de instandhouding van o.a. een object, kunstwerk of waterstaatswerk. De typen beheerder zijn conform de indeling in bronhouders (BGT).
|beheerder_gedetailleerd                   |beheerder gedetailleerd                              |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectBeheerderGedetailleerd]; ; Default: None; Nadere aanduiding van de beheerder van het beheerobject.
|beheergebied                              |beheergebied                                         |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [GCR_NAAM]; Verwijzende sleutel naar [gebiedscontractregio_v]; Default: None; Verwijzende sleutel naar gebiedscontractregio_v; De provincie heeft haar gebied in 8 gebieden opgesplitst. Amsterdam (gebied 8) is zelfstandig. Er zijn geen beheerobjecten in Areaaldata.
|eigenaar                                  |eigenaar                                             |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectEigenaar]; ; Default: None; (Rechts)persoon die het meest omvattend recht op een zaak heeft. De typen eigenaren zijn conform de indeling in bronhouders (BGT).
|eigenaar_gedetailleerd                    |eigenaar gedetailleerd                               |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectEigenaarGedetailleerd]; ; Default: None; Nadere aanduiding van de eigenaar van het beheerobject.
|gisib_id                                  |gisib_id                                             |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; wordt aangemaakt in GISIB
|grondsoortnaam                            |grondsoortnaam                                       |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [GrondsoortType]; ; Default: None; type grond onder de wegvak
|hoofdroute                                |hoofdroute                                           |TEXT(255,0)                            |IMBOR; Areaaldata; Enumeratie/Referentie; keuzelijst [Hoofdroute]; Verwijzende sleutel naar [weg_v]; Default: None; Verwijzende sleutel naar weg_v; AD_ID foreign key
|kilometrering_begin                       |kilometrering begin                                  |FLOAT(6,2)                             |IMBOR; Wegvak; Vrij invoerveld; ; ; Default: None; Kilometrering alleen bij kunstwerken die langs een weg liggen.
|kilometrering_eind                        |kilometrering eind                                   |FLOAT(6,2)                             |IMBOR; Wegvak; Vrij invoerveld; ; ; Default: None; Kilometrering alleen bij kunstwerken die langs een weg liggen.
|lengte                                    |lengte (m)                                           |LONG(10,0)                             |IMBOR; Wegvak; Vrij invoerveld; ; ; Default: None; Lengte van het beheerobject.
|onderhoudsplichtige                       |onderhoudsplichtige                                  |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectOnderhoudsplichtige]; ; Default: None; Organisatie die verantwoordelijk is voor het onderhoud van het beheerobject.
|verkeersintensiteit                       |verkeersintensiteit                                  |FLOAT(6,2)                             |IMBOR; Wegvak; Vrij invoerveld; ; ; Default: None; pae; Het aantal verkeerseenheden dat een bepaalde dwarsdoorsnede van de weg passeert gedurende een bepaalde tijdsduur.
|wegnummer                                 |wegnummer                                            |TEXT(255,0)                            |IMBOR; Wegvak; Enumeratie/Referentie; keuzelijst [Wegnummer]; ; Default: None; traject; N-nummer
|wegvaknummer                              |wegvaknummer                                         |SHORT(5,0)                             |IMBOR; Wegvak; Vrij invoerveld; ; ; Default: None; de nummer van de wegvak

***

