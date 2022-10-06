## AREAALDATA.waterinrichtingselement_l

$ Feature dataset: Inrichtend

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH/IMGEO
* __Positionele nauwkeurigheid:__ 7,5 cm
* __Geometrie:__ Lijn
* __Definitie:__ Een ruimtelijk object ter inrichting van het water. Dit objecttype is bedoeld om alleenstaande geleide- of remmingswerken in op te nemen. Daar waar een geleide- of 
                remmingswerk onderdeel uitmaakt van een kunstwerk wordt dit opgenomen in de NEN-2767-4 decompositie van het kunstwerk. In deze decompositie worden verder geen 
                geometrieën vastgelegd.

***

|KOLOM                              |TYPE          	        |DEFINITIE|
|------                          	|----          	        |-----    |
|OBJECTID                           |OID(38,0,0)            |Interne ID ArcGIS - Nullable: False|
|BGTPLUSTYPE                        |String(50,0,0)         |Beschrijving - keuzelijst [typeWTILijn] Nullable: False Default: None|
|IDENTIFICATIE                      |String(255,0,0)        |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|STATUS                             |String(10,0,0)         |Beschrijving - keuzelijst [status] Nullable: False Default: :bestaand|
|BRONHOUDER                         |String(5,0,0)          |BGT, De bronhoudercode van het object, keuzelijst [bronhouder] - Nullable: False Default: None|
|INONDERZOEK                        |String(1,0,0)          |BGT, Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N|
|RELATIEVEHOOGTELIGGING             |SmallInteger(0,10,0)   |BGT, Aanduiding voor de relatieve hoogte van het object - Nullable: False Default: 0|
|TIJDSTIPREGISTRATIE                |Date(8,0,0)            |Beschrijving - keuzelijst [] Nullable: True Default: None|
|EINDREGISTRATIE                    |Date(8,0,0)            |Beschrijving - keuzelijst [] Nullable: True Default: None|
|LV_PUBLICATIEDATUM                 |Date(8,0,0)            |BGT, Tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening - Nullable: True|
|BERICHT_ID                         |String(128,0,0)        |Beschrijving - keuzelijst [] Nullable: True Default: None|
|SHAPE                              |Geometry(0,0,0)        |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Length                       |Double(0,0,0)          |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|TYPESPEC                           |String(255,0,0)        |Nadere typering van het object, keuzelijst [typeSpecWIILijn] - Nullable: True Default: None|
|VERWERKINGSSTATUS                  |String(255,0,0)        |Status van de gegevens, keuzelijst [VERWERKINGSSTATUS] - Nullable: False Default: Nieuw|
|OBJECTID                           |OID(38,0,0)            |Interne ID ArcGIS - Nullable: False|
|GLOBALID                           |GlobalID(38,0,0)       |Global Unique Identifier - Nullable: False|
|GISIB_ID                           |Integer(0,10,0)        |ID beheer openbare ruimte (GISIB) - Nullable: True|
|AD_ID                               |String(255,0,0)    |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]' - Nullable: False Default: None|
|OBJECTBEGINTIJD                    |Date(8,0,0)            |Datum waarop het object bij de bronhouder is ontstaan - Nullable: True|
|OBJECTEINDTIJD                     |Date(8,0,0)            |Datum waarop het object bij de bronhouder niet meer geldig is - Nullable: True|
|CREATED_USER                       |String(255,0,0)        |Naam van gebruiker die de rij heeft aangemaakt - Nullable: True Default: None|
|CREATED_DATE                       |Date(8,0,0)            |Aanmaakdatum - Nullable: True|
|LAST_EDITED_USER                   |String(50,0,0)         |Naam van gebruiker die de laatste mutatie heeft doorgevoerd - Nullable: True Default: None|
|LAST_EDITED_DATE                   |Date(8,0,0)            |Datum van de laatste mutatie - Nullable: True|
|BEHEERDER                          |String(255,0,0)        |Beheerder van het object, keuzelijst [BEHEERDER] - Nullable: True Default: None|
|ONDERHOUDER                        |String(255,0,0)        |Onderhouder van het object, keuzelijst [ONDERHOUDER] - Nullable: True Default: None|
|EIGENAAR                           |String(255,0,0)        |Eigenaar van het object, keuzelijst [INSTANTIE] - Nullable: True Default: None| 
|DATALEVERANCIER                    |String(255,0,0)        |Leverancier van de data - Nullable: True Default: None|


***
