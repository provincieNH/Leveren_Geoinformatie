## AREAALDATA.waterloop_l

$ Feature dataset: Inrichtend

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 25 cm
* __Geometrie:__ Lijn
* __Definitie:__ Terrein ingericht voor afvoer en berging van oppervlaktewater. BGT kent alleen vlakken. Dit objecttype zal uitgefaseerd worden.

***

|KOLOM                               |TYPE          	       |DEFINITIE|
|------                              |----          	       |-----    |
|OBJECTID                            |OID(38,0,0)              |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None|
|GLOBALID                            |GlobalID(38,0,0)         |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None|
|AD_ID                               |String(255,0,0)          |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None|
|GISIB_ID                            |Integer(0,10,0)          |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None|
|IDENTIFICATIE                       |String(255,0,0)          |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None|
|STATUS                              |String(10,0,0)           |BGT; BGT status van het object; keuzelijst [status]; Nullable: False; Default: bestaand|
|OBJECTBEGINTIJD                     |Date(8,0,0)              |BGT; Datum waarop het object bij de bronhouder is ontstaan; Nullable: False|
|OBJECTEINDTIJD                      |Date(8,0,0)              |BGT; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|VERWERKINGSSTATUS                   |String(255,0,0)          |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|BEHEERDER                           |String(255,0,0)          |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None|
|ONDERHOUDER                         |String(255,0,0)          |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None|
|EIGENAAR                            |String(255,0,0)          |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None|
|TYPESPEC                            |String(255,0,0)          |PNH; Nadere typering van het object; keuzelijst [typeSpecWTL]; Nullable: True; Default: None|
|CAT_WATERLOOP                       |String(255,0,0)          |PNH; Categorie waterloop; keuzelijst [CAT_WATERLOOP]; Nullable: True; Default: None|
|JAAR_PLAATSING_AANLEG_GESCHAT       |String(1,0,0)            |PNH; Jaar plaatsing of aanleg is geschat: ja of nee; keuzelijst [jaNee]; Nullable: True; Default: N|
|BODEMHOOGTE                         |Float(0,25,10)           |PNH; Hoogte t.o.v. NAP; Nullable: True|
|BIJZONDEREWAARDE                    |String(255,0,0)          |PNH; Indicatie van bijzondere waarde; Nullable: True; Default: None|
|OPMERKINGMBTONDERH                  |String(255,0,0)          |PNH; Opmerking met betrekking tot het onderhoud; Nullable: True; Default: None|
|PEILVAST                            |Float(0,25,10)           |PNH; Vaste peil; Nullable: True|
|PEILWINTER                          |Float(0,25,10)           |PNH; Winter peil; Nullable: True|
|PEILZOMER                           |Float(0,25,10)           |PNH; Zomer peil; Nullable: True|
|VERKANTINGTALUD                     |String(255,0,0)          |PNH; TODO; Nullable: True; Default: None|
|WATERBREEDTE                        |Float(0,25,10)           |PNH; Breedte Natte profiel in meters (2 decimalen); Nullable: True|
|SLOOTVEGETATIE                      |String(1,0,0)            |PNH; Slootvegetatie dient verwerkt te worden: Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N|
|WATERDIEPTE                         |Float(0,25,10)           |PNH; TODO; Nullable: True|
|WATERSCHAP                          |String(30,0,0)           |PNH; Naam Waterschap; keuzelijst [WATERSCHAP]; Nullable: True; Default: None|
|BERICHT_ID                          |String(128,0,0)          |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|TRAJECT                             |String(255,0,0)          |PNH; FK naar traject_v; Nullable: True; Default: None|
|DATALEVERANCIER                     |String(255,0,0)          |PNH; Leverancier van de data; Nullable: True; Default: None|
|CREATED_USER                        |String(255,0,0)          |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)              |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)           |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)              |PNH; Datum van de laatste mutatie; Nullable: True|
|SHAPE                               |Geometry                 |PNH; Lijn|
|SHAPE_Length                        |Double(0,0,0)            |PNH; Lengte in meters, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None|



***
