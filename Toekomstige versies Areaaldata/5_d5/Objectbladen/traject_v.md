## AREAALDATA.traject_v

* __Areaaldata model versie:__ 5.0
* __Herkomst Definitie:__ IMBOR/NEN3610
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Vlak
* __Definitie:__ Functioneel; Gebaand gedeelte van het terrein ten behoeve van het verkeer te land, in lengte- en dwarsrichting begrensd door weggrenzen. IMBOR zegt weg (traject)  en water (vaarwegdeeltraject)
* __MappingBGT:__ x
* __Heeft Z-waarden:__ ENABLED
* __Heeft M-waarden:__ DISABLED

***

|__ATTRIBUUT__                             |__ALIAS__                                         |__DATATYPE (length, precision)__       |__DEFINITIE__ (Oorsprong; Superklasse; Attribuuttype; Enumeratie/Referentie; Verwijzende sleutel; Standaard waarde; Definitie)|
|------                                    |------                                            |------                                 |-----    |
|objectid                                  |objectid                                          |OID(0,0)                               |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS.
|globalid                                  |globalid                                          |Globalid(38,0)                         |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken.
|ad_id                                     |ad_id                                             |TEXT(255,0)                            |PNH; AREAALDATA; GUID; ; ; Default: None; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer.
|created_user                              |created_user                                      |TEXT(255,0)                            |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS.
|created_date                              |created_date                                      |DATE(15,0)                             |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS.
|last_edited_user                          |last_edited_user                                  |TEXT(255,0)                            |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS.
|last_edited_date                          |last_edited_date                                  |DATE(15,0)                             |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ; Default: None; Datum van de laatste mutatie, gegenereerd door ArcGIS.
|objectbegintijd                           |objectbegintijd                                   |DATE(9,0)                              |PNH; AREAALDATA; Vrij invoerveld; ; ; Default: None; Datum waarop het object bij de bronhouder is ontstaan.
|objecteindtijd                            |objecteindtijd                                    |DATE(9,0)                              |PNH; AREAALDATA; Vrij invoerveld; ; ; Default: None; Datum waarop het object bij de bronhouder niet meer geldig is.
|verwerkingsstatus                         |verwerkingsstatus                                 |TEXT(255,0)                            |PNH; AREAALDATA; Enumeratie; keuzelijst [Verwerkingsstatus]; ; Default: None; Status van de gegevens.
|dataleverancier                           |dataleverancier                                   |TEXT(255,0)                            |PNH; AREAALDATA; Vrij invoerveld; ; ; Default: None; Leverancier van de data.
|opmerking                                 |opmerking                                         |TEXT(3000,0)                           |PNH; AREAALDATA; Vrij invoerveld; ; ; Default: None; Algemene opmerking voor het object, zoals een omschrijving of toelichting.
|aanlegjaar                                |aanlegjaar                                        |SHORT(5,0)                             |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Het jaar van aanleg. Kan afwijken van bouwjaar (bijvoorbeeld bij herbruik).
|begin_linkeroever                         |beginlinkeroever                                  |FLOAT(6,2)                             |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; hmp - begin linkeroever
|begin_rechteroever                        |beginrechteroever                                 |FLOAT(6,2)                             |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; hmp - begin rechteroever
|beheerder                                 |beheerder                                         |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [BeheerdObjectBeheerder]; ; Default: None; Een publiekrechtelijke instantie of (rechts)persoon die toeziet op de instandhouding van o.a. een object, kunstwerk of waterstaatswerk. De typen beheerder zijn conform de indeling in bronhouders (BGT).
|beperking                                 |beperking                                         |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; In het geval waar een vaarwegtraject niet voldoet aan het streefbeeld moet de geldende beperkingen die gelden voor het hele traject aangegeven worden
|cemt_klasse                               |cemt klasse                                       |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [Cemt klasse]; ; Default: None; CEMTKLASSE object
|eind_linkeroever                          |eind linkeroever                                  |FLOAT(6,2)                             |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; hmp - eind linkeroever
|eind_rechteroever                         |eind rechteroever                                 |FLOAT(6,2)                             |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; hmp - eind rechteroever
|gebiedscontractregio                      |gebiedscontractregio                              |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; Verwijzende sleutel naar [gebiedscontractregio_v]; Default: None; Verwijzende sleutel naar gebiedscontractregio_v. Functionele laag. De provincie heeft haar gebied in 8 gebieden opgesplitst. Amsterdam (gebied 8) is zelfstandig.
|gisib_id                                  |gisib_id                                          |TEXT(255,0)                            |PNH; Areaaldata; Waarde wordt automatisch bepaald; ; ; Default: None; wordt aangemaakt in GISIB
|jaar_van_aanleg                           |jaar van aanleg                                   |SHORT(5,0)                             |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Het jaar van aanleg. Kan afwijken van bouwjaar (bijvoorbeeld bij herbruik).
|lengte_linkeroever                        |lengte linkeroever                                |SHORT(5,0)                             |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; totaal lengte van linkeroever
|lengte_rechteroever                       |lengte rechteroerver                              |SHORT(5,0)                             |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; totaal lengte van rechteroever
|maatgevendschip                           |maatgevendschip                                   |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [Maatgevend schip]; ; Default: None; MAATGEVENDSCHIP waarde
|rangorde                                  |rangorde                                          |SHORT(5,0)                             |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; ToDo
|streefbeeld                               |streefbeeld                                       |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Concrete visuele doelstelling
|theoretisch_eindjaar                      |theoretisch_eindjaar                              |SHORT(5,0)                             |PNH; Areaaldata; Vrij invoerveld; ; ; Default: None; Jaar dat het beheerobject aan het theoretische einde van haar levensduur is.
|traject_deelcode                          |traject deelcode                                  |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [Traject deelcode]; ; Default: None; Uniek code ter identificatie van een traject
|type_traject                              |type traject                                      |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [TypeTraject]; ; Default: None; Omschrijving van de type traject
|voldoet                                   |voldoet                                           |TEXT(3,0)                              |PNH; Areaaldata; Ja/Nee; ; ; Default: None; Voldoet aan de streefbeeld
|wegnummer                                 |wegnummer                                         |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [Trajectnummer]; ; Default: None; traject; N-nummer
|wegtype                                   |wegtype                                           |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [Wegtype]; ; Default: None; De functie van de weg
|wegtype_bestaand                          |wegtype bestaand                                  |TEXT(255,0)                            |PNH; Areaaldata; Enumeratie/Referentie; keuzelijst [Wegtype bestaand]; ; Default: None; Indeling in wegtypen conform de CROW Systematiek Wegbeheer.

***

