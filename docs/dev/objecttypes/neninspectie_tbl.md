<script src="https://www.kryogenix.org/code/browser/sorttable/sorttable.js"></script>

﻿## AREAALDATA.neninspectie_tbl

* [__Areaaldata model versie:__ 5](https://provincienh.github.io/Leveren_Geoinformatie/dev/)
* __Herkomst Definitie:__ NEN 2767-4
* __Positionele nauwkeurigheid:__ n.v.t
* __Geometrie:__ n.v.t
* __Definitie:__ Condititescore conform NEN 2767-4
* __MappingBGT:__ n.v.t
* __Heeft Z-waarden:__ ENABLED
* __Heeft M-waarden:__ DISABLED

***

<table class="sortable">
<tr><th>__ATTRIBUUT__</th><th>__ALIAS__</th><th>__DATATYPE (length, precision)__</th><th>__DEFINITIE__ (Oorsprong; Superklasse; Attribuuttype; Enumeratie/Referentie; Verwijzende sleutel; Standaard waarde; Nullable; Definitie)</th></tr>
</table>
|objectid                                  |objectid                                    |OID(0,0)                               |PNH; Areaaldata; Waarde wordt automatisch bepaald; ; ; Default: None; NON_NULLABLE; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS.
|globalid                                  |globalid                                    |Globalid(38,0)                         |PNH; Areaaldata; Waarde wordt automatisch bepaald; ; ; Default: None; NON_NULLABLE; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken.
|ad_id                                     |ad_id                                       |TEXT(255,0)                            |PNH; Areaaldata; GUID; ; ; Default: None; NON_NULLABLE; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer.
|created_user                              |created_user                                |TEXT(255,0)                            |PNH; Areaaldata; Waarde wordt automatisch bepaald; ; ; Default: None; NON_NULLABLE; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS.
|created_date                              |created_date                                |DATE(15,0)                             |PNH; Areaaldata; Waarde wordt automatisch bepaald; ; ; Default: None; NON_NULLABLE; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS.
|last_edited_user                          |last_edited_user                            |TEXT(255,0)                            |PNH; Areaaldata; Waarde wordt automatisch bepaald; ; ; Default: None; NON_NULLABLE; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS.
|last_edited_date                          |last_edited_date                            |DATE(15,0)                             |PNH; Areaaldata; Waarde wordt automatisch bepaald; ; ; Default: None; NON_NULLABLE; Datum van de laatste mutatie, gegenereerd door ArcGIS.
|objectbegintijd                           |objectbegintijd                             |DATE(9,0)                              |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; NON_NULLABLE; Datum waarop het object bij de bronhouder is ontstaan.
|objecteindtijd                            |objecteindtijd                              |DATE(9,0)                              |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; NULLABLE; Datum waarop het object bij de bronhouder niet meer geldig is.
|verwerkingsstatus                         |verwerkingsstatus                           |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie; keuzelijst [Verwerkingsstatus](../domeinen/Verwerkingsstatus.html); ; Default: None; NON_NULLABLE; Status van de gegevens.
|dataleverancier                           |dataleverancier                             |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; NULLABLE; Leverancier van de data.
|opmerking                                 |opmerking                                   |TEXT(3000,0)                           |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; NULLABLE; Algemene opmerking voor het object, zoals een omschrijving of toelichting.
|bouwdeel_kunstwerk                        |bouwdeel kunstwerk                          |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; NULLABLE; Indicatieve foreign key van een object op bouwdeel niveau
|conditiescore                             |conditiescore                               |LONG(10,0)                             |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; NULLABLE; Conditiescore conform NEN 2767-4
|conditiescore_datum                       |conditiescore datum                         |DATE(9,0)                              |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; NULLABLE; Datum opname Conditiescore.
|conditiescore_opmerking                   |conditiescore opmerking                     |TEXT(3000,0)                           |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; NULLABLE; Opmerking bij conditiescore conform NEN 2767-4
|element_kunstwerk                         |element kunstwerk                           |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; NULLABLE; Indicatieve foreign key van een object op element niveau
|gisib_id                                  |gisib id                                    |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; NULLABLE; Wordt aangemaakt in GISIB
|kunstwerk                                 |kunstwerk                                   |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; NULLABLE; Indicatieve foreign key van een object op kunstwerk niveau

***
