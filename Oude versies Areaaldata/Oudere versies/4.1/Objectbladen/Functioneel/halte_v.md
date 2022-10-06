## AREAALDATA.halte_v

*Feature dataset: Functioneel*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH/NDOV
* __Positionele nauwkeurigheid:__ nvt
* __SHAPE:__ Vlak
* __Definitie:__ Het geheel van objecten behorende bij een stopplaats van een autobus. (Integraal Gegevens Model Ideaal Areaal 1.2). STOPPLACE in NDOV terminologie


***

|KOLOM                               |TYPE                |DEFINITIE|
|------                              |----                |-----    |
|OBJECTID                            |OID(38,0,0)         |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:Yes|
|GLOBALID                            |GlobalID(38,0,0)    |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:No|
|AD_ID                               |String(255,0,0)     |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None; Visible:Yes|
|GISIB_ID                            |Integer(0,10,0)     |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|VERWERKINGSSTATUS                   |String(255,0,0)     |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible:Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)         |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True; Visible:Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)         |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True; Visible:Yes|
|BEHEERDER                           |String(255,0,0)     |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible:Yes|
|ONDERHOUDER                         |String(255,0,0)     |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible:No|
|EIGENAAR                            |String(255,0,0)     |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible:No|
|TYPESPEC                            |String(255,0,0)     |PNH; Nadere typering van het object; keuzelijst [typeSpecHLT]; Nullable: True; Default: None; Visible:Yes|
|NAAM                                |String(255,0,0)     |PNH; Naam van de halte; keuzelijst [HALTENAAM]; Nullable: True; Default: None; Visible:Yes|
|WEGNAAM                             |String(255,0,0)     |PNH; Naam vd Weg; Nullable: True; Default: None; Visible:Yes|
|WEGNUMMER                           |String(255,0,0)     |PNH; Nummer vd Weg; Nullable: True; Default: None; Visible:Yes|
|GEMEENTE                            |String(255,0,0)     |PNH; Gemeentenaam; keuzelijst [GEMEENTE]; Nullable: True; Default: None; Visible:No|
|HALTENUMMER                         |String(255,0,0)     |PNH; Identificatienummer van de Halte. Let op: Het landelijk unieke nummer van NDOV staat bij Perron!; Nullable: True; Default: None; Visible:Yes|
|PROJECT                             |String(1,0,0)       |PNH; Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: O; Visible:No|
|SUBSIDIEPROJECT                     |String(255,0,0)     |PNH; Naam van het subsidieproject voor aanleg; Nullable: True; Default: None; Visible:No|
|HALTEKOM                            |String(1,0,0)       |PNH; Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend]; Nullable: False; Default: O; Visible:No|
|ONDERHOUDSOVEREENKOMST              |String(255,0,0)     |PNH; Verwijzing naar de Onderhoud overeenkomst (documentnr, locatie e.d.); Nullable: True; Default: None; Visible:No|
|FOTO                                |String(255,0,0)     |PNH; Verwijzing naar naam/locatie van een foto vd Halte; Nullable: True; Default: None; Visible:No|
|ELEKTROTECHN_TEKENING               |String(255,0,0)     |PNH; Verwijzing naar naam/locatie van een elektrotechnische tekening vd Halte; Nullable: True; Default: None; Visible:No|
|WOONPLAATS                          |String(255,0,0)     |PNH; Gemeentenaam; keuzelijst [GEMEENTE]; Nullable: True; Default: None; Visible:No|
|STATUS_HALTE                        |String(255,0,0)     |PNH; Status van de halte: is deze in gebruik of niet; Nullable: True; Default: None; Visible:No|
|DATALEVERANCIER                     |String(255,0,0)     |PNH; Leverancier van de data; Nullable: True; Default: None; Visible:No|
|CREATED_USER                        |String(255,0,0)     |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None; Visible:No|
|CREATED_DATE                        |Date(8,0,0)         |PNH; Aanmaakdatum; Nullable: True; Visible:No|
|LAST_EDITED_USER                    |String(50,0,0)      |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None; Visible:No|
|LAST_EDITED_DATE                    |Date(8,0,0)         |PNH; Datum van de laatste mutatie; Nullable: True; Visible:No|
|SHAPE                               |Geometry            |PNH; Vlak; Visible:Yes|
|SHAPE_Length                        |Double(0,0,0)       |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None; Visible:Yes|
|SHAPE_Area                          |Double(0,0,0)       |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None; Visible:Yes|
|CONCESSIEVERLENER                   |String(255,0,0)     |PNH; FK naar concessieverlener_tbl; voor de plaatsing; Nullable: True; Default: None|
|TRAJECT                             |String(255,0,0)     |PNH; FK naar traject_v; Nullable: True; Default: None; Visible:Yes|

***
