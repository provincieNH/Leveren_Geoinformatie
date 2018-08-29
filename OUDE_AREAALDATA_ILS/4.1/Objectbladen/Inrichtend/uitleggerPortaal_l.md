## AREAALDATA.uitleggerPortaal_l

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __SHAPE:__ Lijn
* __Definitie:__ Uitlegger/Portaal is het lijnvormige element van een uitlegger of portaal. In het geval van een uitlegger bestaat het totaal uit 1 mast (object in paalDraagconstructie_p) en een object in uitleggerPortaal_l. In het geval van een portaal bestaat het geheel uit 2 masten (objecten in paalDraagconstructie_p) en een object in uitleggerPortaal_l. Aan een uitleggePortaal kunnen vervolgens lantaarns of armaturen gekoppeld zijn.



***

|KOLOM                               |TYPE                     |DEFINITIE|
|------                              |----                     |-----    |
|OBJECTID                            |OID(38,0,0)              |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:Yes|
|GLOBALID                            |GlobalID(38,0,0)         |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:Yes|
|AD_ID                               |String(255,0,0)          |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None; Visible:Yes|
|GISIB_ID                            |Integer(0,10,0)          |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|IDENTIFICATIE                       |String(255,0,0)          |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None; Visible:No|
|VERWERKINGSSTATUS                   |String(255,0,0)          |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible:Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)              |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True; Visible:Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)              |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True; Visible:Yes|
|RELATIEVEHOOGTELIGGING              |SmallInteger(0,10,0)     |BGT; Aanduiding voor de relatieve hoogte van het object; Nullable: False; Default: 0; Visible:Yes|
|BEHEERDER                           |String(255,0,0)          |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible:Yes|
|ONDERHOUDER                         |String(255,0,0)          |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible:No|
|EIGENAAR                            |String(255,0,0)          |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible:No|
|TYPESPEC                            |String(255,0,0)          |PNH; Nadere typering van het object, 'Uitlegger' of 'Portaal'; keuzelijst [typeSpecUIP]; Nullable: True; Default: None; Visible:Yes|
|DATUMGARANTIE                       |Date(8,0,0)              |PNH; Datum en jaartal tot wanneer de garantie geldig is; Nullable: True; Default: None; Visible:No|
|DATUMPLAATSING                      |Date(8,0,0)              |PNH; Datum plaatsing; Nullable: True; Visible:No|
|OMSCHRIJVING                        |String(255,0,0)          |PNH; Extra toelichting; Nullable: True; Default: None; Visible:Yes|
|LENGTE                              |Float(0,10,1)            |PNH; Lengte in meters met 1 decimaal; Nullable: True; Default: None; Visible:Yes|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)     |PNH; Levensverwachting; Nullable: True; Visible:No|
|PLANJAAR                            |SmallInteger(0,10,0)     |PNH; Het geplande jaar dat het object vervangen wordt; Nullable: True; Default: None; Visible:No|
|TRAJECT                             |String(255,0,0)          |PNH; FK naar traject_v; Nullable: True; Default: None; Visible:Yes|
|PAAL                                |String(255,0,0)          |PNH; FK naar paalDraagconstructie_p; Nullable: True; Default: None; Visible:Yes|
|PAAL2                               |String(255,0,0)          |PNH; Foreign Key naar tweede paalDraagconstructie_p, alleen in geval van TYPESPEC Portaal; Nullable: True; Default: None; Visible:Yes|
|DATALEVERANCIER                     |String(255,0,0)          |PNH; Leverancier van de data; Nullable: True; Default: None; Visible:No|
|CREATED_USER                        |String(255,0,0)          |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None; Visible:No|
|CREATED_DATE                        |Date(8,0,0)              |PNH; Aanmaakdatum; Nullable: True; Visible:No|
|LAST_EDITED_USER                    |String(50,0,0)           |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None; Visible:No|
|LAST_EDITED_DATE                    |Date(8,0,0)              |PNH; Datum van de laatste mutatie; Nullable: True; Visible:No|
|SHAPE                               |Geometry                 |PNH; Lijn; Visible:Yes|
|SHAPE_Length                        |Double(0,0,0)            |PNH; Lengte in meters, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None; Visible:Yes|


***

