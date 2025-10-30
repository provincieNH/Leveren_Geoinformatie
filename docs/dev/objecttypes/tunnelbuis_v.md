## AREAALDATA.tunnelbuis_v

* [__Areaaldata model versie:__ 5](https://provincienh.github.io/Leveren_Geoinformatie/dev/)
* __Herkomst Definitie:__ IMBOR/NEN3610
* __Positionele nauwkeurigheid:__ 7,5 cm (NB, groter dan BGT)
* __Geometrie:__ Vlak
* __Definitie:__ Opening in een tunnel, die ruimte biedt voor een transportlink.
* __MappingBGT:__ tunneldeel_v
* __Heeft Z-waarden:__ ENABLED
* __Heeft M-waarden:__ DISABLED

***

|__ATTRIBUUT__|__ALIAS__|__DATATYPE__|__Oorsprong__|__Superklasse__|__Attribuuttype__|__Enumeratie/Referentie__|__Verwijzende sleutel__|__Standaard waarde__|__Definitie__|
|------|------|------|------|------|------|------|------|------|------|
|------                                    |------                                        |------                                 |-----    |
|objectid|objectid|OID(0,0)|PNH|AREAALDATA|Waarde wordt automatisch bepaald|||Default: None|Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS.|
|globalid|globalid|Globalid(38,0)|PNH|AREAALDATA|Waarde wordt automatisch bepaald|||Default: None|Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken.|
|ad_id|ad_id|TEXT(255,0)|PNH|AREAALDATA|GUID|||Default: None|Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer.|
|created_user|created_user|TEXT(255,0)|PNH|AREAALDATA|Waarde wordt automatisch bepaald|||Default: None|Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS.|
|created_date|created_date|DATE(15,0)|PNH|AREAALDATA|Waarde wordt automatisch bepaald|||Default: None|Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS.|
|last_edited_user|last_edited_user|TEXT(255,0)|PNH|AREAALDATA|Waarde wordt automatisch bepaald|||Default: None|Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS.|
|last_edited_date|last_edited_date|DATE(15,0)|PNH|AREAALDATA|Waarde wordt automatisch bepaald|||Default: None|Datum van de laatste mutatie, gegenereerd door ArcGIS.|
|objectbegintijd|objectbegintijd|DATE(9,0)|PNH|AREAALDATA|Vrij invoerveld|||Default: None|Datum waarop het object bij de bronhouder is ontstaan.|
|objecteindtijd|objecteindtijd|DATE(9,0)|PNH|AREAALDATA|Vrij invoerveld|||Default: None|Datum waarop het object bij de bronhouder niet meer geldig is.|
|verwerkingsstatus|verwerkingsstatus|TEXT(255,0)|PNH|AREAALDATA|Enumeratie|keuzelijst [Verwerkingsstatus](../domeinen/Verwerkingsstatus.html)||Default: None|Status van de gegevens.|
|dataleverancier|dataleverancier|TEXT(255,0)|PNH|AREAALDATA|Vrij invoerveld|||Default: None|Leverancier van de data.|
|opmerking|opmerking|TEXT(3000,0)|PNH|AREAALDATA|Vrij invoerveld|||Default: None|Algemene opmerking voor het object, zoals een omschrijving of toelichting.|
|st_area(shape)|st_area|DOUBLE(0,0)|PNH|AREAALDATA|Waarde wordt automatisch bepaald|||Default: None|Oppervlakte van het beheerobject in m2.|
|st_perimeter(shape)|st_perimeter|DOUBLE(0,0)|PNH|AREAALDATA|Waarde wordt automatisch bepaald|||Default: None|Omtrek van het beheerobject in meters.|
|aantal_elementen|aantal elementen|TEXT(255,0)|PNH|Areaaldata|Vrij invoerveld|||Default: None|Indien een of meer dezelfde elementen als een enkel element mogen worden opgenomen, kan in dit attribuut worden aangegeven hoeveel elementen het betreft. Let op: Enkel door PNH in te vullen|
|beheerder|beheerder|TEXT(255,0)|IMBOR|Beheerd object|Enumeratie/Referentie|keuzelijst [BeheerdObjectBeheerder](../domeinen/BeheerdObjectBeheerder.html)||Default: None|Een publiekrechtelijke instantie of (rechts)persoon die toeziet op de instandhouding van o.a. een object, kunstwerk of waterstaatswerk. De typen beheerder zijn conform de indeling in bronhouders (BGT).|
|beheerder_gedetailleerd|beheerder gedetailleerd|TEXT(255,0)|IMBOR|Beheerd object|Enumeratie/Referentie|keuzelijst [BeheerdObjectBeheerderGedetailleerd](../domeinen/BeheerdObjectBeheerderGedetailleerd.html)||Default: None|Nadere aanduiding van de beheerder van het beheerobject.|
|beheergebied|beheergebied|TEXT(255,0)|IMBOR|Beheerd object|Enumeratie/Referentie|keuzelijst [GCR_NAAM](../domeinen/GCR_NAAM.html)|Verwijzende sleutel naar [gebiedscontractregio_v]|Default: None|De provincie heeft haar gebied in 8 gebieden opgesplitst. Amsterdam (gebied 8) is zelfstandig. Aanduiding van het beheergebied waarbinnen het beheerobject ligt. Bevat een verwijzende sleutel naar gebiedscontractregio_v (simpel). AD_ID foreign key.|
|bericht_id|bgt bericht id|TEXT(255,0)|PNH|Areaaldata|Enumeratie/Referentie|||Default: None|Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer.|
|bgt_objecttype|bgt classificatie|TEXT(255,0)|IMBOR|Geo-object|Enumeratie/Referentie|keuzelijst [BGTclassificatie](../domeinen/BGTclassificatie.html)||Default: tunneldeel_v|Specificatie van het BGT/IMGeo-object.|
|bgt_opmerking|bgt opmerking|TEXT(255,0)|IMBOR|Geo-object|Vrij invoerveld|||Default: None|Opmerking die bij het object ten behoeve van de uitwisseling geplaatst kan worden speciaal voor de BGT-applicatie (Geovoorziening).|
|bouwjaar|bouwjaar|SHORT(5,0)|IMBOR|Constructie|Vrij invoerveld|||Default: None|Bouwjaar van het object. Deze kan afwijken van het jaar van aanleg, bijvoorbeeld wanneer een beheerobject hergebruikt wordt.|
|breedte|breedte (m)|DOUBLE(10,3)|IMBOR|Kunstwerk|Vrij invoerveld|||Default: None|Breedte van het beheerobject.|
|bronhouder|bgt bronhouder|TEXT(255,0)|IMBOR|Geo-object|Enumeratie/Referentie|keuzelijst [Bronhouder](../domeinen/Bronhouder.html)||Default: None|De bronhoudercode van het object.|
|conformen|conformen|TEXT(3,0)|PNH|Areaaldata|Enumeratie/Referentie|keuzelijst [JaNeeOnbekend](../domeinen/JaNeeOnbekend.html)||Default: None|Is Element conform NEN|
|doorrijbreedte|doorrijbreedte|DOUBLE(10,3)|IMBOR|Tunnel|Vrij invoerveld|||Default: None|Doorrijbreedte van een object of van een opening van het object in meters.|
|doorrijhoogte|doorrijhoogte|DOUBLE(10,3)|IMBOR|Tunnel|Vrij invoerveld|||Default: None|Doorrijhoogte onder een object of onder een opening van het object in meters.|
|eigenaar|eigenaar|TEXT(255,0)|IMBOR|Beheerd object|Enumeratie/Referentie|keuzelijst [BeheerdObjectEigenaar](../domeinen/BeheerdObjectEigenaar.html)||Default: None|(Rechts)persoon die het meest omvattend recht op een zaak heeft. De typen eigenaren zijn conform de indeling in bronhouders (BGT).|
|eigenaar_gedetailleerd|eigenaar gedetailleerd|TEXT(255,0)|IMBOR|Beheerd object|Enumeratie/Referentie|keuzelijst [BeheerdObjectEigenaarGedetailleerd](../domeinen/BeheerdObjectEigenaarGedetailleerd.html)||Default: None|Nadere aanduiding van de eigenaar van het beheerobject.|
|eind_registratie|bgt eindregistratie|DATE(15,0)|IMBOR|Geo-object|Vrij invoerveld|||Default: None|Eind van de periode waarop deze instantie van het object geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig.|
|gisib_id|gisib id|LONG(10,0)|PNH|Areaaldata|Vrij invoerveld|||Default: None|Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer.|
|hoofdroute|hoofdroute|TEXT(255,0)|PNH|Kunstwerk|Enumeratie/Referentie|keuzelijst [Hoofdroute](../domeinen/Hoofdroute.html)|Verwijzende sleutel naar [weg_v]|Default: None|Verwijzende sleutel naar weg_v (simpel)|
|hoogte|hoogte (m)|DOUBLE(10,3)|IMBOR|Kunstwerk|Vrij invoerveld|||Default: None|Hoogte van het beheerobject in meters.|
|identificatie|bgt identificatie|TEXT(255,0)|IMBOR|Object|GUID|||Default: None|Uniek nummer van het object (GUID), een numerieke identificatie. Conform NEN3610 zijn identificatiecodes persistent: ze wijzigen niet gedurende de levensduur van een object. SVB identificatie|
|in_onderzoek|bgt in onderzoek|TEXT(3,0)|IMBOR|Geo-object|Enumeratie/Referentie|keuzelijst [JaNeeOnbekend](../domeinen/JaNeeOnbekend.html)||Default: None|Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object.|
|kilometrering_begin|kilometrering begin|FLOAT(6,2)|IMBOR|Tunnelwand|Vrij invoerveld|||Default: None|Kilometrering alleen bij kunstwerken die langs een weg liggen-begin|
|kilometrering_eind|kilometrering eind|FLOAT(6,2)|IMBOR|Tunnelwand|Vrij invoerveld|||Default: None|Kilometrering alleen bij kunstwerken die langs een weg liggen-eind|
|kritisch|kritisch|TEXT(3,0)|PNH|Areaaldata|Enumeratie/Referentie|keuzelijst [JaNeeOnbekend](../domeinen/JaNeeOnbekend.html)||Default: None|Kritisch|
|lengte|lengte (m)|DOUBLE(10,3)|IMBOR|Kunstwerk|Vrij invoerveld|||Default: None|Lengte van het beheerobject in meters.|
|ligging|ligging|TEXT(255,0)|IMBOR|Gebiedsindeling|Enumeratie/Referentie|keuzelijst [GebiedsindelingLigging](../domeinen/GebiedsindelingLigging.html)||Default: None|Aanduiding van de ligging van het beheerobject binnen of buiten de bebouwde kom.|
|lv_publicatiedatum|bgt lv publicatiedatum|DATE(15,0)|IMBOR|Geo-object|Waarde wordt automatisch bepaald|||Default: None|Datum en tijdstip waarop de Landelijke voorziening het object heeft opgenomen. Dit mag niet worden ingevuld door de aannemer.|
|onderdeel_van_kunstwerk|onderdeel van kunstwerk|TEXT(255,0)|PNH|Decompositie|Vrij invoerveld|||Default: None|Verwijzende sleutel naar kwelement_tbl (simpel)|
|onderhoudsplichtige|onderhoudsplichtige|TEXT(255,0)|IMBOR|Beheerd object|Enumeratie/Referentie|keuzelijst [BeheerdObjectOnderhoudsplichtige](../domeinen/BeheerdObjectOnderhoudsplichtige.html)||Default: None|Organisatie die verantwoordelijk is voor het onderhoud van het beheerobject.|
|oppervlakte|oppervlakte (m2)|DOUBLE(12,3)|IMBOR|Kunstwerk|Vrij invoerveld|||Default: None|Oppervlakte van het beheerobject in m2, overgenomen van BGT/IMGeo.|
|oppervlaktebehandeling|oppervlaktebehandeling|TEXT(255,0)|IMBOR|Kunstwerk|Enumeratie/Referentie|keuzelijst [KunstwerkOppervlaktebehandeling](../domeinen/KunstwerkOppervlaktebehandeling.html)||Default: None|Aanduiding voor de wijze waarop het oppervlak van het object behandeld is tegen externe invloeden.|
|relatieve_hoogteligging|bgt relatieve hoogteligging|SHORT(5,0)|IMBOR|Geo-object|Vrij invoerveld|||Default: -1|Aanduiding voor de relatieve hoogte van het beheerobject.|
|status|bgt status|TEXT(255,0)|IMBOR|Geo-object|Enumeratie/Referentie|keuzelijst [BGTstatus](../domeinen/BGTstatus.html)||Default: None|Status van het Beheerobject in het inwinningsproces van de geometrie. Wordt gebruikt voor schets- en definitieve geometrie.|
|theoretisch_eindjaar|theoretisch eindjaar|SHORT(5,0)|IMBOR|Reëel object|Vrij invoerveld|||Default: None|Jaar dat het beheerobject aan het theoretische einde van haar levensduur is.|
|tijdstip_registratie|bgt tijdstip registratie|DATE(15,0)|IMBOR|Geo-object|Waarde wordt automatisch bepaald|||Default: None|Tijdstip waarop deze versie van het informatieobject is opgenomen in de registratie.|
|tunnelgang_type|tunnelgang type|TEXT(255,0)|IMBOR|Tunnel|Enumeratie/Referentie|keuzelijst [TunnelgangType](../domeinen/TunnelgangType.html)||Default: None|Typering van het beheerobject.|
|volgnummer|volgnummer|TEXT(255,0)|PNH|Areaaldata|Enumeratie/Referentie|keuzelijst [VOLGNUMMER](../domeinen/VOLGNUMMER.html)||Default: None|Indien een reeks van dezelfde elementen voorkomen dan dienen deze worden met een volgnummer te worden geduid. De nummering dient logischerwijs te worden gestart met noord-georiënteerde item als eerste te benoemen en vervolgens de daaropvolgende items door te nummeren met de klok mee|
|windrichting|windrichting|TEXT(255,0)|PNH|Areaaldata|Enumeratie/Referentie|keuzelijst [WINDRICHTING](../domeinen/WINDRICHTING.html)||Default: None|Om de locatie van verschillende elementen aan te duiden|

***
