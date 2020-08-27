# Kunstwerken

Een kunstwerk is een samenhangende eenheid binnen een verkeersinfrastructuur voor het vervoeren van mensen en goederen. Het maakt een veilige en betrouwbare kruising tussen landverkeer, scheepvaartverkeer, voorzieningen en water mogelijk. Het kan ook de aanvoer, afvoer, kering en berging van water mogelijk maken. 

Kenmerkend voor het kunstwerkbeheer is dat het gaat om een verzameling van objecten die samen een functioneel geheel vormen en die zijn gebonden door locatie. Waar er sprake is van complexe kunstwerken wordt er een onderverdeling aangebracht, in de vorm van een decompositie.

De NEN 2767-4 Decompositie wordt gevolgd voor Kunstwerken en Oeverconstructies. Tevens wordt afgeweken van de NEN2767-4 door ook geluidswerende voorzieningen als beheerobject te benaderen. Voor bevorderen van het assetmanagement worden van de genoemde typen beheerobjecten ook de elementen en bouwdelen vastgelegd.


| | | | |
|------          |----         |----                        |----|
|__Beheerobject__ |	kunstwerk_p	| geluidwerendeVoorziening_l |	oevervak_v|
|__Element__ |	kwElement_tbl |	scheidingGeluidsscherm_l |	scheidingWater_l|
|__Bouwdeel__ |	bouwdeelKunstwerk_tbl |	bouwdeelGeluidscherm_tbl |	bouwdeelOevervak_tbl|

Om te voldoen aan het vereiste van de BGT worden de objecten met een topografisch component ook in de vorm van opdelende en inrichtende features vastgelegd. Bijvoorbeeld een hek op een brug moet zowel in scheiding_l als in bouwdeelKunstwerk_tbl worden vastgelegd. Ook zijn er voor de BGT specifieke aan een kunstwerken gerelateerde objecten, welke hieronder bij het kopje ‘BGT’ worden benoemd. 

### Relaties

![Kunstwerk relaties](D:\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.2d3\Objectbladen\03_Kunstwerken\kw_relaties.png)

### BGT

Omdat de BGT niet aanluit op de NEN 2767-4 zijn er zijn aparte objecten gedefinieerd om de Kunstwerken conform BGT vast te kunnen leggen. Het is dus de bedoeling dat een kunstwerk zowel vastgelegd wordt conform de NEN als de BGT. Specifiek voor kunstwerken bestaan de volgende objecten:

•	kunstwerkdeel_mp/l/v
•	tunneldeel_v
•	overbruggingsdeel_v

***

