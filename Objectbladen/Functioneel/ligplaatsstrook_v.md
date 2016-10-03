## AREAALDATA.ligplaatsstrook_v

$ Feature dataset: Functioneel


* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt
* __SHAPE:__ Vlak
* __Definitie:__ Een Ligplaatsstrook is een gebied waar ligplaatsen toegestaan zijn

***

|KOLOM                               |TYPE              |DEFINITIE|
|------                              |----              |-----    |
|ZIJDE                               |String(255,0,0)     |Zijde, keuzelijst [ZIJDE] - Nullable: True Default: None|
|CULTUURHISTORISCHE                  |String(255,0,0)     |Cultuur Historische Waarde - Nullable: True Default: None|
|GEMIDDELDEBREEDTE                   |Float(0,25,10)      |Gemiddelde Breedte - Nullable: True|
|HMBEGIN                             |Float(0,25,10)      |Begin Hectometrering van Ligplaatsstrook - Nullable: True|
|HMEIND                              |Float(0,25,10)      |Eind Hectometrering van Ligplaatsstrook - Nullable: True|
|LENGTE                              |SmallInteger(0,10,0)|Lengte Ligplaatsstrook - Nullable: True|
|LIGPLAATSSTROOKLIN                  |Float(0,25,10)      |Ligplaatsstrook Linker Oever - Nullable: True|
|LIGPLAATSSTROOKREC                  |Float(0,25,10)      |Ligplaatsstrook Rechter Oever - Nullable: True|
|OPMERKING                           |String(3000,0,0)    |Extra toelichting - Nullable: True Default: None|
|RESTRUIMTE                          |Float(0,25,10)      |Beschikbare ruimte in nautisch profiel - Nullable: True|
|SHAPE                               |Geometry            |Vlak|
|SHAPE_Length                        |Double(0,0,0)       |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Area                          |Double(0,0,0)       |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|ECOLOGISCHEHOOFDST                  |String(255,0,0)     |FK naar ecoHoofdstructuur_v - Nullable: True Default: None|
|ECOLOGISCHEVERBIND                  |String(255,0,0)     |FK naar ecoVerbZone_v - Nullable: True Default: None|
|VAARWEGDEELTRAJECT                  |String(255,0,0)     |FK naar vaarwegdeeltraject_v - Nullable: True Default: None|
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
