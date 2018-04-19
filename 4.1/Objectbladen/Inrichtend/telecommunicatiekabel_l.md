## AREAALDATA.telecommunicatiekabel_l

$ Feature dataset: Inrichtend


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL (2015)
* __Positionele nauwkeurigheid:__ 7,5 cm
* __SHAPE:__ Lijn
* __Definitie:__ Een aansluiting of reeks aansluitingen van een nutsvoorzieningennet voor het overbrengen van signaalinformatie van de ene locatie naar een andere. (Bron: INSPIRE)


***

|KOLOM                               |TYPE                 |DEFINITIE|
|------                              |----                 |-----    |
|OBJECTID                            |OID(38,0,0)          |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None|
|GLOBALID                            |GlobalID(38,0,0)     |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None|
|AD_ID                               |String(255,0,0)      |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None|
|GISIB_ID                            |Integer(0,10,0)      |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None
|IDENTIFICATIE                       |String(255,0,0)      |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)      |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|OBJECTBEGINTIJD                     |Date(8,0,0)          |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)          |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|BEHEERDER                           |String(255,0,0)      |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None|
|ONDERHOUDER                         |String(255,0,0)      |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None|
|EIGENAAR                            |String(255,0,0)      |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None|
|TYPESPEC                            |String (10,0,0)      |PNH; Nadere typering van het object: 'Data'; keuzelijst [typeSpecKAB]; Nullable: True; Default: None|
|AANTALADERS                         |String(255,0,0)      |PNH; Codering t.b.v. het aantal aders dat de kabel bevat (bijvoorbeeld 4x1,5 of 2x2,5); Nullable: True; Default: None|
|AFWIJKENDEDIEPTE                    |String(255,0,0)      |PNH; Afwijking van de gangbare dieptelegging voor een leiding van dit thema in centimeter; Nullable: True; Default: None|
|bovengrondsZichtbaar                |String(1,0,0)        |IMKL; Aangegeven wordt of de telecommunicatiekabel bovengronds vanaf het maaiveld zichtbaar is; keuzelijst [jaNee]; Nullable: True; Default: None|
|CODEKABEL                           |String(50,0,0)       |PNH; Codering om het type kabel nader te onderscheiden. Hoofdlettergebruik is belangrijk. 'zh' en 'mb' specificatie volgt de code en dan een spatie. Enkele voorbeelden: 'VO-YMvKas' // 'UXL EO-YMeKas zh'; Nullable: True; Default: None|
|LENGTE                              |Float(0,10,2)        |PNH; Lengte van de kabel (m, 2 decimalen); Nullable: True|
|OMSCHRIJVING                        |String(255,0,0)      |PNH; Extra toelichting; Nullable: True; Default: None|
|NAAR                                |String(50,0,0)       |PNH; Bestemming van de kabel. Bijvoorbeeld 'MOF' // 'LM 10052' // 'DRK83.1' // Lnt 7.2' // 'LUS D8.2'; Nullable: True; Default: None|
|OPMERKING                           |String(3000,0,0)     |PNH; Opmerking; Nullable: True; Default: None|
|PRODUCT                             |String(50,0,0)       |PNH; Het product dat door de leiding vervoerd wordt of kan worden vervoerd, 'Energie', 'Data' of 'Onbekend'; Nullable: True; Default: None|
|VAN                                 |String(255,0,0)      |PNH; Startlocatie van de kabel. Bijvoorbeeld 'MOF'// 'VRI522103' // 'LM 54304' ; Nullable: True; Default: None|
|VERHOOGDRISICO                      |String(10,0,0)       |PNH; Verhoogd risico Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: O|
|VOORZORGMAATREGEL                   |String(255,0,0)      |PNH; Vermelding of er voorzorgsmaatregelen getroffen dienen te worden. Aangegeven wordt wat de voorzorgsmaatregel is; Nullable: True; Default: None|
|MATERIAALTYPE                       |String(20,0,0)       |PNH; Materiaaltype; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None|
|HUIDIGESTATUS                       |String(50,0,0)       |PNH; Huidige status; keuzelijst [ConditionOfFacilityValue]; Nullable: False; Default: None|
|TOELICHTING                         |String(255,0,0)      |PNH; Extra toelichting; Nullable: True; Default: None|
|GEONAUWKEURIGHEIDXY                 |String(50,0,0)       |IMKL; Nauwkeurigheid van de liggingsgegevens in het horizontale vlak; keuzelijst [NauwkeurigheidXYvalue]; Nullable: True; Default: None|
|DIEPTELEGGING                       |String(255,0,0)      |PNH; FK naar diepteTovMaaiveld_p; Nullable: True; Default: None|
|KASTVRI                             |String(255,0,0)      |PNH; FK naar kastVri_p; Nullable: True; Default: None|
|DATALEVERANCIER                     |String(255,0,0)      |PNH; Leverancier van de data; Nullable: True; Default: None|
|CREATED_USER                        |String(255,0,0)      |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)          |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)       |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)          |PNH; Datum van de laatste mutatie; Nullable: True|
|SHAPE                               |Geometry             |PNH; Lijn|
|SHAPE_Length                        |Double(0,0,0)        |PNH; Lengte in meters, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None|


***