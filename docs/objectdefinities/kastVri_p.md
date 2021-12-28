## AREAALDATA.kastVri_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Kast ten behoeve van de regeling van verkeerslichten
* __Mapping_BGT:__ kast_p
* __Mapping_Gisib:__ VRI kast
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__(oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----          	     |-----    |
|OBJECTID                            |OID(38,0,0)            |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)       |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: No|
|AD_ID                               |TEXT(255,0,0)          |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)           |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)          |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.html); Nullable: False; Default: Nieuw; Visible: Yes|
|HUIDIGESTATUS                       |TEXT(50,0,0)           |PNH; Huidige status; keuzelijst [ConditionOfFacilityValue](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ConditionOfFacilityValue.html); Nullable: False; Default: functional; Visible: No|
|OBJECTBEGINTIJD                     |DATE(8,0,0)            |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)            |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING              |SHORT(0,5,0)           |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                           |TEXT(255,0,0)          |PNH; Beheerder van het object; keuzelijst [BEHEERDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEERDER.html); Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)          |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ONDERHOUDER.html); Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |TEXT(255,0,0)          |PNH; Eigenaar van het object; keuzelijst [INSTANTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/INSTANTIE.html); Nullable: True; Default: None; Visible: Yes|
|VERTICALE_POSITIE                   |LONG(0,10,0)           |PNH; Verticale positie; keuzelijst [VerticalePositie](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VerticalePositie.html); Nullable: False; Default: 3; Visible: No|
|BGTPLUSTYPE                         |TEXT(50,0,0)           |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeKST](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeKST.html); Nullable: False; Default: None; Visible: No|
|VRI_NUMMER                          |TEXT(255,0,0)          |PNH; Verwijzing naar ObjectID TOPdesk; ; Nullable: True; Default: None; Visible: No|
|OPMERKING_BSP                       |TEXT(255,0,0)          |PNH; Toevoeging van subjectieve informatie met betrekking tot opmerkelijke waarnemingen; ; Nullable: True; Default: None; Visible: Yes|
|AUTOMAATKOPPELING                   |TEXT(255,0,0)          |PNH; Indicatie of de automaat gekoppeld is aan één of meer andere automaten; ; Nullable: True; Default: None; Visible: Yes|
|CONTRACTNUMONDERH                   |TEXT(255,0,0)          |PNH; Telefoonnummer van het contract met de onderhouder; ; Nullable: True; Default: None; Visible: Yes|
|DATUMGARANTIE                       |DATE(8,0,0)            |PNH; Datum en jaartal tot wanneer de garantie geldig is; ; Nullable: True; Default: None; Visible: No|
|DATUMPLAATSING                      |DATE(8,0,0)            |PNH; Datum plaatsing kast; ; Nullable: True; Default: None; Visible: No|
|TYPESPEC                            |TEXT(255,0,0)          |PNH; Nadere typering van het object; keuzelijst [typeSpecKST](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecKST.html); Nullable: True; Default: None; Visible: Yes|
|LEVENSVERWACHTING                   |SHORT(0,5,0)           |PNH; Levensverwachting; ; Nullable: True; Default: None; Visible: No|
|PLANJAAR                            |SHORT(0,5,0)           |PNH; Het jaar dat nu gepland staat om item te vervangen; ; Nullable: True; Default: None; Visible: No|
|PRIOVOORZIENINGEN                   |TEXT(255,0,0)          |PNH; Indicatie of de kast één of meer prioriteitsvoorzieningen bevat, ja/nee. Zo ja, weten welke proriteitsvoorziening het is: het kunnen er meerdere zijn; ; Nullable: True; Default: None; Visible: Yes|
|SERIENUMMER                         |TEXT(255,0,0)          |PNH; Serienummer van de fabrikant (5 á 6 posities); ; Nullable: True; Default: None; Visible: Yes|
|ZIJWEG                              |TEXT(255,0,0)          |PNH; Straatnaam (één vermelden, ook al zijn er meer); ; Nullable: True; Default: None; Visible: Yes|
|LAMPSPANNING                        |TEXT(255,0,0)          |PNH; Lampspanning waarde; ; Nullable: True; Default: None; Visible: No|
|SOORTAUTOMAATKOPPE                  |TEXT(255,0,0)          |PNH; Soort Automaatkoppeling; ; Nullable: True; Default: None; Visible: No|
|TYPECOMMUNICATIE                    |TEXT(30,0,0)           |PNH; Type communicatie; keuzelijst [TYPE_COMMUNICATIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/TYPE_COMMUNICATIE.html); Nullable: True; Default: None; Visible: No|
|INNETWERK                           |TEXT(255,0,0)          |PNH; Verwijzende sleutel naar utiliteitsNet_tbl (simpel); ; Nullable: True; Default: None; Visible: Yes|
|EISVOORZORGSMAATRBUFFER             |LONG(0,10,0)           |PNH; Wanneer de asset een verhoogd risico/impact op/bij graafschade heeft, kan hier een veiligheidsbuffer in meters worden opgegeven. Wanneer aan de algemene EV-voorwaarden is voldaan en er binnen deze buffer gegraven wordt, ontvangt de grondroerder een eisvoorzorgsmaatregelbrief. Zonder opgaaf gelden algemene uitgangspunten en voorgedefinieerde bufferafstand. Bij een negatieve waarde, als -1, wordt geen brief uitgestuurd; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |TEXT(255,0,0)          |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |TEXT(255,0,0)          |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)            |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)           |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)            |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|KP_CODE                             |LONG(15,0,0)           |PNH; kruispuntcode;  ; Nullable: True; Default: None; Visible: Yes|
|WEGNR                               |TEXT(15,0,0)           |PNH; Wegnr, bijv: N241; ;Nullable: True; Default: None; Visible: Yes|
|TELEFOON                            |TEXT(15,0,0)           |PNH; SP Telefoon; ;Nullable: True; Default: None; Visible: No|
|KENMERKEN                           |TEXT(255,0,0)          |PNH; SP Kenmerken; ;Nullable: True; Default: None; Visible: No|
|LEVERANCIER                         |TEXT(50,0,0)           |PNH; SP LEVERANCIER; ;Nullable: True; Default: None; Visible: No|
|CONTACTNR                           |TEXT(15,0,0)           |PNH; SP CONTACTNR; ;Nullable: True; Default: None; Visible: No|
|OPMERKING_SP                        |TEXT(255,0,0)          |PNH; SP OPMERKING_SP; ;Nullable: True; Default: None; Visible: No|
|OPMERKING                           |TEXT(255,0,0)          |PNH; Algemene opmerking door GON voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|IMPACT_VEILIGHEID                   |LONG(0,10,0)           |PNH; SCORE IMPACT_VEILIGHEID; keuzelijst [VRI_SCORE_VEILIGHEID](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VRI_SCORE_VEILIGHEID.html); Nullable: True; Default: None; Visible: No|
|IMPACT_VERTRAGING_MIN               |LONG(0,10,0)           |PNH; SCORE IMPACT_VERTRAGING_MIN; keuzelijst [VRI_SCORE_VERTRAGING_MIN](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VRI_SCORE_VERTRAGING_MIN.html); Nullable: True; Default: None; Visible: No|
|OVERSTEEKBAARHEID                   |LONG(0,10,0)           |PNH; SCORE OVERSTEEKBAARHEID; keuzelijst [VRI_SCORE_OVERSTEEKBAARHEID](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VRI_SCORE_OVERSTEEKBAARHEID.html); Nullable: True; Default: None; Visible: No|
|HINDER_LANGZAAM_VERKEER             |LONG(0,10,0)           |PNH; SCORE HINDER_LANGZAAM_VERKEER; keuzelijst [VRI_SCORE_HINDER_LANGZAAM_VERKEER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VRI_SCORE_HINDER_LANGZAAM_VERKEER.html); Nullable: True; Default: None; Visible: No|
|HINDER_OV                           |LONG(0,10,0)           |PNH; SCORE HINDER_OV; ; Nullable: True; Default: None; Visible: No|
|PRIO_NETWERKVISIE                   |LONG(0,10,0)           |PNH; SCORE PRIO_NETWERKVISIE; keuzelijst [VRI_SCORE_PRIO_NETWERKVISIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VRI_SCORE_PRIO_NETWERKVISIE.html); Nullable: True; Default: None; Visible: No|
|VM_KWALITEITSNIVEAU                 |LONG(0,10,0)           |PNH; SCORE VM_KWALITEITSNIVEAU; keuzelijst [VRI_SCORE_VM_KWALITEITSNIVEAU](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VRI_SCORE_VM_KWALITEITSNIVEAU.html); Nullable: True; Default: None; Visible: No|
|TOTAALSCORE                         |LONG(0,10,0)           |PNH; TOTAALSCORE calculated field; ;Nullable: True; Default: None; Visible: No|
|TOTAALPRIO                          |LONG(0,10,0)           |PNH; TOTAALPRIO calculated field; ;Nullable: True; Default: None; Visible: No|
|HECTOMETER                          |TEXT(255,0,0)          |PNH; Hectometer aanduiding, scriptmatig te bepalen obv dichtst bijzijnde hectometerpaal; ; Nullable: True; Default: None; Visible: Yes|
|VRI_FOLDER_URL                      |TEXT(500,0,0)          |PNH; Locatie VRI-folder; ; Nullable: True; Default: \\nhwvmfsp.003.pds.noord-holland.nl\data4\bu\kernbeheer\vri; Visible: Yes|
|HULPDIENSTINGREEP_VIA_KAR           |TEXT(255,0,0)          |PNH; Hulpdienst ingreep via KAR; keuzelijst [jaNee] ; Nullable: True; Default: None; Visible: Yes|
|CAMERA_OBSERVATIE                   |TEXT(255,0,0)          |PNH; Aanwezigheid van observatiecamera bij VRI installatie; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.html); Nullable: True; Default: None; Visible: Yes|
|DEELCONFLICT_AANWEZIG               |TEXT(255,0,0)          |PNH; Deelconflict aanwezig; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.html); Nullable: True; Default: None; Visible: Yes|
|KAR_ID                              |LONG(15,0,0)           |PNH; KAR-ID; ; Nullable: True; Default: None; Visible: Yes|
|TOPDESKLOCATIE_LATITUDE             |DOUBLE(0,0,0)          |PNH; Niet ingemeten LATITUDE in WGS84, in decimale graden afkomstig uit Topdesk. Na inmeting wordt dit coordinaat verwijderd; ; Nullable: True; Default: None; Visible: No|
|TOPDESKLOCATIE_LONGTITUDE           |DOUBLE(0,0,0)          |PNH; Niet ingemeten LONGTITUDE in WGS84, in decimale graden afkomstig uit Topdesk. Na inmeting wordt dit coordinaat verwijderd; ; Nullable: True; Default: None; Visible: No|
|LOCATIE_INGEMETEN                   |TEXT(255,0,0)          |PNH; Locatie ingemeten of niet, indien afkomstig uit topdesk=nee; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.html); Nullable: True; Default: None; Visible: Yes|
|SHAPE                               |Geometry(0,0,0)        |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|




***
