## AREAALDATA.wegvak_v

* __Areaaldata model versie:__ 5.0
* __Herkomst Definitie:__ IMBOR/NEN3610
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Vlak
* __Definitie:__ Administratief afgebakend gedeelte van een weg waarbinnen de inspectiemetingen uitgevoerd worden. Een wegvak is doorgaands 100 meter en loopt in de meeste gevallen gelijk aan de wegindexering (hectometerpalen). In de breedte dient een wegvak alle wegdelen en ondersteunende wegdelen te omvatten.
* __MappingBGT:__ x
* __Heeft Z-waarden:__ ENABLED
* __Heeft M-waarden:__ DISABLED

***

|__ATTRIBUUT__                |__ALIAS__                    |__DATATYPE (length, precision)__       |__DEFINITIE__ (Oorsprong; Superklasse; Attribuuttype; Enumeratie/Referentie; Definitie)|
|------                       |------                       |------                                 |-----    |
|objectid                     |objectid                     |OID(0,0)                               |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; Default: None; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS.
|globalid                     |globalid                     |Globalid(38,0)                         |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; Default: None; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken.
|ad_id                        |ad_id                        |TEXT(255,0)                            |PNH; AREAALDATA; GUID; ; Default: None; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer.
|created_user                 |created_user                 |TEXT(255,0)                            |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; Default: None; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS.
|created_date                 |created_date                 |DATE(15,0)                             |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; Default: None; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS.
|last_edited_user             |last_edited_user             |TEXT(255,0)                            |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; Default: None; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS.
|last_edited_date             |last_edited_date             |DATE(15,0)                             |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; Default: None; Datum van de laatste mutatie, gegenereerd door ArcGIS.
|objectbegintijd              |objectbegintijd              |DATE(9,0)                              |PNH; AREAALDATA; Vrij invoerveld; ; Default: None; Datum waarop het object bij de bronhouder is ontstaan.
|objecteindtijd               |objecteindtijd               |DATE(9,0)                              |PNH; AREAALDATA; Vrij invoerveld; ; Default: None; Datum waarop het object bij de bronhouder niet meer geldig is.
|verwerkingsstatus            |verwerkingsstatus            |TEXT(255,0)                            |PNH; AREAALDATA; Enumeratie; keuzelijst [verwerkingsstatus]; Default: None; Status van de gegevens.
|dataleverancier              |dataleverancier              |TEXT(255,0)                            |PNH; AREAALDATA; Vrij invoerveld; ; Default: None; Leverancier van de data.
|opmerking                    |opmerking                    |TEXT(3000,0)                           |PNH; AREAALDATA; Vrij invoerveld; ; Default: None; Algemene opmerking voor het object, zoals een omschrijving of toelichting.
|beheerder_ad4                |beheerder ad4                |TEXT(255,0)                            |IMBOR; Beheerobject; Enueratie/referentie; keuzelijst [BeheerdObjectBeheerderAD4]; Default: None; Een publiekrechtelijke instantie of (rechts)persoon die toeziet op de instandhouding van o.a. een object, kunstwerk of waterstaatswerk. De typen beheerder zijn conform de indeling in bronhouders (BGT).
|beheergebied                 |beheergebied                 |TEXT(255,0)                            |IMBOR; Gebiedsindeling; Enueratie/referentie; keuzelijst [Beheergebied]; Default: None; De provincie heeft haar gebied in 8 gebieden opgesplitst. Amsterdam (gebied 8) is zelfstandig. Er zijn geen beheerobjecten in Areaaldata.
|bestuurlijke_regio           |bestuurelijke regio          |TEXT(255,0)                            |PNH; Gebiedsindeling; Enueratie/referentie; keuzelijst [Bestuurlijke regio]; Default: None; De provincie heeft een aantal taken binnen de Noord-Hollandse gemeenten. Zo heeft de commissaris van de Koning (CvdK) een belangrijke rol bij de benoeming van burgemeesters. Ook houdt de provincie toezicht op de financiën van gemeenten.
|eigenaar_ad4                 |eigenaar ad4                 |TEXT(255,0)                            |IMBOR; Beheerobject; Enueratie/referentie; keuzelijst [BeheerdObjectEigenaarAD4]; Default: None; (Rechts)persoon die het meest omvattend recht op een zaak heeft. De typen eigenaren zijn conform de indeling in bronhouders (BGT).
|gebiedstype                  |gebiedstype                  |TEXT(255,0)                            |IMBOR; Gebiedsindeling; Waarde wordt automatisch bepaald; ; Default: None; Aanduiding van het gebiedstype waarbinnen het beheerobject ligt. Conform de indeling zoals toegepast bij de CROW Benchmark Beheerprestaties.
|gisib_id                     |gisib_id                     |TEXT(255,0)                            |PNH; Areaaldata; Vrij invoerveld; ; Default: None; wordt aangemaakt in GISIB
|omtrek                       |omtrek                       |DOUBLE(10,3)                           |PNH; Geo-object; Vrij invoerveld; ; Default: None; Omtrek in meters, dit wordt automatisch gevuld uit SHAPE_Length
|oppervlakte                  |oppervlakte                  |DOUBLE(10,3)                           |PNH; Geo-object; Vrij invoerveld; ; Default: None; Oppervlakte in m2, dit wordt automatisch gevuld uit SHAPE_Area
|shape                        |shape                        |DOUBLE(10,3)                           |PNH; Geo-object; Vrij invoerveld; ; Default: None; vlak oppervlakte
|shape_area                   |shape area                   |DOUBLE(10,3)                           |PNH; Geo-object; Vrij invoerveld; ; Default: None; Oppervlakte in m2, dit wordt berekend in bepaalde applicaties
|shape_length                 |shape length                 |DOUBLE(10,3)                           |PNH; Geo-object; Vrij invoerveld; ; Default: None; Omtrek in meters, dit wordt berekend in bepaalde applicaties
|traject                      |traject                      |TEXT(255,0)                            |PNH; Gebiedsindeling; Enueratie/referentie; keuzelijst [Traject]; Default: None; traject; AD_ID foreign key
|traject_nummer               |traject nummer               |TEXT(255,0)                            |PNH; Gebiedsindeling; Enueratie/referentie; keuzelijst [Trajectnummer]; Default: None; traject; N-nummer
|typeondergrond               |typeondergrond               |TEXT(255,0)                            |PNH; Wegvak; Enueratie/referentie; keuzelijst [Typeondergrond]; Default: None; type grond onder de wegvak
|veiligheidsregio             |veikigheidsregio             |TEXT(255,0)                            |IMBOR; Gebiedsindeling; Enueratie/referentie; keuzelijst [Veiligheidsregio]; Default: None; De provincie is betrokken bij het beheersen van rampen en crises. Noord-Holland is verdeeld in 5 veiligheidsregio’s
|wegvaknummer                 |wegvaknummer                 |SHORT(5,0)                             |PNH; Wegvak; Vrij invoerveld; ; Default: None; de nummer van de wegvak
|wgv_afstandtot               |wgv_afstandtot               |FLOAT(6,2)                             |PNH; Wegvak; Vrij invoerveld; ; Default: None; Aanduiding bij welk wwegindexeringspaal (hectometerpaal) het inspectievak eindigt
|wgv_afstandtvan              |wgv_afstandtvan              |FLOAT(6,2)                             |PNH; Wegvak; Vrij invoerveld; ; Default: None; Aanduiding bij welk wwegindexeringspaal (hectometerpaal) het inspectievak begint

***

