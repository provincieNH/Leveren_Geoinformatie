## AREAALDATA.constructielaag_tbl

* __Areaaldata model versie:__ 5.0
* __Herkomst Definitie:__ IMBOR/NEN3610
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ n.v.t.
* __Definitie:__ Administratief afgebakend de constructie van een wegdeel. Het vastleggen van de laagopbouw van een verhardingsobject via constructielagen. Begin bij de deklaag; laag 1 en ga zo door tot de funderingslaag.
* __MappingBGT:__ x
* __Heeft Z-waarden:__ ENABLED
* __Heeft M-waarden:__ DISABLED

***

|__ATTRIBUUT__                       |__ALIAS__                           |__DATATYPE (length, precision)__       |__DEFINITIE__ (Oorsprong; Superklasse; Attribuuttype; Enumeratie/Referentie; Definitie)|
|------                              |------                              |------                                 |-----    |
|objectid                            |objectid                            |OID(0,0)                               |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; Default: None; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS.
|globalid                            |globalid                            |Globalid(38,0)                         |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; Default: None; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken.
|ad_id                               |ad_id                               |TEXT(255,0)                            |PNH; AREAALDATA; GUID; ; Default: None; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer.
|created_user                        |created_user                        |TEXT(255,0)                            |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; Default: None; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS.
|created_date                        |created_date                        |DATE(15,0)                             |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; Default: None; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS.
|last_edited_user                    |last_edited_user                    |TEXT(255,0)                            |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; Default: None; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS.
|last_edited_date                    |last_edited_date                    |DATE(15,0)                             |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; Default: None; Datum van de laatste mutatie, gegenereerd door ArcGIS.
|objectbegintijd                     |objectbegintijd                     |DATE(9,0)                              |PNH; AREAALDATA; Vrij invoerveld; ; Default: None; Datum waarop het object bij de bronhouder is ontstaan.
|objecteindtijd                      |objecteindtijd                      |DATE(9,0)                              |PNH; AREAALDATA; Vrij invoerveld; ; Default: None; Datum waarop het object bij de bronhouder niet meer geldig is.
|verwerkingsstatus                   |verwerkingsstatus                   |TEXT(255,0)                            |PNH; AREAALDATA; Enumeratie; keuzelijst [verwerkingsstatus]; Default: None; Status van de gegevens.
|dataleverancier                     |dataleverancier                     |TEXT(255,0)                            |PNH; AREAALDATA; Vrij invoerveld; ; Default: None; Leverancier van de data.
|opmerking                           |opmerking                           |TEXT(3000,0)                           |PNH; AREAALDATA; Vrij invoerveld; ; Default: None; Algemene opmerking voor het object, zoals een omschrijving of toelichting.
|breedte                             |breedte                             |DOUBLE(10,3)                           |IMBOR; Constructielaag; Vrij invoerveld; ; Default: None; aanduiding laag breedte
|constructielaag_dikte               |constructielaag dikte               |DOUBLE(10,3)                           |IMBOR; Constructielaag; Vrij invoerveld; ; Default: None; aanduiding laag dikte van de constructielaag *meerdere regels mogelijke)
|constructielaag_nummer              |constructielaag nummer              |FLOAT(6,2)                             |IMBOR; Constructielaag; Vrij invoerveld; ; Default: None; aanduiding laag volgorde van de constructielaag *meerdere regels mogelijke)
|constructielaagsoort                |constructielaagsoort                |TEXT(255,0)                            |IMBOR; Constructielaag; Enueratie/referentie; keuzelijst [Constructielaagsoort]; Default: None; Aanduiding voor de constructielaag
|constructielaagsoort_type           |constructielaagsoort type           |TEXT(255,0)                            |IMBOR; Constructielaag; Enueratie/referentie; keuzelijst [ConstructielaagsoortType]; Default: None; aanduiding type materiaal voor de constructielaag
|gisib_id                            |gisib_id                            |TEXT(255,0)                            |PNH; Areaaldata; Waarde wordt automatisch bepaald; ; Default: None; wordt aangemaakt in GISIB
|hoogte                              |hoogte                              |DOUBLE(10,3)                           |IMBOR; Constructielaag; Vrij invoerveld; ; Default: None; aanduiding laag hoogte
|lengte                              |lengte                              |DOUBLE(10,3)                           |IMBOR; Constructielaag; Vrij invoerveld; ; Default: None; aanduiding laag lengte (als die afwijkt van de deklaag)
|verhardingdtype                     |verhardingstype                     |TEXT(255,0)                            |PNH; Verharding; Enueratie/referentie; keuzelijst [TypeVerhardingAD4]; Default: None; Aanduiding type verharding per constructielaag
|wegdeel                             |wegdeel                             |TEXT(255,0)                            |PNH; Wegdeel; Vrij invoerveld; ; Default: None; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format ‘AD.[GUID]’. Dit moet worden ingevuld door de aannemer.

***

