## AREAALDATA.kastOvl_p

$ Feature dataset: Inrichtend

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Kast ten behoeve van de regeling van de openbare verlichting.


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
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecKST] - Nullable: True Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)    |Status van de gegevens, keuzelijst [VERWERKINGSSTATUS] - Nullable: False Default: Nieuw|
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
|OMSCHRIJVING                        |String(255,0,0)     |Omschrijving - Nullable: True Default: None|
|AANTALGROEPEN                       |SmallInteger(0,10,0)|Aantal elektriciteitsgroepen aanwezig in de kast - Nullable: True|
|TYPECOMMUNICATIE                    |String(255,0,0)     |Type Communicatie, keuzelijst [TYPE_COMMUNICATIE] - Nullable: True Default: None|
|DATUMGARANTIE                       |Date(8,0,0)         |Datum garantie - Nullable: True|
|DATUMPLAATSING                      |Date(8,0,0)         |Datum plaatsing - Nullable: True|
|JAAR_PLAATSING_AANLEG_GESCHAT       |String(1,0,0)       |Jaar plaatsing of aanleg is geschat: : Ja/Nee - keuzelijst [jaNee] - Nullable: True Default: N|
|AANWEZGIHEIDDIM                     |String(1,0,0)       |Aanwezigheid van een diminstallatie in de kast: Ja/Nee - keuzelijst [jaNee] - Nullable: True Default: N|
|AANWTELEMANAGEMENT                  |String(1,0,0)       |Aanwezigheid van een telemanagementvoorziening in de kast (t.b.v. het op afstand kunnen instellen): Ja/Nee - keuzelijst [jaNee] - Nullable: True Default: N|
|AUTOMAATKOPPELING                   |String(255,0,0)     |Indicatie of de automaat gekoppeld is aan één of meer andere automaten (met name bij LED-kasten) - Nullable: True Default: None|
|AUTOMAATNUMMER                      |SmallInteger(0,10,0)|Indien een automatenkoppeling: kastnummer van de gekoppelde automaat - Nullable: True Default: None|
|CONSERVERING                        |String(255,0,0)     |Conservering - Nullable: True Default: None|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)|Levensverwachting - Nullable: True|
|PLANJAAR                            |SmallInteger(0,10,0)|Planjaar - Nullable: True|
|RALKLEUR                            |String(255,0,0)     |Ralkleur - Nullable: True Default: None|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0)|Restlevensduur - Nullable: True|
|TELNUMMER                           |SmallInteger(0,10,0)|Indien een telemanagementvoorziening aanwezig is: wat is het telefoonnummer hiervan - Nullable: True|
|FABRIKANTTYPECODE                   |String(255,0,0)     |Fabrikanttypecode, keuzelijst [FABRIKANT_TYPECODE] - Nullable: True Default: None|
|EANEMETER                           |String(255,0,0)     |De EAN-code vermeld op de meter - Nullable: True Default: None|
|KASTNUMMER                          |String(255,0,0)     |Bestaande uit 6 cijfers: de eerste drie het nummerdeel van het wegnummer (N201 -> 201), de laatste drie het nummer van het dichtstbijzijnde hectometerpaaltje (38,1 -> 381) = Installatienummer (zie Verlichtingsinstallatie) - Nullable: True Default: None|
|DIMSYSTEEM                          |String(1,0,0)       |Dimsysteem: Ja/Nee/Onbekend, keuzelijst [jaNeeOnbekend] Nullable: True Default: O|
|MATERIAALTYPE                       |String(255,0,0)     |Type materiaal, keuzelijst [MATERIAALTYPE] - Nullable: True Default: None|
|INNETWERK                           |String(255,0,0)     |FK naar utiliteitsNet_tbl (type OVL)- Nullable: True Default: None|
|TRAJECT                             |String(255,0,0)     |FK naar traject_v - Nullable: True Default: None|
|ADRES                               |String(255,0,0)     |FK naar adres_tbl - Nullable: True Default: None|


***
