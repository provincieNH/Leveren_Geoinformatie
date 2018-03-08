## AREAALDATA.kabelbed_v

$ Feature dataset: Functioneel

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL 2015
* __Positionele nauwkeurigheid:__ 7,5 cm
* __SHAPE:__ Vlak
* __Definitie:__ ruimtebeslag dat door een gemeenschappelijk tracé van één of meer kabels, buizen, HDPE- en-of mantebluizen; die toebehoren aan één netwerkbeheerder; wordt gevormd 

***

|KOLOM                               |TYPE                 |DEFINITIE|
|------                              |----                 |-----    |
|OBJECTID                            |OID(38,0,0)          |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None|
|GLOBALID                            |GlobalID(38,0,0)     |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None|
|AD_ID                               |String(255,0,0)      |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None|
|GISIB_ID                            |Integer(0,10,0)      |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None|
|IDENTIFICATIE                       |String(255,0,0)      |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)      |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|HUIDIGESTATUS                       |String(50,0,0)       |IMKL; Huidige status; keuzelijst [ConditionOfFacilityValue]; Nullable: False; Default: None|
|STATUS                              |String(10,0,0)       |BGT; BGT status van het object; keuzelijst [status]; Nullable: True; Default: bestaand
|OBJECTBEGINTIJD                     |Date(8,0,0)          |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)          |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|BEHEERDER                           |String(255,0,0)      |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None|
|ONDERHOUDER                         |String(255,0,0)      |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None|
|EIGENAAR                            |String(255,0,0)      |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None|
|AANTALKABELS                        |SmallInteger(0,10,0) |PNH; Aantal kabels of buizen dat zich in een kabelbed bevindt. Conditie: Wordt opgenomen indien het aantal groter is dan 1, de kabels, buizen, HDPE- en/of mantelbuizen niet als afzonderlijke lijnen (kunnen) worden weergegeven en – in het geval van kabels; ze geen onderdeel uitmaken van een stervormig aangelegd aansluitnetwerk waarbij wordt voldaan aan de bij Ministeriële Regeling hieraan gestelde regels; Nullable: False|
|AFWIJKINGDIEPTE                     |String(255,0,0)      |PNH; Afwijking (cm) van de gangbare dieptelegging voor een leiding van dit thema. Wordt alleen opgenomen indien er sprake is van een legging die afwijkt van de gangbare legging voor dit thema. Aangegeven wordt of de diepte tov NAP of Maaiveld gerefereerd is. Voor het thema ‘Riool vrij verval’ is er geen sprake van een gangbare dieptelegging. De gerealiseerde dieptelegging kan echter wel met het attribuut afwijkendeDieptelegging worden opgenomen; Nullable: False; Default: None|
|bovengrondsZichtbaar                |String(1,0,0)        |IMKL; Aangegeven wordt of het kabelbed bovengronds vanaf het maaiveld zichtbaar is; keuzelijst [jaNee]; Nullable: True; Default: None|
|BREEDTE                             |Float(0,25,10)       |PNH; Breedte van het kabelbed (cm); Nullable: True|
|PRODUCT                             |String(255,0,0)      |PNH; Het product dat door de leiding vervoerd wordt of kan worden vervoerd; Nullable: True; Default: None|
|MATERIAALTYPE                       |String(255,0,0)      |PNH; Type materiaal; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None|
|GEONAUWKEURIGHEIDXY                 |String(50,0,0)       |PNH; Nauwkeurigheid van de liggingsgegevens in het horizontale vlak; keuzelijst [NauwkeurigheidXYvalue]; Nullable: False; Default: None|
|VERTICALE_POSITIE                   |Float(0,10,2)        |PNH; Verticale positie; Nullable: True; Default: None|
|WAARSCHUWINGSTYPE                   |String(255,0,0)      |IMKL; Bovengronds zichtbaar waarschuwingsmechanisme om de positie van een ondergronds element van een nutsvoorzieningennetwerk aan te geven; Nullable: False; Default: None|
|OMSCHRIJVING                        |String(255,0,0)      |PNH; Extra toelichting; Nullable: True; Default: None|
|OPMERKING                           |String(3000,0,0)     |PNH; Opmerking; Nullable: True; Default: None|
|INNETWERK                           |String(255,0,0)      |PNH; FK naar utiliteitsNet_tbl; Nullable: True; Default: None|
|LINK                                |String(255,0,0)      |PNH; FK naar utiliteitsLink_l; Nullable: True; Default: None|
|DIEPTELEGGING                       |String(255,0,0)      |PNH; FK naar diepteTovMaaiveld_p; Nullable: True; Default: None|
|DATALEVERANCIER                     |String(255,0,0)      |PNH; Leverancier van de data; Nullable: True; Default: None|
|CREATED_USER                        |String(255,0,0)      |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)          |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)       |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)          |PNH; Datum van de laatste mutatie; Nullable: True|
|SHAPE                               |Geometry             |PNH; Lijn|
|SHAPE_Length                        |Double(0,0,0)        |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld. ; Nullable: False; Default: None|
|SHAPE_Area                          |Double(0,0,0)        |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld.; Nullable: False; Default: None|


***
