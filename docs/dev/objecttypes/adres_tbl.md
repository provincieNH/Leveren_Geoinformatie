## AREAALDATA.adres_tbl

* __Areaaldata model versie:__ 5
* __Herkomst Definitie:__ IMBOR/NEN3610
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ n.v.t.
* __Definitie:__ Een object met adresgegevens, om naar te verwijzen vanuit kunstwerken, vri_; en ovl_kasten
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
|verwerkingsstatus                         |verwerkingsstatus                             |TEXT(255,0)                            |PNH; AREAALDATA; Enumeratie; keuzelijst [Verwerkingsstatus](../domeinen/Verwerkingsstatus.html); ; Default: None; Status van de gegevens.
|dataleverancier                           |dataleverancier                               |TEXT(255,0)                            |PNH; AREAALDATA; Vrij invoerveld; ; ; Default: None; Leverancier van de data.
|opmerking                                 |opmerking                                     |TEXT(3000,0)                           |PNH; AREAALDATA; Vrij invoerveld; ; ; Default: None; Algemene opmerking voor het object, zoals een omschrijving of toelichting.
|gisib_id                                  |gisib id                                      |LONG(10,0)                             |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer.
|huisnummer                                |huisnummer                                    |LONG(10,0)                             |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Huisnummer
|locatieomschrijving                       |locatieomschrijving                           |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Beschrijving van de locatie indien geen specifiek adres
|plaats                                    |plaats                                        |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Plaatsnaam
|postcode                                  |postcode                                      |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; NL postcode
|straat                                    |straat                                        |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Straatnaam
|toevoeging                                |toevoeging                                    |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Toevoeging; i.a. Rood of Zwaart of A, B, C….

***

