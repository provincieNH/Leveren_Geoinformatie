## AREAALDATA.lantaarn_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __SHAPE:__ Punt
* __Definitie:__  De lichten van een verkeersregelinstallatie samen met het achtergrondschild en de zonnekappen


***

|KOLOM                               |TYPE (length, precision, scale)                   |DEFINITIE (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                   |-----    |
|OBJECTID                            |OID(38,0,0)            |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)       |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |String(255,0,0)        |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |Integer(0,10,0)        |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |String(255,0,0)        |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)            |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)            |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|BEHEERDER                           |String(255,0,0)        |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |String(255,0,0)        |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |String(255,0,0)        |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |String(255,0,0)        |PNH; Nadere typering van het object; keuzelijst [typeSpecLAN]; Nullable: True; Default: None; Visible: Yes|
|MONTAGEWIJZE                        |String(255,0,0)        |PNH; Montagewijze; keuzelijst [MONTAGEWIJZE]; Nullable: True; Default: None; Visible: Yes|
|HECTOMETER                          |String(255,0,0)        |PNH; Hectometrering; ; Nullable: True; Default: None; Visible: Yes|
|ACHTERGRONDSCHILD                   |String(255,0,0)        |PNH; Achtergrond schild aanwezig; ; Nullable: True; Default: None; Visible: No|
|DATUMPLAATSING                      |Date(8,0,0)            |PNH; Datum Plaatsing; ; Nullable: True; Default: None; Visible: No|
|OMSCHRIJVING                        |String(255,0,0)        |PNH; Extra toelichting; ; Nullable: True; Default: None; Visible: Yes|
|LANTAARNNUMMER                      |String(255,0,0)        |PNH; Lantaarn Nummer; ; Nullable: True; Default: None; Visible: Yes|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)   |PNH; Levensverwachting; ; Nullable: True; Default: None; Visible: No|
|PLANJAAR                            |SmallInteger(0,10,0)   |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|FABRIKANTTYPECODE                   |String(255,0,0)        |PNH; Fabrikanttypecode; keuzelijst [FABRIKANT_TYPECODE]; Nullable: True; Default: None; Visible: Yes|
|PAAL                                |String(255,0,0)        |PNH; FK naar paalDraagconstructie_p; ; Nullable: True; Default: None; Visible: No|
|UITLEGGERPORTAAL                    |String(255,0,0)        |PNH; FK naar uitleggerPortaal_l; ; Nullable: True; Default: None; Visible: No|
|TRAJECT                             |String(255,0,0)        |PNH; FK naar traject_v; keuzelijst [TRAJECT_NAAM] ; Nullable: True; Default: None; Visible: Yes|
|DATALEVERANCIER                     |String(255,0,0)        |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |String(255,0,0)        |PNH; Naam van gebruiker die de rij heeft aangemaakt; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)            |PNH; Aanmaakdatum; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)         |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)            |PNH; Datum van de laatste mutatie; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry               |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|


***




