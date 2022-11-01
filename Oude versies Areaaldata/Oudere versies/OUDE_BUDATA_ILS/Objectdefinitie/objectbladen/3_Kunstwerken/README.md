﻿# Kunstwerken

Een kunstwerk is een samenhangende eenheid binnen een verkeersinfrastructuur voor het vervoeren van mensen en goederen. Het maakt een veilige en betrouwbare kruising tussen landverkeer, scheepvaartverkeer, voorzieningen en water mogelijk. Het kan ook de aanvoer, afvoer, kering en berging van water mogelijk maken. 


Kenmerkend voor het kunstwerkbeheer is dat het gaat om een verzameling van objecten die samen een functioneel geheel vormen en die zijn gebonden door locatie. Waar er sprake is van complexe kunstwerken wordt er een onderverdeling aangebracht, in de vorm van een decompositie.

De NEN 2767-4 Decompositie wordt gevolgd voor Kunstwerken en Oeverconstructies. Waarbij de elementen en bouwdelen van Oeverconstructies in dezelde tabellen (element en bouwdeel) worden vastgelegd als de elementen en bouwdelen van kunstwerken. Om de objecteigenschappen zo nauwkeurig mogelijk te modelleren is er wel voor gekozen om het NEN Beheerobject in BU-Data op te 'knippen' in 4 verschillende objecten:

* KUNSTWERK_VAST
* KUNSTWERK_BEWEEGBAAR
* GELUIDWERENDE_VOORZIENING
* SCHUTSLUIS

Deze onderverdeling is vooral ingegeven door de verschillende objecteigenschappen (paspoortgegevens) die van deze objecten bijgehouden worden.

NB. GELUIDWERENDE_VOORZIENING is formeel in de NEN geen beheerobject. Een Geluidwerende Constructie komt in de NEN voor op Element niveau onder Wegen of Kunstwerken. Omdat PNH GELUIDSSCHERM als zelfstandig object beheerd is er voor gekozen om dit toch als entiteit op het hoogste niveau op te nemen.


![Kunstwerken](Kunstwerken.png)

### BGT

Kunstwerken is in het BUDATA datamodel opgebouwd conform de NEN 2767-4 decompositie. Overkoepelend is er nog een Complex gedefinieerd om Beheer objecten te bundelen in 1 te beheren object.
In deze decompositie wordt het Beheerobject met een punt, lijn of vlak vastgelegd. De Bouwdelen worden alleen alfanumeriek vastgelegd. De Elementen van Oeverconstructies (vaarwegen) en Geluidschermen hebben een lijngeometrie die overeen moet komen met het betreffende BGT object.
De BGT sluit niet aan op de NEN 2767-4. Er zijn aparte objecten gedefinieerd om de Kunstwerken conform BGT vast te kunnen leggen. Het is dus de bedoeling dat een kunstwerk zowel vastgelegd wordt conform de NEN als de BGT.

***

