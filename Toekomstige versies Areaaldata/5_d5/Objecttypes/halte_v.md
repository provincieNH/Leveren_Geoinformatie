ï»¿## AREAALDATA.halte_v

* __Areaaldata model versie:__ 5.0
* __Herkomst Definitie:__ IMBOR/NEN3610
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Vlak
* __Definitie:__ Functioneel; Het geheel van objecten behorende bij een stopplaats van een autobus. (Integraal Gegevens Model Ideaal Areaal 1.2). STOPPLACE in NDOV terminologie. Ofwel eenvoudige stopplaats voor voertuigen van het openbaar vervoer.
* __MappingBGT:__ x
* __Heeft Z-waarden:__ ENABLED
* __Heeft M-waarden:__ DISABLED

***

|__ATTRIBUUT__                             |__ALIAS__                                             |__DATATYPE (length, precision)__       |__DEFINITIE__ (Oorsprong; Superklasse; Attribuuttype; Enumeratie/Referentie; Verwijzende sleutel; Standaard waarde; Definitie)|
|------                                    |------                                                |------                                 |-----    |
|objectid                                  |objectid                                              |OID(0,0)                               |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ;Default: None; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS.
|globalid                                  |globalid                                              |Globalid(38,0)                         |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ;Default: None; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken.
|ad_id                                     |ad_id                                                 |TEXT(255,0)                            |PNH; AREAALDATA; GUID; ; ;Default: None; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer.
|created_user                              |created_user                                          |TEXT(255,0)                            |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ;Default: None; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS.
|created_date                              |created_date                                          |DATE(15,0)                             |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ;Default: None; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS.
|last_edited_user                          |last_edited_user                                      |TEXT(255,0)                            |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ;Default: None; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS.
|last_edited_date                          |last_edited_date                                      |DATE(15,0)                             |PNH; AREAALDATA; Waarde wordt automatisch bepaald; ; ;Default: None; Datum van de laatste mutatie, gegenereerd door ArcGIS.
|objectbegintijd                           |objectbegintijd                                       |DATE(9,0)                              |PNH; AREAALDATA; Vrij invoerveld; ; ;Default: None; Datum waarop het object bij de bronhouder is ontstaan.
|objecteindtijd                            |objecteindtijd                                        |DATE(9,0)                              |PNH; AREAALDATA; Vrij invoerveld; ; ;Default: None; Datum waarop het object bij de bronhouder niet meer geldig is.
|verwerkingsstatus                         |verwerkingsstatus                                     |TEXT(255,0)                            |PNH; AREAALDATA; Enumeratie; keuzelijst [verwerkingsstatus]; ;Default: None; Status van de gegevens.
|dataleverancier                           |dataleverancier                                       |TEXT(255,0)                            |PNH; AREAALDATA; Vrij invoerveld; ; ;Default: None; Leverancier van de data.
|opmerking                                 |opmerking                                             |TEXT(3000,0)                           |PNH; AREAALDATA; Vrij invoerveld; ; ;Default: None; Algemene opmerking voor het object, zoals een omschrijving of toelichting.
|bebouwde_kom                              |bebouwde kom                                          |TEXT(255,0)                            |PNH; Gebiedsindeling; Enumeratie/Referentie; keuzelijst [BebouwdeKOMgrens]; ; Default: None; Aanduiding van de ligging van het beheerobject binnen of buiten de bebouwde kom.
|beheerafspraak                            |beheerafspraak                                        |TEXT(255,0)                            |IMBOR; Beheerd object; Vrij invoerveld; ; ; Default: None; Attribuut voor het vermelden van aanvullende afspraken over het beheer van een object of voor het vermelden van specificaties van de beheersituatie van een object.
|beheerder                                 |beheerder                                             |TEXT(255,0)                            |PNH; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerObjectBeheerder]; ; Default: None; Een publiekrechtelijke instantie of (rechts)persoon die toeziet op de instandhouding van o.a. een object, kunstwerk of waterstaatswerk. De typen beheerder zijn conform de indeling in bronhouders (BGT).
|beheerder_detail                          |beheerder gedetailleerd                               |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerObjectBeheerderDetail]; ; Default: None; Nadere aanduiding van de beheerder van het beheerobject.
|beheergebied                              |beheergebied                                          |TEXT(255,0)                            |IMBOR; Gebiedsindeling; Vrij invoerveld; ; Verwijzende sleutel naar [gebiedscontractregio_v]; Default: None; Verwijzende sleutel naar gebiedscontractregio_v. De provincie heeft haar gebied in 8 gebieden opgesplitst. Amsterdam (gebied 8) is zelfstandig. Er zijn geen beheerobjecten in Areaaldata.
|beheerstatus                              |beheerstatus                                          |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerObjectStatus]; ; Default: None; Status van het beheerobject
|bestuurlijke_regio                        |bestuurelijke regio                                   |TEXT(255,0)                            |PNH; Gebiedsindeling; Vrij invoerveld; ; Verwijzende sleutel naar [bestuurlijkeregio_v]; Default: None; Verwijzende sleutel naar bestuurlijkeregio_v.De provincie heeft een aantal taken binnen de Noord-Hollandse gemeenten. Zo heeft de commissaris van de Koning (CvdK) een belangrijke rol bij de benoeming van burgemeesters. Ook houdt de provincie toezicht op de financiÃ«n van gemeenten.
|concessieverlener                         |concessieverlener                                     |TEXT(255,0)                            |PNH; Halte; Vrij invoerveld; ; Verwijzende sleutel naar [Concessieverlener]; Default: None; Verwijzende sleutel naar concessieverlener_tbl
|eigenaar                                  |eigenaar                                              |TEXT(255,0)                            |PNH; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerObjectEigenaar]; ; Default: None; (Rechts)persoon die het meest omvattend recht op een zaak heeft. De typen eigenaren zijn conform de indeling in bronhouders (BGT).
|eigenaar_detail                           |eigenaar gedetailleerd                                |TEXT(255,0)                            |IMBOR; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerObjectEigenaarDetail]; ; Default: None; Nadere aanduiding van de eigenaar van het beheerobject.
|elektrotechn_tekening                     |elektrotechn_tekening                                 |TEXT(255,0)                            |PNH; Halte; Vrij invoerveld; ; ; Default: None; De locatie aanduiding waar de technische tekening te vnden zijn
|foto                                      |foto                                                  |TEXT(255,0)                            |PNH; Halte; Vrij invoerveld; ; ; Default: None; Interne locatie van een foto
|gebiedstype                               |gebiedstype                                           |TEXT(255,0)                            |IMBOR; Gebiedsindeling; Waarde wordt automatisch bepaald; ; ; Default: None; Aanduiding van het gebiedstype waarbinnen het beheerobject ligt. Conform de indeling zoals toegepast bij de CROW Benchmark Beheerprestaties.
|gedeeld_beheer                            |gedeeld beheer                                        |TEXT(3,0)                              |IMBOR; Beheerd object; Ja/Nee; ; ; Default: None; Aanduiding voor het registreren van gedeeld beheer van het object.
|gemeentenaam                              |gemeentenaam                                          |TEXT(255,0)                            |IMBOR; Gebiedsindeling; Vrij invoerveld; ; Verwijzende sleutel naar [gemeente_v]; Default: None; Verwijzende sleutel naar gemeente_v. Naam van de gemeente waarbinnen het beheerobject ligt.
|gisib_id                                  |gisib_id                                              |TEXT(255,0)                            |PNH; Areaaldata; Waarde wordt automatisch bepaald; ; ; Default: None; wordt aangemaakt in GISIB
|haltekom                                  |haltekom                                              |TEXT(3,0)                              |PNH; Halte; Ja/Nee; ; ; Default: None; ligging van de halte
|haltenaam                                 |haltenaam                                             |TEXT(255,0)                            |PNH; Halte; Vrij invoerveld; ; ; Default: None; Unieke naam van de halte
|haltenummer                               |haltenummer                                           |TEXT(255,0)                            |PNH; Halte; Vrij invoerveld; ; ; Default: None; Unieke nummer van de halte
|halteplaats                               |halteplaats                                           |TEXT(255,0)                            |IMBOR; Halte; Enumeratie/Referentie; keuzelijst [Halteplaats]; ; Default: None; Waar bevindt de halte; langs de weg of vaarweg
|omtrek                                    |omtrek                                                |DOUBLE(10,3)                           |PNH; Geo-object; Vrij invoerveld; ; ; Default: None; Omtrek in meters, dit wordt automatisch gevuld uit SHAPE_Length
|onderhouder                               |onderhoudsplichtige                                   |TEXT(255,0)                            |PNH; Beheerd object; Enumeratie/Referentie; keuzelijst [BeheerObjectOnderhouder]; ; Default: None; Organisatie die verantwoordelijk is voor het onderhoud van het beheerobject.
|onderhoudsovereenkomst                    |onderhoudsovereenkomst                                |TEXT(255,0)                            |PNH; Halte; Vrij invoerveld; ; ; Default: None; de omschrijving van de onderhoudsovereenkomst
|openbare_ruimtenaam                       |openbare ruimtenaam                                   |TEXT(255,0)                            |IMBOR; Gebiedsindeling; Vrij invoerveld; ; ; Default: None; Aanduiding van de openbare ruimte, zoals gedefinieerd in IMGeo of in de BAG, waarbinnen het beheerobject ligt. Overname uit IMGeo-bestand met grenzen openbare ruimtes of uit de Basisregistraties voor Adressen en Gebouwen (zonder begrenzing).
|oppervlakte                               |oppervlakte                                           |DOUBLE(10,3)                           |PNH; Geo-object; Vrij invoerveld; ; ; Default: None; Oppervlakte in m2, dit wordt automatisch gevuld uit SHAPE_Area
|project                                   |project                                               |TEXT(3,0)                              |PNH; Halte; Ja/Nee; ; ; Default: None; in verband met een project
|subsidieproject                           |subsidieproject                                       |TEXT(255,0)                            |PNH; Halte; Vrij invoerveld; ; ; Default: None; de subside omschrijving van het project
|traject                                   |traject                                               |TEXT(255,0)                            |PNH; Gebiedsindeling; Vrij invoerveld; ; Verwijzende sleutel naar [traject_v]; Default: None; Verwijzende sleutel naar traject_v; AD_ID foreign key
|traject_nummer                            |traject nummer                                        |TEXT(255,0)                            |PNH; Gebiedsindeling; Enumeratie/Referentie; keuzelijst [Trajectnummer]; ; Default: None; traject; N-nummer
|tweede_beheerder                          |tweede beheerder                                      |TEXT(255,0)                            |IMBOR; Beheerd object; Vrij invoerveld; ; ; Default: None; Registratie van de tweede beheerder in geval van gedeeld beheer.
|tweede_eigenaar                           |tweede eigenaar                                       |TEXT(255,0)                            |IMBOR; Beheerd object; Vrij invoerveld; ; ; Default: None; Registratie van de tweede eigenaar in geval van gedeeld eigenaarschap.
|veiligheidsregio                          |veikigheidsregio                                      |TEXT(255,0)                            |IMBOR; Gebiedsindeling; Vrij invoerveld; ; Verwijzende sleutel naar [veiligheidsregio_v]; Default: None; Verwijzende sleutel naar veiligheidsregio_v. De provincie is betrokken bij het beheersen van rampen en crises. Noord-Holland is verdeeld in 5 veiligheidsregioâ€™s
|waterschapnaam                            |waterschapnaam                                        |TEXT(255,0)                            |IMBOR; Gebiedsindeling; Vrij invoerveld; ; Verwijzende sleutel naar [waterschappen_v]; Default: None; Verwijzende sleutel naar waterschappen_v. Aanduiding van het waterschap, waarbinnen het beheerobject ligt. Overname uit IMGeo-bestand met waterschapsgrenzen.
|wegen_beheergrens                         |wegen beheergrens                                     |TEXT(255,0)                            |PNH; Gebiedsindeling; Vrij invoerveld; ; Verwijzende sleutel naar [beheergrenzen_v]; Default: None; Verwijzende sleutel naar beheergrenzen_v
|wegnaam                                   |wegnaam                                               |TEXT(255,0)                            |PNH; Halte; Vrij invoerveld; ; ; Default: None; de lokale naam van de weg
|wegvak                                    |wegvak                                                |TEXT(255,0)                            |PNH; Gebiedsindeling; Vrij invoerveld; ; Verwijzende sleutel naar [wegvak_v]; Default: None; Verwijzende sleutel naar wegvak_v; Overname van het wegvaknummer uit vorige indeling; uniek AD_ID
|wegvaknummer                              |wegvaknummer                                          |TEXT(255,0)                            |PNH; Gebiedsindeling; Vrij invoerveld; ; ; Default: None; de nummer van de wegvak
|wgv_afstandtot                            |wgv afstandtot                                        |TEXT(255,0)                            |PNH; Gebiedsindeling; Vrij invoerveld; ; ; Default: None; Aanduiding bij welk wegindexeringspaal (hectometerpaal) het inspectievak eindigt
|wgv_afstandvan                            |wgv afstandvan                                        |TEXT(255,0)                            |PNH; Gebiedsindeling; Vrij invoerveld; ; ; Default: None; Aanduiding bij welk wegindexeringspaal (hectometerpaal) het inspectievak begint
|zitmeubel                                 |zitmeubel                                             |TEXT(255,0)                            |PNH; Halte; Enumeratie/Referentie; keuzelijst [Zitmeubel]; ; Default: None; Type aanwezig meubel
|zonnepaneel                               |zonnepaneel                                           |TEXT(3,0)                              |PNH; Halte; Ja/Nee; ; ; Default: None; in verband met een zonnepaneel

***
