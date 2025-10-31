## AREAALDATA.crowmeting_tbl

* __Areaaldata model versie:__ 5.0
* __Herkomst Definitie:__ IMBOR/NEN3610
* __Positionele nauwkeurigheid:__ N.v.t.
* __Geometrie:__ n.v.t.
* __Definitie:__ Een inspectie geeft een momentopname weer hoe een PNH wegvakonderdeel er op dat moment bij ligt. De CROW norm wordt gebruikt. Het object Meting is bedoeld om de metingen van een bepaald wegvakonderdeel vast te leggen. Metingen zijn: langsonvlakheid, stroefheid, zetting, spoorvorming, comfortindex
* __MappingBGT:__ N.v.t.
* __Heeft Z-waarden:__ ENABLED
* __Heeft M-waarden:__ DISABLED

***

|__ATTRIBUUT__                             |__ALIAS__                                            |__DATATYPE (length, precision)__       |__DEFINITIE__ (Oorsprong; Superklasse; Attribuuttype; Enumeratie/Referentie; Verwijzende sleutel; Standaard waarde; Nullable; Definitie)|
|------                                    |------                                               |------                                 |-----    |
|objectid                                  |objectid                                             |OID(0,0)                               |PNH; Areaaldata; Waarde wordt automatisch bepaald; ; ; Default: None; NON_NULLABLE; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS.
|globalid                                  |globalid                                             |Globalid(38,0)                         |PNH; Areaaldata; Waarde wordt automatisch bepaald; ; ; Default: None; NON_NULLABLE; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken.
|ad_id                                     |ad_id                                                |TEXT(255,0)                            |PNH; Areaaldata; GUID; ; ; Default: None; NON_NULLABLE; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer.
|created_user                              |created_user                                         |TEXT(255,0)                            |PNH; Areaaldata; Waarde wordt automatisch bepaald; ; ; Default: None; NON_NULLABLE; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS.
|created_date                              |created_date                                         |DATE(15,0)                             |PNH; Areaaldata; Waarde wordt automatisch bepaald; ; ; Default: None; NON_NULLABLE; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS.
|last_edited_user                          |last_edited_user                                     |TEXT(255,0)                            |PNH; Areaaldata; Waarde wordt automatisch bepaald; ; ; Default: None; NON_NULLABLE; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS.
|last_edited_date                          |last_edited_date                                     |DATE(15,0)                             |PNH; Areaaldata; Waarde wordt automatisch bepaald; ; ; Default: None; NON_NULLABLE; Datum van de laatste mutatie, gegenereerd door ArcGIS.
|objectbegintijd                           |objectbegintijd                                      |DATE(9,0)                              |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; NON_NULLABLE; Datum waarop het object bij de bronhouder is ontstaan.
|objecteindtijd                            |objecteindtijd                                       |DATE(9,0)                              |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; NULLABLE; Datum waarop het object bij de bronhouder niet meer geldig is.
|verwerkingsstatus                         |verwerkingsstatus                                    |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie; keuzelijst [Verwerkingsstatus]; ; Default: None; NON_NULLABLE; Status van de gegevens.
|dataleverancier                           |dataleverancier                                      |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; NULLABLE; Leverancier van de data.
|opmerking                                 |opmerking                                            |TEXT(3000,0)                           |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; NULLABLE; Algemene opmerking voor het object, zoals een omschrijving of toelichting.
|asfaltverharding                          |asfaltverharding                                     |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; Verwijzende sleutel naar [asfaltverharding_v]; Default: None; NULLABLE; Verwijzende sleutel naar asfaltverharding_v (simpel)
|betonverharding                           |betonverharding                                      |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; Verwijzende sleutel naar [betonverharding_v]; Default: None; NULLABLE; Verwijzende sleutel naar betonverharding_v (simpel)
|elementenverharding                       |elementenverharding                                  |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; Verwijzende sleutel naar [elementenverharding_v]; Default: None; NULLABLE; Verwijzende sleutel naar elementenverharding_v (simpel)
|gisib_id                                  |gisib id                                             |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; NULLABLE; wordt aangemaakt in GISIB
|metingdatum                               |metingdatum                                          |DATE(9,0)                              |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; NULLABLE; Datum van de Meting
|metingtype                                |metingtype                                           |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [CROWMetingType]; ; Default: None; NULLABLE; Soort Meting
|metingwaarde                              |metingwaarde                                         |FLOAT(6,2)                             |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; NULLABLE; Waarde van de Meting

***

