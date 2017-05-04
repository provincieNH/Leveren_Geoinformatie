## AREAALDATA.kabelbed_v

$ Feature dataset: Functioneel

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL 2015
* __Positionele nauwkeurigheid:__ 7,5 cm
* __SHAPE:__ Vlak
* __Definitie:__ ruimtebeslag dat door een gemeenschappelijk tracé van één of meer kabels, buizen, HDPE- en-of mantebluizen - die toebehoren aan één netwerkbeheerder - wordt gevormd 

***

|KOLOM                               |TYPE              |DEFINITIE|
|------                              |----              |-----    |
|AANTALKABELS                        |SmallInteger(0,10,0)|Aantal kabels of buizen dat zich in een kabelbed bevindt. Conditie: Wordt opgenomen indien het aantal groter is dan 1, de kabels, buizen, HDPE- en/of mantelbuizen niet als afzonderlijke lijnen (kunnen) worden weergegeven en – in het geval van kabels - ze geen onderdeel uitmaken van een stervormig aangelegd aansluitnetwerk waarbij wordt voldaan aan de bij Ministeriële Regeling hieraan gestelde regels - Nullable: False|
|AFWIJKINGDIEPTE                     |String(255,0,0)     |Afwijking (cm) van de gangbare dieptelegging voor een leiding van dit thema. Wordt alleen opgenomen indien er sprake is van een legging die afwijkt van de gangbare legging voor dit thema. Aangegeven wordt of de diepte tov NAP of Maaiveld gerefereerd is. Voor het thema ‘Riool vrij verval’ is er geen sprake van een gangbare dieptelegging. De gerealiseerde dieptelegging kan echter wel met het attribuut afwijkendeDieptelegging worden opgenomen.- Nullable: False Default: None|
|bovengrondsZichtbaar                |String(1,0,0)       |Aangegeven wordt of het kabelbed bovengronds vanaf het maaiveld zichtbaar is, keuzelijst [jaNee] - Nullable: True Default: None|
|BREEDTE                             |Float(0,25,10)      |Breedte van het kabelbed (cm) - Nullable: True|
|OMSCHRIJVING                        |String(255,0,0)     |Extra toelichting - Nullable: True Default: None|
|OPMERKING                           |String(3000,0,0)    |Opmerking - Nullable: True Default: None|
|PRODUCT                             |String(255,0,0)     |Het product dat door de leiding vervoerd wordt of kan worden vervoerd - Nullable: True Default: None|
|MATERIAALTYPE                       |String(255,0,0)     |Type materiaal, keuzelijst [MATERIAALTYPE] - Nullable: True Default: None|
|SHAPE                               |Geometry            |Lijn|
|SHAPE_Length                        |Double(0,0,0)       |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|IDENTIFICATIE                       |String(255,0,0)    |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)    |Status van de gegevens, keuzelijst [VERWERKINGSSTATUS] - Nullable: False Default: Nieuw|
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
|HUIDIGESTATUS                       |String(50,0,0)       |Huidige status, keuzelijst [ConditionOfFacilityValue] - Nullable: False Default: None|
|INNETWERK                           |String(255,0,0)      |FK naar utiliteitsNet_tbl - Nullable: True Default: None|
|GEONAUWKEURIGHEIDXY                 |String(50,0,0)       |Nauwkeurigheid van de liggingsgegevens in het horizontale vlak, keuzelijst [NauwkeurigheidXYvalue] - Nullable: False Default: None|
|DIEPTELEGGING                       |String(255,0,0)      |FK naar diepteTovMaaiveld_p - Nullable: True Default: None|
|VERTICALE_POSITIE                   |Float(0,10,2)        |Verticale positie - Nullable: True Default: None|
|WAARSCHUWINGSTYPE                   |String(255,0,0)      |ToDo Waarschuwingstype - Nullable: True Default: None|
|LINK                                |String(255,0,0)      |FK naar utiliteitsLink_l - Nullable: True Default: None|

***
