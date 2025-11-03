<script src="https://www.kryogenix.org/code/browser/sorttable/sorttable.js"></script>

﻿## AREAALDATA.bordes_v

* [__Areaaldata model versie:__ 5](https://provincienh.github.io/Leveren_Geoinformatie/dev/)
* __Herkomst Definitie:__ IMBOR/NEN3610
* __Positionele nauwkeurigheid:__ 7,5 cm (NB, groter dan BGT)
* __Geometrie:__ Vlak
* __Definitie:__ Bordes valt onder GebouwInstallatie. Een verhard oppervlak, eventueel verhoogd en/of uitgevoerd met treden, grenzend aan een pand en primair bedoeld voor gebruik door voetgangers.
* __MappingBGT:__ gebouwInstallatie_v
* __Heeft Z-waarden:__ ENABLED
* __Heeft M-waarden:__ DISABLED

***

<table class="sortable">
<tr><th>__ATTRIBUUT__</th><th>__ALIAS__</th><th>__DATATYPE (length, precision)__</th><th>__DEFINITIE__ (Oorsprong; Superklasse; Attribuuttype; Enumeratie/Referentie; Verwijzende sleutel; Standaard waarde; Nullable; Definitie)</th></tr>
</table>
|objectid                                  |objectid                                    |OID(0,0)                               |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; NON_NULLABLE; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS.
|globalid                                  |globalid                                    |Globalid(38,0)                         |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; NON_NULLABLE; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken.
|ad_id                                     |ad_id                                       |TEXT(255,0)                            |PNH; AREAALDATA; GUID; ; ; Default: None; NON_NULLABLE; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer.
|created_user                              |created_user                                |TEXT(255,0)                            |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; NON_NULLABLE; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS.
|created_date                              |created_date                                |DATE(15,0)                             |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; NON_NULLABLE; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS.
|last_edited_user                          |last_edited_user                            |TEXT(255,0)                            |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; NON_NULLABLE; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS.
|last_edited_date                          |last_edited_date                            |DATE(15,0)                             |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; NON_NULLABLE; Datum van de laatste mutatie, gegenereerd door ArcGIS.
|objectbegintijd                           |objectbegintijd                             |DATE(9,0)                              |PNH; AREAALDATA; Vrij invoerveld; ; ; Default: None; NON_NULLABLE; Datum waarop het object bij de bronhouder is ontstaan.
|objecteindtijd                            |objecteindtijd                              |DATE(9,0)                              |PNH; AREAALDATA; Vrij invoerveld; ; ; Default: None; NULLABLE; Datum waarop het object bij de bronhouder niet meer geldig is.
|verwerkingsstatus                         |verwerkingsstatus                           |TEXT(255,0)                            |PNH; AREAALDATA; Enumeratie; keuzelijst [Verwerkingsstatus](../domeinen/Verwerkingsstatus.html); ; Default: None; NON_NULLABLE; Status van de gegevens.
|dataleverancier                           |dataleverancier                             |TEXT(255,0)                            |PNH; AREAALDATA; Vrij invoerveld; ; ; Default: None; NULLABLE; Leverancier van de data.
|opmerking                                 |opmerking                                   |TEXT(3000,0)                           |PNH; AREAALDATA; Vrij invoerveld; ; ; Default: None; NULLABLE; Algemene opmerking voor het object, zoals een omschrijving of toelichting.
|st_area(shape)                            |st_area                                     |DOUBLE(0,0)                            |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; NON_NULLABLE; Oppervlakte van het beheerobject in m2.
|st_perimeter(shape)                       |st_perimeter                                |DOUBLE(0,0)                            |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; NON_NULLABLE; Omtrek van het beheerobject in meters.
|beheerder                                 |beheerder                                   |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectBeheerder](../domeinen/BeheerdObjectBeheerder.html); ; Default: None; NULLABLE; Een publiekrechtelijke instantie of (rechts)persoon die toeziet op de instandhouding van o.a. een object, kunstwerk of waterstaatswerk. De typen beheerder zijn conform de indeling in bronhouders (BGT).
|beheergebied                              |beheergebied                                |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [GCR_NAAM](../domeinen/GCR_NAAM.html); Verwijzende sleutel naar [gebiedscontractregio_v]; Default: None; NULLABLE; De provincie heeft haar gebied in 8 gebieden opgesplitst. Amsterdam (gebied 8) is zelfstandig. Aanduiding van het beheergebied waarbinnen het beheerobject ligt. Bevat een verwijzende sleutel naar gebiedscontractregio_v (simpel). AD_ID foreign key. 
|bgtplustype                               |bgt plustype                                |TEXT(255,0)                            |IMBOR; Bordes; Enumeratie/Referentie; keuzelijst [typeGBI](../domeinen/typeGBI.html); ; Default: niet-bgt:bordes; NON_NULLABLE; Nadere type omschrijving in de BGT.
|bouwdeel_type                             |bouwdeel type                               |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [typeKWbouwdeel](../domeinen/typeKWbouwdeel.html); ; Default: None; NULLABLE; Nadere typering van het NEN-object
|eigenaar                                  |eigenaar                                    |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectEigenaar](../domeinen/BeheerdObjectEigenaar.html); ; Default: None; NULLABLE; (Rechts)persoon die het meest omvattend recht op een zaak heeft. De typen eigenaren zijn conform de indeling in bronhouders (BGT).
|gisib_id                                  |gisib id                                    |LONG(10,0)                             |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; NULLABLE; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer.
|hoofdroute                                |hoofdroute                                  |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [Hoofdroute](../domeinen/Hoofdroute.html); Verwijzende sleutel naar [weg_v]; Default: None; NULLABLE; Verwijzende sleutel naar weg_v (simpel); Naam van de hoofdroute waarbinnen het object ligt.
|locatieaanduiding                         |locatieaanduiding                           |TEXT(255,0)                            |PNH; Decompositie; Enumeratie/Referentie; keuzelijst [Locatieaanduiding](../domeinen/Locatieaanduiding.html); ; Default: None; NULLABLE; Om de locatie van verschillende bouwdelen aan te duiden waar volgnr en windrichting niet volstaan
|materiaaltype                             |materiaaltype                               |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [Materiaaltype](../domeinen/Materiaaltype.html); ; Default: None; NULLABLE; Materiaal waaruit het object is opgebouwd.
|onderdeel_van_element                     |onderdeel van element                       |TEXT(255,0)                            |PNH; Decompositie; Vrij invoerveld; ; ; Default: None; NULLABLE; Verwijzende sleutel naar betreffende kwelement; Featureclass is een bouwdeel van
|onderhoudsplichtige                       |onderhoudsplichtige                         |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerdObjectOnderhoudsplichtige](../domeinen/BeheerdObjectOnderhoudsplichtige.html); ; Default: None; NULLABLE; Organisatie die verantwoordelijk is voor het onderhoud van het beheerobject.
|relatieve_hoogteligging                   |bgt relatieve hoogteligging                 |SHORT(5,0)                             |IMBOR; Geo-object; Vrij invoerveld; ; ; Default: None; NON_NULLABLE; Aanduiding voor de relatieve hoogte van het beheerobject.

***
