## AREAALDATA.electriciteitskabel_l

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ IMKL (2015)
* __Positionele nauwkeurigheid:__ 7,5 cm
* __Geometrie:__ Lijn
* __Definitie:__ Een aansluiting of reeks aansluitingen van een nutsvoorzieningennet voor het overbrengen van elektriciteit van de ene locatie naar een andere. (Bron: INSPIRE)
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ Kabel
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                |-----    |
|OBJECTID                            |OID(38,0,0)         |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)    |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: No|
|AD_ID                               |String(255,0,0)     |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |Integer(0,10,0)     |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                       |String(255,0,0)     |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|HUIDIGESTATUS                       |String(50,0,0)      |PNH; Huidige status; keuzelijst [ConditionOfFacilityValue]; Nullable: False; Default: functional; Visible: Yes|
|VERWERKINGSSTATUS                   |String(255,0,0)     |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)         |PNH; Datum waarop het object voor het eerst volgens het areaaldata datamodel wordt vastgelegd ; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)         |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|BEHEERDER                           |String(255,0,0)     |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |String(255,0,0)     |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |String(255,0,0)     |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: False; Default: None; Visible: Yes|
|TYPESPEC                            |String(10,0,0)      |PNH; Nadere typering van het object; keuzelijst [typeSpecKAB]; Nullable: True; Default: None; Visible: Yes|
|AANTALADERS                         |String(50,0,0)      |PNH; Het aantal aders in de elektriciteitskabel. Punten geven decimalen weer, geen spaties en het gebruik van 'x' ipv 'X'. Enkele voorbeelden: 8x1.5+2.5 // 1x2 // 3x4x0.8; ; Nullable: True; Default: None; Visible: No|
|CODEKABEL                           |String(255,0,0)     |PNH; Codering om het type kabel nader te onderscheiden. Hoofdlettergebruik is belangrijk. 'zh' en 'mb' specificatie volgt de code en dan een spatie. Enkele voorbeelden: 'VO-YMvKas' // 'UXL EO-YMeKas zh'; ; Nullable: True; Default: None; Visible: Yes|
|NAAR                                |String(255,0,0)     |PNH; Bestemming van de kabel. Bijvoorbeeld 'MOF' // 'LM 10052' // 'DRK83.1' // Lnt 7.2' // 'LUS D8.2' ; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |String(3000,0,0)    |PNH; Toevoeging van subjectieve informatie met betrekking tot opmerkelijke waarnemingen; ; Nullable: True; Default: None; Visible: Yes|
|VAN                                 |String(255,0,0)     |PNH; Startlocatie van de kabel. Bijvoorbeeld 'MOF'// 'VRI522103' // 'LM 54304'; ; Nullable: True; Default: None; Visible: Yes|
|GEONAUWKEURIGHEIDXY                 |String(50,0,0)      |PNH; Nauwkeurigheid van de liggingsgegevens in het horizontale vlak in cm; ; Nullable: False; Default: None; Visible: No|
|BEDRIJFSSPANNING                    |Integer(0,10,0)     |PNH; Bedrijfsvoltage in V, afkomstig uit operatingVoltage; ; Nullable: False; Default: 230; Visible: Yes|
|NOMINALESPANNING                    |Integer(0,10,0)     |PNH; Nominale spanning in V, afkomstig uit nominalVoltage; ; Nullable: False; Default: 230; Visible: Yes|
|VERTICALE_POSITIE                   |Integer(0,10,0)     |PNH; Verticale positie; keuzelijst [VerticalePositie]; Nullable: False; Default: 3; Visible: No|
|KASTVRI                             |String(255,0,0)     |PNH; Verwijzende sleutel naar kastVri_p (simpel); ; Nullable: True; Default: None; Visible: Yes|
|KASTOVL                             |String(255,0,0)     |PNH; Verwijzende sleutel naar kastOvl_p (simpel); ; Nullable: True; Default: None; Visible: Yes|
|DIEPTELEGGING                       |String(255,0,0)     |PNH; Dieptelegging van de gehele kabel tov maaiveld in cm; ; Nullable: False; Default: None; Visible: Yes|
|INDICATIEVELIGGING                  |String(1,0,0)       |PNH; Is de geometrie indicatief ingetekend, ja of nee; keuzelijst [jaNee]; Nullable: false; Default: J; Visible: Yes|
|EISVOORZORGSMAATRBUFFER             |Integer(0,10,0)     |PNH; Wanneer de asset een verhoogd risico/impact op/bij graafschade heeft, kan hier een veiligheidsbuffer in meters worden opgegeven. Wanneer aan de algemene EV-voorwaarden is voldaan en er binnen deze buffer gegraven wordt, ontvangt de grondroerder een eisvoorzorgsmaatregelbrief. Zonder opgaaf gelden algemene uitgangspunten en voorgedefinieerde bufferafstand. Bij een negatieve waarde, als -1, wordt geen brief uitgestuurd; ; Nullable: True; Default: None; Visible: No|
|IMKL_InNetwork                      |String(255,0,0)     |PNH; Provincie aanduiding voor het type net, VB: VRI of OVL; keuzelijst [IMKL_InNetwork]; Nullable: False; Default: None; Visible: Yes|
|DATALEVERANCIER                     |String(255,0,0)     |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |String(255,0,0)     |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)         |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)      |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)         |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry            |PNH; Lijn; ; Nullable: False; Default: None; Visible: Yes|
|SHAPE_Length                        |Double(0,0,0)       |PNH; Lengte in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|LENGTE                              |Double(0,0,0)       |PNH; Lengte in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|







***
