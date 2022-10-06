## AREAALDATA.kastVri_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.2
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
|GLOBALID                            |GlobalID(38,0,0)       |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |String(255,0,0)        |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |Integer(0,10,0)        |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                       |String(255,0,0)        |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |String(255,0,0)        |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|HUIDIGESTATUS                       |String(50,0,0)         |PNH; Huidige status; keuzelijst [ConditionOfFacilityValue]; Nullable: False; Default: functional; Visible: No|
|STATUS                              |String(10,0,0)         |BGT; BGT status van het object; keuzelijst [status]; Nullable: False; Default: bestaand; Visible: No|
|OBJECTBEGINTIJD                     |Date(8,0,0)            |PNH; Datum waarop het object voor het eerst volgens het areaaldata datamodel wordt vastgelegd ; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)            |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING              |SmallInteger(0,5,0)    |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                           |String(255,0,0)        |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |String(255,0,0)        |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |String(255,0,0)        |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|BRONHOUDER                          |String(5,0,0)          |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None; Visible: No|
|VERTICALE_POSITIE                   |Integer(0,10,0)        |PNH; Verticale positie; keuzelijst [VerticalePositie]; Nullable: False; Default: 3; Visible: No|
|BGTPLUSTYPE                         |String(50,0,0)         |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeKST]; Nullable: False; Default: None; Visible: No|
|TOPDESK_ID                          |String(255,0,0)        |PNH; Verwijzing naar ObjectID TOPdesk; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |String(255,0,0)        |PNH; Toevoeging van subjectieve informatie met betrekking tot opmerkelijke waarnemingen; ; Nullable: True; Default: None; Visible: Yes|
|AUTOMAATKOPPELING                   |String(255,0,0)        |PNH; Indicatie of de automaat gekoppeld is aan één of meer andere automaten; ; Nullable: True; Default: None; Visible: Yes|
|CONTRACTNUMONDERH                   |String(255,0,0)        |PNH; Telefoonnummer van het contract met de onderhouder; ; Nullable: True; Default: None; Visible: Yes|
|DATUMGARANTIE                       |Date(8,0,0)            |PNH; Datum en jaartal tot wanneer de garantie geldig is; ; Nullable: True; Default: None; Visible: No|
|DATUMPLAATSING                      |Date(8,0,0)            |PNH; Datum plaatsing kast; ; Nullable: True; Default: None; Visible: No|
|JAAR_PLAATSING_AANLEG_GESCHAT       |String(1,0,0)          |PNH; Jaar plaatsing of aanleg is geschat: Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|TYPESPEC                            |String(255,0,0)        |PNH; Nadere typering van het object; keuzelijst [typeSpecKST]; Nullable: True; Default: None; Visible: Yes|
|LEVENSVERWACHTING                   |SmallInteger(0,5,0)    |PNH; Levensverwachting; ; Nullable: True; Default: None; Visible: No|
|NUMMERGEKOPPELDEAU                  |String(255,0,0)        |PNH; Indien een automatenkoppeling: de soort koppeling (groene golf, peletonkoppeling, etc.); ; Nullable: True; Default: None; Visible: Yes|
|PLANJAAR                            |SmallInteger(0,5,0)    |PNH; Het jaar dat nu gepland staat om item te vervangen; ; Nullable: True; Default: None; Visible: No|
|PRIOVOORZIENINGEN                   |String(255,0,0)        |PNH; Indicatie of de kast één of meer prioriteitsvoorzieningen bevat, ja/nee. Zo ja, weten welke proriteitsvoorziening het is: het kunnen er meerdere zijn; ; Nullable: True; Default: None; Visible: Yes|
|RALKLEUR                            |String(30,0,0)         |PNH; De RAL-kleur(en) die gebruikt zijn voor het object. Eerst de kleurcode gevolgd door de naam van de kleur; ; Nullable: True; Default: None; Visible: No|
|RESTLEVENSDUUR                      |SmallInteger(0,5,0)    |PNH; Restlevensduur in maanden; ; Nullable: True; Default: None; Visible: No|
|SERIENUMMER                         |String(255,0,0)        |PNH; Serienummer van de fabrikant (5 á 6 posities); ; Nullable: True; Default: None; Visible: Yes|
|ZIJWEG                              |String(255,0,0)        |PNH; Straatnaam (één vermelden, ook al zijn er meer); ; Nullable: True; Default: None; Visible: Yes|
|LAMPSPANNING                        |String(255,0,0)        |PNH; Lampspanning waarde; ; Nullable: True; Default: None; Visible: No|
|SOORTAUTOMAATKOPPE                  |String(255,0,0)        |PNH; Soort Automaatkoppeling; ; Nullable: True; Default: None; Visible: No|
|TYPECOMMUNICATIE                    |String(30,0,0)         |PNH; Type communicatie; keuzelijst [TYPE_COMMUNICATIE]; Nullable: True; Default: None; Visible: No|
|ADRES                               |String(255,0,0)        |PNH; Verwijzende sleutel naar adres_tbl (simpel); ; Nullable: True; Default: None; Visible: No|
|INNETWERK                           |String(255,0,0)        |PNH; Verwijzende sleutel naar utiliteitsNet_tbl (simpel); ; Nullable: True; Default: None; Visible: Yes|
|EISVOORZORGSMAATRBUFFER             |Integer(0,10,0)        |PNH; Wanneer de asset een verhoogd risico/impact op/bij graafschade heeft, kan hier een veiligheidsbuffer in meters worden opgegeven. Wanneer aan de algemene EV-voorwaarden is voldaan en er binnen deze buffer gegraven wordt, ontvangt de grondroerder een eisvoorzorgsmaatregelbrief. Zonder opgaaf gelden algemene uitgangspunten en voorgedefinieerde bufferafstand. Bij een negatieve waarde, als -1, wordt geen brief uitgestuurd; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |String(255,0,0)        |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|INONDERZOEK                         |String(1,0,0)          |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible: No|
|TIJDSTIPREGISTRATIE                 |Date(8,0,0)            |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|EINDREGISTRATIE                     |Date(8,0,0)            |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|LV_PUBLICATIEDATUM                  |Date(8,0,0)            |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BERICHT_ID                          |String(128,0,0)        |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |String(255,0,0)        |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)            |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)         |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)            |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|KP_CODE                             |Integer(15,0,0)        |PNH; kruispuntcode;  ; Nullable: True; Default: None; Visible: Yes|
|WEGNR                               |String(15,0,0)         |PNH; Wegnr, bijv: N241;  ; Nullable: True; Default: None; Visible: Yes|
|EERSTELIJN                          |String(50,0,0)         |PNH; SP eerstelijn onderhoud;  ; Nullable: True; Default: None; Visible: No|
|TELEFOON                            |String(15,0,0)         |PNH; SP Telefoon;  ; Nullable: True; Default: None; Visible: No|
|KENMERKEN                           |String(255,0,0)        |PNH; SP Kenmerken;  ; Nullable: True; Default: None; Visible: No|
|LEVERANCIER                         |String(50,0,0)         |PNH; SP LEVERANCIER;  ; Nullable: True; Default: None; Visible: No|
|CONTACTNR                           |String(15,0,0)         |PNH; SP CONTACTNR;  ; Nullable: True; Default: None; Visible: No|
|OPMERKING_SP                        |String(255,0,0)        |PNH; SP OPMERKING_SP;  ; Nullable: True; Default: None; Visible: No|
|IMPACT_VEILIGHEID                   |Integer(0,10,0)        |PNH; SCORE IMPACT_VEILIGHEID; keuzelijst [VRI_SCORE_VEILIGHEID]; Nullable: True; Default: None; Visible: No|
|IMPACT_VERTRAGING_MIN               |Integer(0,10,0)        |PNH; SCORE IMPACT_VERTRAGING_MIN; keuzelijst [VRI_SCORE_VERTRAGING_MIN]; Nullable: True; Default: None; Visible: No|
|OVERSTEEKBAARHEID                   |Integer(0,10,0)        |PNH; SCORE OVERSTEEKBAARHEID; keuzelijst [VRI_SCORE_OVERSTEEKBAARHEID]; Nullable: True; Default: None; Visible: No|
|HINDER_LANGZAAM_VERKEER             |Integer(0,10,0)        |PNH; SCORE HINDER_LANGZAAM_VERKEER; keuzelijst [VRI_SCORE_HINDER_LANGZAAM_VERKEER]; Nullable: True; Default: None; Visible: No|
|HINDER_OV                           |Integer(0,10,0)        |PNH; SCORE HINDER_OV; ; Nullable: True; Default: None; Visible: No|
|PRIO_NETWERKVISIE                   |Integer(0,10,0)        |PNH; SCORE PRIO_NETWERKVISIE; keuzelijst [VRI_SCORE_PRIO_NETWERKVISIE]; Nullable: True; Default: None; Visible: No|
|VM_KWALITEITSNIVEAU                 |Integer(0,10,0)        |PNH; SCORE VM_KWALITEITSNIVEAU; keuzelijst [VRI_SCORE_VM_KWALITEITSNIVEAU]; Nullable: True; Default: None; Visible: No|
|TOTAALSCORE                         |Integer(0,10,0)        |PNH; TOTAALSCORE calculated field;  ; Nullable: True; Default: None; Visible: No|
|TOTAALPRIO                          |Integer(0,10,0)        |PNH; TOTAALPRIO calculated field;  ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry(0,0,0)        |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|




***
