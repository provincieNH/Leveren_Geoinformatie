## AREAALDATA.kastOvl_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Kast ten behoeve van de regeling van de openbare verlichting.


***

|KOLOM                               |TYPE (length, precision, scale)          	     |DEFINITIE (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----          	     |-----    |
|OBJECTID                            |OID(38,0,0)            |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)       |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |String(255,0,0)        |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |Integer(0,10,0)        |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BGTPLUSTYPE                         |String(50,0,0)         |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeKST]; Nullable: False; Default: None; Visible: No|
|IDENTIFICATIE                       |String(255,0,0)        |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |String(255,0,0)        |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|STATUS                              |String(10,0,0)         |BGT; BGT status van het object; keuzelijst [status]; Nullable: False; Default: bestaand; Visible: No|
|OBJECTBEGINTIJD                     |Date(8,0,0)            |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)            |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING              |SmallInteger(0,10,0)   |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                           |String(255,0,0)        |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |String(255,0,0)        |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |String(255,0,0)        |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|BRONHOUDER                          |String(5,0,0)          |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None; Visible: No|
|TYPESPEC                            |String(255,0,0)        |PNH; Nadere typering van het object; keuzelijst [typeSpecKST]; Nullable: True; Default: None; Visible: Yes|
|OMSCHRIJVING                        |String(255,0,0)        |PNH; Omschrijving; ; Nullable: True; Default: None; Visible: Yes|
|AANTALGROEPEN                       |SmallInteger(0,10,0)   |PNH; Aantal elektriciteitsgroepen aanwezig in de kast; ; Nullable: True; Default: None; Visible: No|
|TYPECOMMUNICATIE                    |String(30,0,0)         |PNH; Type communicatie; keuzelijst [TYPE_COMMUNICATIE]; Nullable: True; Default: None; Visible: No|
|DATUMPLAATSING                      |Date(8,0,0)            |PNH; Datum Plaatsing; ; Nullable: True; Default: None; Visible: No|
|JAAR_PLAATSING_AANLEG_GESCHAT       |String(1,0,0)          |PNH; Jaar plaatsing of aanleg is geschat: : Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|AANWEZGIHEIDDIM                     |String(1,0,0)          |PNH; Aanwezigheid van een diminstallatie in de kast: Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|AANWTELEMANAGEMENT                  |String(1,0,0)          |PNH; Aanwezigheid van een telemanagementvoorziening in de kast (t.b.v. het op afstand kunnen instellen): Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|AUTOMAATKOPPELING                   |String(20,0,0)         |PNH; Aangeven of er een koppeling is tussen automaat en Ovlkast; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: None; Visible: Yes|
|AUTOMAATNUMMER                      |Integer(0,10,0)        |PNH; Indien een een automaat gekoppeld is aan een Ovlkast, het kastnummer invullen; ; Nullable: True; Default: None; Visible: Yes|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)   |PNH; Levensverwachting; ; Nullable: True; Default: None; Visible: No|
|PLANJAAR                            |SmallInteger(0,10,0)   |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|RALKLEUR                            |String(30,0,0)         |PNH; De RAL-kleur(en) die gebruikt zijn voor het object. Eerst de kleurcode gevolgd door de naam van de kleur; keuzelijst [RALKLEUR]; Nullable: True; Default: None; Visible: No|
|FABRIKANTTYPECODE                   |String(255,0,0)        |PNH; Fabrikanttypecode; keuzelijst [FABRIKANT_TYPECODE]; Nullable: True; Default: None; Visible: Yes|
|EANEMETER                           |String(255,0,0)        |PNH; De EAN-code vermeld op de meter; ; Nullable: True; Default: None; Visible: No|
|KASTNUMMER                          |String(255,0,0)        |PNH; Bestaande uit 6 cijfers: de eerste drie het nummerdeel van het wegnummer (N201> 201), de laatste drie het nummer van het dichtstbijzijnde hectometerpaaltje (38,1> 381) = Installatienummer (zie Verlichtingsinstallatie); ; Nullable: True; Default: None; Visible: Yes|
|TYPEDIMSYSTEEM                      |String(20,0,0)         |PNH; Het type dimsysteem mits de kastOvl is aangesloten op een dimsysteem, zie AANWEZIGHEIDDIM; Keuzelijst [typedimsysteem]; Nullable: True; Default: None; Visible: No|
|MATERIAALTYPE                       |String(255,0,0)        |PNH; Type materiaal; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None; Visible: Yes|
|ADRES                               |String(255,0,0)        |PNH; FK naar adres_tbl; ; Nullable: True; Default: None; Visible: No|
|INNETWERK                           |String(255,0,0)        |PNH; FK naar utiliteitsNet_tbl; ; Nullable: True; Default: None; Visible: No|
|INONDERZOEK                         |String(1,0,0)          |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible: No|
|TIJDSTIPREGISTRATIE                 |Date(8,0,0)            |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|EINDREGISTRATIE                     |Date(8,0,0)            |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|LV_PUBLICATIEDATUM                  |Date(8,0,0)            |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BERICHT_ID                          |String(128,0,0)        |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |String(255,0,0)        |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |String(255,0,0)        |PNH; Naam van gebruiker die de rij heeft aangemaakt; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)            |PNH; Aanmaakdatum; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)         |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)            |PNH; Datum van de laatste mutatie; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry(0,0,0)        |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|



***
