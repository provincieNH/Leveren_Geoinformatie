## AREAALDATA.kastVri_p

$ Feature dataset: Inrichtend

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Kast ten behoeve van de regeling van verkeerslichten


***

|KOLOM                             |TYPE          	   |DEFINITIE|
|------                            |----          	   |-----    |
|BGTPLUSTYPE                       |String(50,0,0)     |Beschrijving - keuzelijst [typeKST] Nullable: False Default: None|
|IDENTIFICATIE                     |String(255,0,0)    |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|STATUS                            |String(10,0,0)     |Beschrijving - keuzelijst [status] Nullable: False Default: :bestaand|
|BRONHOUDER                        |String(5,0,0)      |BGT, De bronhoudercode van het object, keuzelijst [bronhouder] - Nullable: False Default: None|
|INONDERZOEK                       |String(1,0,0)      |BGT, Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee, keuzelijst [jaNee] Nullable: False Default: N|
|RELATIEVEHOOGTELIGGING            |SmallInteger(0,10,0)|BGT, Aanduiding voor de relatieve hoogte van het object - Nullable: False Default: 0|
|TIJDSTIPREGISTRATIE               |Date(8,0,0)        |Beschrijving - keuzelijst [] Nullable: True Default: None|
|EINDREGISTRATIE                   |Date(8,0,0)        |Beschrijving - keuzelijst [] Nullable: True Default: None|
|LV_PUBLICATIEDATUM                |Date(8,0,0)        |BGT, Tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening - Nullable: True|
|BERICHT_ID                        |String(128,0,0)    |Beschrijving - keuzelijst [] Nullable: True Default: None|
|SHAPE                             |Geometry(0,0,0)    |Beschrijving: - keuzelijst [] Nullable: True Default: None|
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
|TOPDESK_ID                          |String(255,0,0)     |Verwijzing naar ObjectID TOPdesk - Nullable: True Default: None|
|OMSCHRIJVING                        |String(255,0,0)     |Omschrijving - Nullable: True Default: None|
|ADSLKENMERK                         |String(255,0,0)     |TODO - Nullable: True Default: None|
|AUTOMAATKOPPELING                   |String(255,0,0)     |Indicatie of de automaat gekoppeld is aan één of meer andere automaten - Nullable: True Default: None|
|CONTRACTNUMONDERH                   |String(255,0,0)     |Nummer van het contract met de onderhouder - Nullable: True Default: None|
|DATUMGARANTIE                       |Date(8,0,0)         |TODO - Nullable: True|
|DATUMPLAATSING                      |Date(8,0,0)         |Datum plaatsing kast  - Nullable: True|
|JAAR_PLAATSING_AANLEG_GESCHAT       |String(1,0,0)      |Jaar plaatsing of aanleg is geschat: Ja/Nee - keuzelijst [jaNee] - Nullable: True Default: N|
|DEELCONFLICT                        |String(255,0,0)     |TODO - Nullable: True Default: None|
|DYNAMISCHVERKEERSM                  |String(255,0,0)     |TODO - Nullable: True Default: None|
|EANEMETER                           |String(255,0,0)     |De EAN-code vermeld op de meter - Nullable: True Default: None|
|FTPGEBRUIKERSWACHT                  |String(255,0,0)     |TODO - Nullable: True Default: None|
|FTPGEBRUIKERSNAAM                   |String(255,0,0)     |TODO - Nullable: True Default: None|
|INDIVIDUELELAMPMEL                  |String(255,0,0)     |TODO - Nullable: True Default: None|
|IVERAINBELWACHTWOO                  |String(255,0,0)     |T.b.v. de communicatie met de VRI-beheercentrale - Nullable: True Default: None|
|IVERAINBELNAAM                      |String(255,0,0)     |T.b.v. de communicatie met de VRI-beheercentrale - Nullable: True Default: None|
|IVERAIP                             |String(255,0,0)     |T.b.v. de communicatie met de VRI-beheercentrale - Nullable: True Default: None|
|IVERALICENTIENUMME                  |String(255,0,0)     |T.b.v. de communicatie met de VRI-beheercentrale - Nullable: True Default: None|
|IVERAPIN                            |String(255,0,0)     |T.b.v. de communicatie met de VRI-beheercentrale - Nullable: True Default: None|
|IVERAVERSIENUMMER                   |String(255,0,0)     |Versienummer van de aansluiting - Nullable: True Default: None|
|KANVASADRES                         |String(255,0,0)     |TODO - Nullable: True Default: None|
|KARANTENNE                          |String(1,0,0)       |Kar Antenne aanwezig: Ja/Nee (keuzelijst [jaNee] - Nullable: True Default: N|
|KASTTYPE                            |String(255,0,0)     |TODO - Nullable: True Default: None|
|KWCLICENTIENUMMER                   |String(1,0,0)       |T.b.v. de aansluiting op de kwaliteitscentrale - Nullable: True Default: N|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)|TODO - Nullable: True|
|NUMMERGEKOPPELDEAU                  |String(255,0,0)     |Indien een automatenkoppeling: de soort koppeling (groene golf, peletonkoppeling, etc.) - Nullable: True Default: None|
|PLANJAAR                            |SmallInteger(0,10,0)|TODO - Nullable: True|
|PRIOVOORZIENINGEN                   |String(255,0,0)     |Indicatie of de kast één of meer prioriteitsvoorzieningen bevat - Nullable: True Default: None|
|RALKLEUR                            |String(255,0,0)     |TODO - Nullable: True Default: None|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0)|Restlevensduur - Nullable: True|
|ROODLAMPBEWAKING                    |String(255,0,0)     |Rood Lamp Bewaking - Nullable: True Default: None|
|SERIENUMMER                         |String(255,0,0)     |Serienummer van de fabrikant (5 á 6 posities) - Nullable: True Default: None|
|SIMNUMMER                           |String(255,0,0)     |TODO - Nullable: True Default: None|
|SOORTPRIOVOORZIENI                  |String(255,0,0)     |Indien een kast één of meer prioriteitsvoorzieningen bevat: de soort prioriteitsvoorziening (KAR (t.b.v. bussen OV een modem) of VTAG, SICS (dan een kaart)) - Nullable: True Default: None|
|SSIDKORTEAFSTANDRA                  |String(255,0,0)     |SSID van de KAR - Nullable: True Default: None|
|TELNUMMER                           |Integer(0,10,0)     |Het telefoonnummer van de automaat - Nullable: True|
|VOORGENVERVDATUM                    |String(255,0,0)     |Datum waarop de kast vervangen moet worden. - Nullable: True Default: None|
|ZIJWEG                              |String(255,0,0)     |Straatnaam (één vermelden, ook al zijn er meer) - Nullable: True Default: None|
|DIMMETHODE                          |String(255,0,0)     |Dimmethode, keuzelijst [DIMMETHODE] - Nullable: True Default: None|
|FABRIKANTTYPECODE                   |String(255,0,0)     |Fabrikant typecode, keuzelijst [FABRIKANT_TYPECODE] - Nullable: True Default: None|
|LAMPSPANNING                        |String(255,0,0)     |Lampspanning waarde - Nullable: True Default: None|
|SOORTAUTOMAATKOPPE                  |String(255,0,0)     |Soort Automaatkoppeling - Nullable: True Default: None|
|TYPECOMMUNICATIE                    |String(255,0,0)     |Type communicatie, keuzelijst [TYPE_COMMUNICATIE] - Nullable: True Default: None|
|INNETWERK                           |String(255,0,0)     |FK naar utiliteitsNet_tbl (type VRI)- Nullable: True Default: None|
|TRAJECT                             |String(255,0,0)     |FK naar traject_v - Nullable: True Default: None|
|ADRES                               |String(255,0,0)     |FK naar adres_tbl - Nullable: True Default: None|


***
