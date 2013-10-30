# Arealen

De objectdefinitie is ingedeeld per Areaal. Dit is de indeling in Arealen zoals deze in de organisatie gebruikt wordt.


1. Algemeen
	Dit zijn de algemene objecten zoals traject, vaarwegtraject, kruispunt etc.
2. Verharding
	Wegen en Riolering
3. Kunstwerken
	conform de NEN 2767-4 decompositie aangevuld met de objecten noodzakelijk voor de BGT
4. Openbare verlichting & VRI
	Alle componenten die tot een OVL of VRI Installatie behoren, inclusief de mast, kast en matrix borden
5. Landschap & Milieu
	Alle groene objecten, inclusief stuw, bermsloten en beschoeiing van bermsloten
6. Meubilair
	Alle overige verkeersvoorzieningen
7. Vaarwegen
	Alle vaarwegobjecten zoals bodems en oeverconstructies. De NEN 2767-4 decompositie wordt hier ook gebruikt.
8. Kabels & Leidingen
	Alle Kabels en leidingen met uitzondering van riolering
9. Openbaar Vervoer
	Alle objecten die met OV te maken hebben en niet al in de andere arealen aanwezig zijn.
	
	
## Opbouw document

De objectdefinitie bestaat uit losse 'objectbladen' die in Markdown syntax geschreven zijn.
Vanuit de Markdown syntax kan eenvoudig een document in Word, Pdf of HTML formaat gegenereerd worden. Als niet het hele document van toepassing is, kunnen ook alleen de relevante objectbladen gebruikt worden.

De objectdefinities zijn op deze manier eenvoudiger te beheren in een versie beheer systeem. Meerdere mensen kunnen er tegelijk aan werken. 

## Identificatie

### GUID
Elk object heeft een unieke GUID (Global Unique Identifier). Bij het aanmaken van een nieuw object in de FileGeodatabase moet ook een nieuwe GUID gegenereert worden. Er wordt van de opdrachtnemer verwacht dat deze nieuwe GUID's genereert voor nieuwe objecten die worden aangemaakt in de database.

### ID
Er is in het model gekozen om sleutels als number(10) vast te leggen, naast de GUID's die als globale unieke identificatie door het systeem gebruikt worden.
Deze sleutels zijn in eerste instantie bedoelt om de relaties tussen objecten aan te kunnen geven (zie PK/FK hieronder)

### OBJECTID
Elk object heeft ook een OBJECTID, dit is een interne Identificatie die gebruikt wordt door de ArcGIS software. De waarde in dit attribuut kan veranderen door het kopieren/migreren van data met ArcGIS en is daarom niet altijd betrouwbaar als consistente sleutel. 


## Uitleg Definitie PK/FK

Elk object heeft een Primary Key (primaire sleutel) die ID heet. Een FK (verwijzende sleutel) heeft steeds de objectnaam waarnaar verwezen wordt.

De keuzelijsten in het BUDATA datamodel zijn ook allemaal eigen 'objecten'. Er staat dus vaak een verwijzing (FK voor Foreign Key) naar een ander object. Dit object kan in het deel Keuzelijsten (CT_) gevonden worden.
Om het BUDATA datamodel toch gebruiksvriendelijk te houden, wordt de waarde uit de keuzelijst die van toepassing is opgeslagen bij het object. 
Bijv. STATUS NUMBER(10,0) bij Boom is een verwijzing naar het ID attribuut van CT_STATUS. ST_CODE laat de waarde zien die de Status heeft voor de specifieke boom.

## Mutaties

### Actualiteit van de objectdefinities
Per object is er een objectblad met de documentatie van het object. Per blad wordt de versie bijgehouden. Het hele document wordt beheerd met het versiebeheersysteem 'GIT'. De wijzigingen in het document kunnen op deze manier makkelijk terug gevonden worden. De vigerende versie van het totale document is altijd beschikbaar in Word en pdf formaat.

### Actualiteit van de gegevens
Bij mutaties aan de areaal gegevens is het van belang dat er aan een aantal regels voldaan wordt:

__Nieuwe__ objecten krijgen een nieuwe GUID, de status 'NIEUW' en een objectbegintijd.

__Veranderingen__ aan objecten worden doorgevoerd door de status 'GEWIJZIGD' in te vullen en een nieuwe objectbegintijd.

__Vervallen__ objecten worden __NIET__ verwijderd, maar krijgen de status vervallen, en een objecteindtijd. 
Door objecten niet te verwijderen, maar een status en een verval datum mee te geven kunnen deze objecten ook uit de dataset bij de opdrachtgever verwijderd worden. 


