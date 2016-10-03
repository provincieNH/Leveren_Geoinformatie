## AREAALDATA.geluidwerendeVoorziening_l

$ Feature dataset: Inrichtend

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ NEN 2767-4 / PNH
* __Positionele nauwkeurigheid:__ 5 cm
* __SHAPE:__ Lijn
* __Definitie:__ Onderdeel van een civiel-technisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen. De NEN 2767-4 decompositie wordt gevolgd, waarbij GELUIDWERENDE_VOORZIENING als Beheerobject is aangemaakt om het element 'geluidwerende constructie' van een bovenliggend beheerobject te voorzien.
Geluidwerende voorzieningen worden als zelfstandige objecten beheerd en niet als element van bv bruggen of wegen (zoals in de NEN 2767-4 beschreven).


***

|KOLOM                               |TYPE              |DEFINITIE|
|------                              |----              |-----    |
|OBJECTCODE                          |String(255,0,0)     |Identificatie van het object - Nullable: True Default: None|
|BIJZONDERHEID                       |String(255,0,0)     |Extra toelichting - Nullable: True Default: None|
|OMSCHRIJVING                        |String(255,0,0)     |Extra toelichting - Nullable: True Default: None|
|FOTO                                |String(255,0,0)     |URL naar Afbeelding - Nullable: True Default: None||
|HMBEGIN                             |Float(0,25,10)      |Kilometrering start Geluidwerende voorziening - Nullable: True|
|HMEIND                              |Float(0,25,10)      |Kilometrering eind Geluidwerende voorziening - Nullable: True|
|AANLEGJAAR                          |SmallInteger(0,10,0)|Aanlegjaar Nullable: True|
|VERVANGINGSJAAR                     |SmallInteger(0,10,0)|Vervangingsjaar - Nullable: True|
|FUNDERINGTYPE                       |String(255,0,0)     |Fundering type, keuzelijst [FUNDERING_TYPE] - Nullable: True Default: None|
|BEGROEID                            |String(1,0,0)       |Indicatie of geluidsscherm begroeid is: Ja/Nee/Onbekend, keuzelijst [jaNeeOnbekend] Nullable: False Default: O|
|LEVENSCYCLUS                        |String(255,0,0)     |Levenscyclus, keuzelijst [LEVENSCYCLUS] - Nullable: True Default: None|
|REGIO                               |String(255,0,0)     |Regio naam, keuzelijst [REGIO] - Nullable: True Default: None|
|SHAPE                               |Geometry            |Lijn|
|SHAPE_Length                        |Double(0,0,0)       |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|TRAJECT                             |String(255,0,0)     |FK naar traject_v - Nullable: True Default: None|
|WEG                                 |String(255,0,0)     |FK naar weg_l - Nullable: True Default: None|
|VAARWEG                             |String(255,0,0)     |FK naar vaarweg_l - Nullable: True Default: None|
|IDENTIFICATIE                       |String(255,0,0)    |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)    |Status van de gegevens, keuzelijst [VERWERKINGSSTATUS] - Nullable: False Default: Nieuwl|
|OBJECTID                            |OID(38,0,0)        |Interne ID ArcGIS - Nullable: False|
|GLOBALID                            |GlobalID(38,0,0)   |Global Unique Identifier - Nullable: False|
|GISIB_ID                            |Integer(0,10,0)    |ID beheer openbare ruimte (GISIB) - Nullable: True|
|AD_ID                               |String(255,0,0)    |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]' - Nullable: False Default: None|
|OBJECTBEGINTIJD                     |Date(8,0,0)        |Datum waarop het object bij de bronhouder is ontstaan - Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)        |Datum waarop het object bij de bronhouder niet meer geldig is - Nullable: True|
|CREATED_USER                        |String(255,0,0)    |Naam van gebruiker die de rij heeft aangemaakt - Nullable: True Default: None|
|CREATED_DATE                        |Date(8,0,0)        |Aanmaakdatum - Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)     |Naam van gebruiker die de laatste mutatie heeft doorgevoerd - Nullable: True Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)        |Datum van de laatste mutatie - Nullable: True|
|BEHEERDER                           |String(255,0,0)    |Beheerder van het object, keuzelijst [BEHEERDER] - Nullable: True Default: None|
|ONDERHOUDER                         |String(255,0,0)    |Onderhouder van het object, keuzelijst [ONDERHOUDER] - Nullable: True Default: None|
|EIGENAAR                            |String(255,0,0)    |Eigenaar van het object, keuzelijst [INSTANTIE] - Nullable: True Default: None| 
|DATALEVERANCIER                     |String(255,0,0)    |Leverancier van de data - Nullable: True Default: None|


***
