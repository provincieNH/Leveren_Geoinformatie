## AREAALDATA.geluidwerendeVoorziening_l

$ Feature dataset: Inrichtend

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ NEN 2767-4 / PNH
* __Positionele nauwkeurigheid:__ 5 cm
* __SHAPE:__ Lijn
* __Definitie:__ Onderdeel van een civiel-technisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen. De NEN 2767-4 decompositie wordt gevolgd, waarbij GELUIDWERENDE_VOORZIENING als Beheerobject is aangemaakt om het element 'geluidwerende constructie' van een bovenliggend beheerobject te voorzien.
Geluidwerende voorzieningen worden als zelfstandige objecten beheerd en niet als element van bv bruggen of wegen (zoals in de NEN 2767-4 beschreven).


***

|KOLOM                               |TYPE                   |DEFINITIE|
|------                              |----                   |-----    |
|OBJECTID                            |OID(38,0,0)            |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None|
|GLOBALID                            |GlobalID(38,0,0)       |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None|
|AD_ID                               |String(255,0,0)        |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None|
|GISIB_ID                            |Integer(0,10,0)        |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None|
|IDENTIFICATIE                       |String(255,0,0)        |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)        |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|OBJECTBEGINTIJD                     |Date(8,0,0)            |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)            |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|BEHEERDER                           |String(255,0,0)        |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None|
|ONDERHOUDER                         |String(255,0,0)        |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None|
|EIGENAAR                            |String(255,0,0)        |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None|
|OBJECTCODE                          |String(255,0,0)        |PNH; Identificatie van het object; Nullable: True; Default: None|
|BIJZONDERHEID                       |String(255,0,0)        |PNH; Extra toelichting; Nullable: True; Default: None|
|OMSCHRIJVING                        |String(255,0,0)        |PNH; Extra toelichting; Nullable: True; Default: None|
|FOTO                                |String(255,0,0)        |PNH; Locatie van de foto op de S schijf bij PNH. Deze hoeft niet gevuld te worden door de aannemer. Nullable: True; Default: None|
|HMBEGIN                             |Float(0,10,1)          |PNH; Hectometrering van begin van vlak, met 1 cijfer achter de punt. Voorbeeld 30.9 ; Nullable: True; Default: None|
|HMEIND                              |Float(0,10,1)          |PNH; Hectometrering van eind van vlak, met 1 cijfer achter de punt. Voorbeeld 30.9 ; Nullable: True; Default: None|
|AANLEGJAAR                          |SmallInteger(0,10,0)   |PNH; Aanlegjaar; Nullable: True|
|VERVANGINGSJAAR                     |SmallInteger(0,10,0)   |PNH; Het geplande jaar dat het object vervangen wordt; Nullable: True; Default: None|
|FUNDERINGTYPE                       |String(255,0,0)        |PNH; Fundering type; keuzelijst [FUNDERING_TYPE]; Nullable: True; Default: None|
|BEGROEID                            |String(1,0,0)          |PNH; Indicatie of geluidsscherm begroeid is: Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend]; Nullable: False; Default: O|
|TRAJECT                             |String(255,0,0)        |PNH; FK naar traject_v; Nullable: True; Default: None|
|LEVENSCYCLUS                        |String(255,0,0)        |PNH; Levenscyclus; keuzelijst [LEVENSCYCLUS]; Nullable: True; Default: None|
|TRAJECT                             |String(255,0,0)        |PNH; FK naar traject_v; Nullable: True; Default: None|
|CREATED_USER                        |String(255,0,0)        |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)            |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)         |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)            |PNH; Datum van de laatste mutatie; Nullable: True|
|DATALEVERANCIER                     |String(255,0,0)        |PNH; Leverancier van de data; Nullable: True; Default: None|
|SHAPE                               |Geometry               |PNH; Lijn|
|SHAPE_Length                        |Double(0,0,0)          |PNH; Lengte in meters, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False;; Default: None|


***
