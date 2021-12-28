# Objectdefinitie Areaaldata

Het Areaaldata model is een verdere detaillering van het IMGeo model, en is de opvolger van het BUDATA datamodel.
Het is gemaakt om beter aan te sluiten op landelijke standaarden. Het is opgedeeld in Featuredatasets conform de BGT.
Zie ook: [Toelichting Objectenhandboek BGT|IMGeo](http://imgeo.geostandaarden.nl/toelichting)

1. __Opdelend: __
	Het terrein in de werkelijkheid wordt gerepresenteerd door opdelende objecten, zoals Wegdeel, Waterdeel en Terreindeel, 
	waarvoor geldt dat deze elkaar niet mogen overlappen en waarbij elk stuk terrein in de werkelijkheid door een object gerepresenteerd wordt.

2. __Inrichtend: __
	Inrichtende objecten dienen ter nadere detaillering van de opdelende objecten. Dit zijn objecten zoals inrichtingselement, Boom, Bord etc.

3. __Functioneel: __
	Functionele objecten zijn bedoeld om een logische samenhang in het areaal aan te brengen. Dit zijn vooral objecten die door PNH zelf zijn gedefinieerd.


	
## Opbouw document

De objectdefinitie bestaat uit losse 'objectbladen' die in Markdown syntax geschreven zijn.
Vanuit de Markdown syntax kan eenvoudig een document in Word, Pdf of HTML formaat gegenereerd worden. Als niet het hele document van toepassing is, kunnen ook alleen de relevante objectbladen gebruikt worden.

De objectdefinities zijn op deze manier eenvoudiger te beheren in een versie beheer systeem. Meerdere mensen kunnen er tegelijk aan werken. 

# Aandachtspunten

## Identificatievelden

### IDENTIFICATIE
Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID 
LET OP: Deze identificatie wordt uitgegeven door de BGT applicatie. Opdrachtnemers hoeven dit attribuut voor nieuwe objecten NIET aan te maken.


### GlobalID
Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software die het beheer van replica's voor mutaties bijhoudt. Dit attribuut zal in de komende 4.3 datamodel update gesaneerd worden.

### GISIB_ID
In de gebruikte beheersoftware Gisib worden er ID's van number(10) gebruikt om relaties vast te leggen.
Deze sleutels zijn in eerste instantie bedoelt om de relaties tussen objecten aan te kunnen geven. In Areaaldata worden deze opgenomen in het GISIB_ID.
Alle objecten in Areaaldata die ook in Gisib voorkomen hebben dit attribuut. Opdrachtnemers hoeven dit attribuut niet te vullen voor nieuwe objecten, en laten het attribuut voor gewijzigde objecten ongemoeid.

### AD_ID
AD_ID is de leidende primaire sleutel in de AREAALDATA database. De relaties tussen objecten lopen via AD_ID.
Opdrachtnemers dienen een uniek AD_ID aan te maken voor nieuwe objecten. Het format van AD_ID is <AD.32 hexadecimale karakters>.


Hiervoor kan een GUID/UUID generator gebruikt worden met een prefix AD. bv: AD.233C2952516E4557B9322FE23FD50263
Van bestaande objecten mag het AD_ID NIET veranderd worden.


### OBJECTID
Elk object heeft ook een OBJECTID, dit is een interne Identificatie die gebruikt wordt door de ArcGIS software. De waarde in dit attribuut kan veranderen door het kopieren/migreren van data met ArcGIS en is daarom niet betrouwbaar als consistente sleutel. 


## Relaties

Relaties worden gevormd via foreign keys met het AD_ID van de gerelateerde objecten.
De relaties dienen gevuld te worden bij actualisatie van de data.

## Domeinen

Keuzelijsten zijn opgenomen als domeinen in de geodatabase. Dit betekend dat in de editor van ArcGIS automatisch een keuzelijst getoond wordt met mogelijke waarden.
Het kan incidenteel voorkomen dat de ingevulde waarde niet overeenkomt met een waarde in de domeinlijst. Dit komt doordat er wel hernieuwd is afgestemd welke waarde gewenst zijn, maar de bestaande data nog niet altijd veranderd is.

Het kan ook voorkomen dat een gewenste waarde nog niet in een domeinlijst voorkomt. (bijvoorbeeld een nieuw type armatuur) In deze gevallen moet er altijd contact opgenomen worden met de opdrachtgever om af te stemmen of de domeinwaarde toegevoegd mag worden.
Bij BGT-attributen mogen nooit domeinwaarden worden toegevoegd. Wanneer onduidelijk is welke beschikbare waarde gekozen dient te worden, kan contact op worden genomen met de opdrachtgever.

## Mutaties

### Actualiteit van de objectdefinities
Per object is er een objectblad met de documentatie van het object. Per blad wordt de versie bijgehouden. Het hele document wordt beheerd met het versiebeheersysteem 'Git'. 
De wijzigingen in het document kunnen op deze manier makkelijk terug gevonden worden. De vigerende versie van het totale document is altijd beschikbaar in Word en pdf formaat.


### Status
Er is een __Status__ attribuut van de BGT (met de waardes plan, bestaand en historisch), hiermee kan de levenscyclus van een object vastgelegd worden.
Er is ook een __VerwerkingsStatus__ (met de waardes Nieuw, Gewijzigd, Vervallen, Actueel), dit is bedoeld om de mutatiestatus door te geven in de uitwisseling tussen opdrachtgever en opdrachtnemer.

### Mutatieverwerking
Bij mutaties aan de areaal gegevens is het van belang dat er aan een aantal regels voldaan wordt:

__Nieuwe__ objecten krijgen een nieuw AD_ID, de __VerwerkingsStatus__ 'NIEUW' en een objectbegintijd.

__Veranderingen__ aan objecten worden doorgevoerd door de __VerwerkingsStatus__ 'GEWIJZIGD' in te vullen.

__Vervallen__ objecten worden __NIET__ verwijderd, maar krijgen de __VerwerkingsStatus__ vervallen, en een objecteindtijd. 
Door objecten niet te verwijderen, maar een status en een verval datum mee te geven kunnen deze objecten ook uit de dataset bij de opdrachtgever verwijderd worden. 


# Objectbladen
