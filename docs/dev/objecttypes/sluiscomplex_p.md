## AREAALDATA.sluiscomplex_p

* [__Areaaldata model versie:__ 5](https://provincienh.github.io/Leveren_Geoinformatie/dev/)
* __Herkomst Definitie:__ IMBOR/NEN3610
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Punt
* __Definitie:__ Functioneellaag die kunstwerk_p vervangt. Kunstwerk met een beweegbare waterkering, dat de verbinding vormt tussen twee wateren.
* __MappingBGT:__ n.v.t.
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
|shape|shape|DOUBLE(0,0)|PNH|AREAALDATA|Waarde wordt automatisch bepaald|||Default: None|Locatie van het beheerobject.|
|adres|adres|TEXT(255,0)|PNH|Areaaldata|Vrij invoerveld||Verwijzende sleutel naar [adres_tbl]|Default: None|Verwijzende sleutel naar adres_tbl (simpel)|
|afstandsbediening|afstandsbediening|TEXT(3,0)|IMBOR|Sluis|Enumeratie/Referentie|keuzelijst [JaNeeOnbekend](../domeinen/JaNeeOnbekend.html)||Default: None|Aanduiding voor het op afstand bedienen van een beheerobject: Ja/Nee/Onbekend.|
|beheerder|beheerder|TEXT(255,0)|IMBOR|Beheerd object|Enumeratie/Referentie|keuzelijst [BeheerdObjectBeheerder](../domeinen/BeheerdObjectBeheerder.html)||Default: None|Een publiekrechtelijke instantie of (rechts)persoon die toeziet op de instandhouding van o.a. een object, kunstwerk of waterstaatswerk. De typen beheerder zijn conform de indeling in bronhouders (BGT).|
|beheerder_gedetailleerd|beheerder gedetailleerd|TEXT(255,0)|IMBOR|Beheerd object|Enumeratie/Referentie|keuzelijst [BeheerdObjectBeheerderGedetailleerd](../domeinen/BeheerdObjectBeheerderGedetailleerd.html)||Default: None|Nadere aanduiding van de beheerder van het beheerobject.|
|beheergebied|beheergebied|TEXT(255,0)|IMBOR|Beheerd object|Enumeratie/Referentie|keuzelijst [GCR_NAAM](../domeinen/GCR_NAAM.html)|Verwijzende sleutel naar [gebiedscontractregio_v]|Default: None|De provincie heeft haar gebied in 8 gebieden opgesplitst. Amsterdam (gebied 8) is zelfstandig. Aanduiding van het beheergebied waarbinnen het beheerobject ligt. Bevat een verwijzende sleutel naar gebiedscontractregio_v (simpel). AD_ID foreign key.|
|beheerobject_subtype|beheerobject subtype|TEXT(255,0)|PNH|Areaaldata|Enumeratie/Referentie|keuzelijst [BEHEER_OBJECT_SUBTYPE](../domeinen/BEHEER_OBJECT_SUBTYPE.html)||Default: None|Beheerobject subtype.|
|bouwjaar|bouwjaar|SHORT(5,0)|IMBOR|Constructie|Vrij invoerveld|||Default: None|Bouwjaar van het object. Deze kan afwijken van het jaar van aanleg, bijvoorbeeld wanneer een beheerobject hergebruikt wordt.|
|bouwjaar_remmingswerk|bouwjaar remmingswerk|SHORT(5,0)|PNH|Areaaldata|Vrij invoerveld|||Default: None|Bouwjaar Remmingswerk.|
|breedte|breedte (m)|DOUBLE(10,3)|IMBOR|Kunstwerk|Vrij invoerveld|||Default: None|Breedte van het beheerobject in meters.|
|conformnen|conformnen|TEXT(3,0)|PNH|Areaaldata|Enumeratie/Referentie|keuzelijst [JaNeeOnbekend](../domeinen/JaNeeOnbekend.html)||Default: None|Indicatie of classificatie conform NEN is: Ja/Nee/Onbekend.|
|doorvaartbreedte|doorvaartbreedte|DOUBLE(10,3)|IMBOR|Aquaduct|Vrij invoerveld|||Default: None|Doorvaartbreedte van het object of van een opening van het object in meters. Meetnauwkeurigheid +/- 1 cm.|
|eigenaar|eigenaar|TEXT(255,0)|IMBOR|Beheerd object|Enumeratie/Referentie|keuzelijst [BeheerdObjectEigenaar](../domeinen/BeheerdObjectEigenaar.html)||Default: None|(Rechts)persoon die het meest omvattend recht op een zaak heeft. De typen eigenaren zijn conform de indeling in bronhouders (BGT).|
|eigenaar_gedetailleerd|eigenaar gedetailleerd|TEXT(255,0)|IMBOR|Beheerd object|Enumeratie/Referentie|keuzelijst [BeheerdObjectEigenaarGedetailleerd](../domeinen/BeheerdObjectEigenaarGedetailleerd.html)||Default: None|Nadere aanduiding van de eigenaar van het beheerobject.|
|foto|foto|TEXT(255,0)|PNH|Areaaldata|Vrij invoerveld|||Default: None|Een URL naar de digitale locatie op de scharepointomgeving van de PNH waar de foto is opgeslagen.|
|gedeeld_beheer|gedeeld beheer|TEXT(255,0)|IMBOR|Overbrugging|Enumeratie/Referentie|keuzelijst [JaNee](../domeinen/JaNee.html)||Default: None|Aanduiding voor het registreren van gedeeld beheer van het object.|
|gemeentenaam|gemeentenaam|TEXT(255,0)|IMBOR|Gebiedsindeling|Enumeratie/Referentie|keuzelijst [Gemeentenaam](../domeinen/Gemeentenaam.html)||Default: None|Naam van de gemeente waarbinnen het beheerobject ligt.|
|gisib_id|gisib id|LONG(10,0)|PNH|Areaaldata|Vrij invoerveld|||Default: None|Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer.|
|hoofdroute|hoofdroute|TEXT(255,0)|PNH|Areaaldata|Enumeratie/Referentie|keuzelijst [Hoofdroute](../domeinen/Hoofdroute.html)|Verwijzende sleutel naar [weg_v]|Default: None|Verwijzende sleutel naar weg_v (simpel)|
|hoofdvaarroute|hoofdvaarroute|TEXT(255,0)|PNH|Sluis|Enumeratie/Referentie|keuzelijst [Vaarwegdeeltraject](../domeinen/Vaarwegdeeltraject.html)|Verwijzende sleutel naar [vaarweg_v]|Default: None|Verwijzende sleutel naar vaarweg_v (simpel)|
|hoogte|hoogte (m)|DOUBLE(10,3)|IMBOR|Kunstwerk|Vrij invoerveld|||Default: None|Hoogte van het beheerobject in meters.|
|hoogte_sluiskolken|hoogte sluiskolken|DOUBLE(10,3)|IMBOR|Sluis|Vrij invoerveld|||Default: None|Hoogte van de sluiskolken.|
|kilometrering|kilometrering|FLOAT(6,2)|PNH|Areaaldata|Vrij invoerveld|||Default: None|Kilometrering alleen bij kunstwerken die langs een weg liggen. Gemeten per hectometer|
|lengte|lengte (m)|DOUBLE(10,3)|IMBOR|Kunstwerk|Vrij invoerveld|||Default: None|Lengte van het beheerobject in meters.|
|loopdek|loopdek|TEXT(255,0)|PNH|Areaaldata|Enumeratie/Referentie|keuzelijst [JaNee](../domeinen/JaNee.html)||Default: None|Loopdek Ja/Nee/Onbekend.|
|monument|monument|TEXT(255,0)|PNH|Areaaldata|Enumeratie/Referentie|keuzelijst [JaNee](../domeinen/JaNee.html)||Default: None|Het object heeft een monumentele status.|
|objectnaam|naam kunstwerk|TEXT(255,0)|IMBOR|ReëelObject|Vrij invoerveld|||Default: None|Naam van het beheerobject.|
|objectnummer|topcode|TEXT(255,0)|IMBOR|ReëelObject|Vrij invoerveld|||Default: None|Nummer van het beheerobject, door de organisatie zelf in te delen. Topcodebepaald PNH zelf|
|omtrek|omtrek (m)|DOUBLE(10,3)|PNH|Areaaldata|Vrij invoerveld|||Default: None|Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length.|
|onderhoudsplichtige|onderhoudsplichtige|TEXT(255,0)|IMBOR|Beheerd object|Enumeratie/Referentie|keuzelijst [BeheerdObjectOnderhoudsplichtige](../domeinen/BeheerdObjectOnderhoudsplichtige.html)||Default: None|Organisatie die verantwoordelijk is voor het onderhoud van het beheerobject.|
|oppervlakte|oppervlakte (m2)|DOUBLE(10,3)|IMBOR|Kunstwerk|Vrij invoerveld|||Default: None|Oppervlakte van het beheerobject in m2, overgenomen van BGT/IMGeo.|
|remmingswerk_vervangingsjaar|remmingswerk vervangingsjaar|SHORT(5,0)|PNH|Areaaldata|Vrij invoerveld|||Default: None|Vervangingsjaar Remwerk.|
|renovatiejaar|renovatiejaar|SHORT(5,0)|PNH|Areaaldata|Vrij invoerveld|||Default: None|Renovatiejaar.|
|status|status|TEXT(255,0)|IMBOR|Areaaldata|Enumeratie/Referentie|keuzelijst [Geo-ObjectStatus](../domeinen/Geo-ObjectStatus.html)||Default: None|Status van het beheerobject in het inwinningsproces van de geometrie. Wordt gebruikt voor schets- en definitieve geometrie.|
|theoretisch_eindjaar|theoretisch eindjaar|SHORT(5,0)|IMBOR|Reëel object|Vrij invoerveld|||Default: None|Jaar dat het beheerobject aan het theoretische einde van haar levensduur is.|
|tweede_beheerder|tweede beheerder|TEXT(255,0)|IMBOR|Overbrugging|Enumeratie/Referentie|keuzelijst [ObjectTweedeBeheerder](../domeinen/ObjectTweedeBeheerder.html)||Default: None|Registratie van de tweede beheerder in geval van gedeeld beheer.|
|tweede_eigenaar|tweede eigenaar|TEXT(255,0)|IMBOR|Overbrugging|Enumeratie/Referentie|keuzelijst [ObjectTweedeEigenaar](../domeinen/ObjectTweedeEigenaar.html)||Default: None|Registratie van de tweede eigenaar in geval van gedeeld eigenaarschap.|
|type|sluis type|TEXT(255,0)|IMBOR|Sluis|Enumeratie/Referentie|keuzelijst [SluisType](../domeinen/SluisType.html)||Default: None|Typering van het beheerobject.|
|type_bediening|type bediening|TEXT(255,0)|IMBOR|Sluis|Enumeratie/Referentie|keuzelijst [SluisTypeBediening](../domeinen/SluisTypeBediening.html)||Default: None|Aanduiding van het type bediening van het object.|
|wachtplaats_vervangingsjaar|wachtplaats vervangingsjaar|SHORT(5,0)|PNH|Areaaldata|Vrij invoerveld|||Default: None|Vervangingsjaar wachtplaats.|
|waterschapnaam|waterschapnaam|TEXT(255,0)|IMBOR|Gebiedsindeling|Enumeratie/Referentie|keuzelijst [Waterschap](../domeinen/Waterschap.html)||Default: None|Aanduiding van het waterschap, waarbinnen het beheerobject ligt. Overname uit IMGeo-bestand met waterschapsgrenzen.|

***
