## AREAALDATA.buis_l

$ Feature dataset: Inrichtend

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL
* __Positionele nauwkeurigheid:__ 7,5 cm
* __SHAPE:__ Lijn
* __Definitie:__ Holle leiding voor het doorstromen van gassen, vloeistoffen of capsules, bestemd om hetzij gas,
een vloeistof of capsules te transporteren, hetzij een vloeistof als intermediair te gebruiken voor het transport van
warmte of een opgeloste of verpulverde stof. NB. Bij PNH eigenlijk alleen gebruikt voor riolering.

***

|KOLOM                               |TYPE              |DEFINITIE|
|------                              |----              |-----    |
|THEMAKAART                          |String(255,0,0)     |Themakaart, keuzelijst [THEMAKAART] - Nullable: True Default: None|
|AANTALBUIZEN                        |SmallInteger(0,10,0)|Aantal buizen gerepresenteerd door de SHAPE van dit object [] - Nullable: True Default: None|
|AFWIJKENDEDIEPTE                    |String(255,0,0)     |Afwijking van de gangbare dieptelegging voor een leiding van dit thema [] - Nullable: True Default: None|
|bovengrondsZichtbaar                |String(1,0,0)       |Aangegeven wordt of de buis bovengronds vanaf het maaiveld zichtbaar is, keuzelijst [jaNee] - Nullable: True Default: None|
|OMSCHRIJVING                        |String(255,0,0)     |Extra toelichting [] - Nullable: True Default: None|
|DATUMPLAATSING                      |Date(8,0,0)         |Datum aanleg - Nullable: True Default: None|
|DIAMETERCM                          |SmallInteger(0,10,0)|Diameter van de buis in cm [] - Nullable: True Default: None|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)|Levensvervachting in jaar [] - Nullable: True Default: None|
|OPMERKING                           |String(3000,0,0)    |extra opmerking [] - Nullable: True Default: None|
|PLANJAAR                            |SmallInteger(0,10,0)|planjaar vervanging [] - Nullable: True Default: None|
|PRODUCT                             |String(255,0,0)     |Het product dat door de leiding vervoerd wordt of kan worden vervoerd [] - Nullable: True Default: None|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0)|Restlevensduur [] - Nullable: True Default: None|
|VERHOOGDRISICO                      |String(255,0,0)     |Vermelding dat het gaat om een net met gevaarlijke inhoud [] - Nullable: True Default: None|
|VOORZORGMAATREGEL                   |String(255,0,0)     |Vermelding of er voorzorgsmaatregelen getroffen dienen te worden [] - Nullable: True Default: None|
|MATERIAALTYPE                       |String(255,0,0)     |Type materiaal, keuzelijst [MATERIAALTYPE] [] - Nullable: True Default: None|
|SHAPE                               |Geometry            |Lijn|
|SHAPE_Length                        |Double(0,0,0)       |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|TRAJECT                             |String(255,0,0)     |FK naar traject_v - Nullable: True Default: None|
|IDENTIFICATIE                       |String(255,0,0)      |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecBUI] - Nullable: True Default: None|
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


***
