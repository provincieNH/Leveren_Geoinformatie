## AREAALDATA.electriciteitskabel_l

$ Feature dataset: Inrichtend


* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL (2015)
* __Positionele nauwkeurigheid:__ 7,5 cm
* __SHAPE:__ Lijn
* __Definitie:__ Een aansluiting of reeks aansluitingen van een nutsvoorzieningennet voor het overbrengen van elektriciteit van de ene locatie naar een andere. (Bron: INSPIRE)

***

|KOLOM                               |TYPE                |DEFINITIE|
|------                              |----                |-----    |
|LENGTE                              |Float(0,10,2)       |Lengte van de kabel (m, 2 decimalen) - Nullable: True|
|AANTALADERS                         |String(255,0,0)     |Codering t.b.v. het aantal aders dat de kabel bevat (bijvoorbeeld 4x1,5 of 2x2,5) - Nullable: True Default: None|
|AFWIJKENDEDIEPTE                    |String(255,0,0)     |Afwijking van de gangbare dieptelegging voor een leiding van dit thema. (Eenheid cm? TODO) - Nullable: True Default: None|
|bovengrondsZichtbaar                |String(1,0,0)       |Aangegeven wordt of de electriciteitskabel bovengronds vanaf het maaiveld zichtbaar is, keuzelijst [jaNee] - Nullable: True Default: None|
|CODE                                |String(25,0,0)      |TODO - Nullable: True Default: None|
|CODEKABEL                           |String(255,0,0)     |Codering om het type kabel nader te onderscheiden. Zo wordt binnen VRI ‘VO-YMVKAS’ of ‘UXL’ gebruikt - Nullable: True Default: None|
|OMSCHRIJVING                        |String(255,0,0)     |Extra toelichting - Nullable: True Default: None|
|NAAR                                |String(255,0,0)     |Bestemming kabel TODO - Nullable: True Default: None|
|OPMERKING                           |String(3000,0,0)    |Opmerking - Nullable: True Default: None|
|PRODUCT                             |String(255,0,0)     |Het product dat door de leiding vervoerd wordt of kan worden vervoerd - Nullable: True Default: None|
|VAN                                 |String(255,0,0)     |Startlocatie kabel TODO - Nullable: True Default: None|
|MATERIAALTYPE                       |String(255,0,0)     |Type materiaal, keuzelijst [MATERIAALTYPE] - Nullable: True Default: None|
|SHAPE                               |Geometry            |Lijn|
|SHAPE_Length                        |Double(0,0,0)       |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|IDENTIFICATIE                       |String(255,0,0)      |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecKAB] - Nullable: True Default: None|
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
|HUIDIGESTATUS                       |String(50,0,0)     |Huidige status, keuzelijst [ConditionOfFacilityValue] - Nullable: False Default: None|
|INNETWERK                           |String(255,0,0)    |FK naar utiliteitsNet_tbl - Nullable: True Default: None|
|LINK                                |String(255,0,0)    |FK naar utiliteitsLink_l - Nullable: True Default: None|
|GEONAUWKEURIGHEIDXY                 |String(50,0,0)     |Nauwkeurigheid van de liggingsgegevens in het horizontale vlak, keuzelijst [NauwkeurigheidXYvalue] - Nullable: False Default: None|
|BEDRIJFSSPANNING                    |Integer(0,10,0)    |Bedrijfsvoltage in V, afkomstig uit operatingVoltage - Nullable: False|
|NOMINALESPANNING                    |Integer(0,10,0)    |Nominale spanning in V, afkomstig uit nominalVoltage - Nullable: False|
|TOELICHTING                         |String(255,0,0)    |Extra toelichting - Nullable: True Default: None|
|DIEPTELEGGING                       |String(255,0,0)    |FK naar diepteTovMaaiveld_p - Nullable: False Default: None|
|VERTICALE_POSITIE                   |Float(0,10,2)      |Verticale positie - Nullable: True Default: None|
|WAARSCHUWINGSTYPE                   |String(255,0,0)    |ToDo Waarschuwingstype - Nullable: True Default: None|







***