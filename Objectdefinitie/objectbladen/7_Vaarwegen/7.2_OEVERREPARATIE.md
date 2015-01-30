## BUDATA.OEVERREPARATIE


* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt
* __Geometrie:__ Punt
* __Definitie:__ To do


***

|KOLOM                           	|TYPE          	|DEFINITIE|
|------                          	|----          	|-----    |
|ID                              	|NUMBER(10,0)  	|Primary Key|
|GUID                            	|VARCHAR2(40)  	|Global Unique Identifier|
|STATUS                          	|VARCHAR2(255) 	|Status van de gegevens, keuzelijst [CT_STATUS]|
|OEVERVAK_ID						|NUMBER(10,0)	|FK naar Oevervak|
|JAAR								|NUMBER(10,0)	|Jaar uitvoering reparatie|
|OBJBEGINTIJD                    	|DATE          	|BGT, Datum waarop het object bij de bronhouder is ontstaan|
|OBJEINDTIJD                     	|DATE          	|BGT, Datum waarop het object bij de bronhouder niet meer geldig is|
|OBJECTID                        	|NUMBER(38,0)   |Interne ID ArcGIS|
|RAPPORT							|VARCHAR2(255)	|Pad naar rapport|

***


