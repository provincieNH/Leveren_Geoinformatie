## AREAALDATA.straatmeubilairLichtpunt_p

$ Feature dataset: Inrichtend

* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ in afwijking op de BGT/IMGEO indeling worden lichtpunten in dit objecttype geadministreerd. Het betreft hier armaturen en markeringsunits.

***

|KOLOM                               |TYPE          	         |DEFINITIE|
|------                              |----          	         |-----    |
|OBJECTID                            |OID(38,0,0)                |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None|
|GLOBALID                            |GlobalID(38,0,0)           |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None|
|AD_ID                               |String(255,0,0)            |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None|
|GISIB_ID                            |Integer(0,10,0)            |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None
|IDENTIFICATIE                       |String(255,0,0)            |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None|
|STATUS                              |String(10,0,0)             |BGT; BGT status van het object; keuzelijst [status]; Nullable: False; Default: bestaand|
|VERWERKINGSSTATUS                   |String(255,0,0)            |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|OBJECTBEGINTIJD                     |Date(8,0,0)                |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)                |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|RELATIEVEHOOGTELIGGING              |SmallInteger(0,10,0)       |BGT; Aanduiding voor de relatieve hoogte van het object; Nullable: False; Default: 0|
|BEHEERDER                           |String(255,0,0)            |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None|
|ONDERHOUDER                         |String(255,0,0)            |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None|
|EIGENAAR                            |String(255,0,0)            |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None|
|BRONHOUDER                          |String(5,0,0)              |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None|
|TYPESPEC                            |String(255,0,0)            |PNH; Nadere typering van het object; keuzelijst [typeSpecSTMLichtpunt]; Nullable: True; Default: None|
|BGTPLUSTYPE                         |String(50,0,0)             |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeSTM]; Nullable: False; Default: None|
|FABRIKANTTYPECODE                   |String(255,0,0)            |PNH; Fabrikanttypecode; keuzelijst [FABRIKANT_TYPECODE]; Nullable: True; Default: None|
|DATUMPLAATSING                      |Date(8,0,0)                |PNH; Datum plaatsing; Nullable: True|
|OMSCHRIJVING                        |String(255,0,0)            |PNH; Extra toelichting; Nullable: True; Default: None|
|HOOGTE                              |Float(0,10,0)              |PNH; Hoogte van het lichtpunt in meter; Nullable: True|
|LEVENSVERWACHTING                   |SmallInteger(0,10,0)       |PNH; Levensverwachting; Nullable: True|
|LICHTPUNTNUMMER                     |String(255,0,0)            |PNH; Lichtpuntnummer ; Nullable: True; Default: None|
|PLANJAAR                            |SmallInteger(0,10,0)       |PNH; Planjaar; Nullable: True|
|RESTLEVENSDUUR                      |SmallInteger(0,10,0)       |PNH; Restlevensduur in maanden; Nullable: True; Default: None|
|DIMSYSTEEM                          |String(1,0,0)              |PNH; Dimsysteem: Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: O|
|RICHTING                            |String(255,0,0)            |PNH; TODO; Nullable: True; Default: None|
|FABRIKANTTYPECODE                   |String(255,0,0)            |PNH; Fabrikanttypecode; keuzelijst [FABRIKANT_TYPECODE]; Nullable: True; Default: None|
|SOORT_ENERGIE                       |String(10,0,0)             |PNH; Soort energie; keuzelijst [SOORT_ENERGIE]; Nullable: True; Default: None|
|AANSLUITING_ADERGROEP               |String(255,0,0)            |PNH; Omschrijving op welke adergroep lamp is aangesloten bv L2-12L125-GR1; Nullable: True; Default: None|
|INNETWERK                           |String(255,0,0)            |PNH; FK naar utiliteitsNet_tbl; Nullable: True; Default: None|
|UITLEGGERPORTAAL                    |String(255,0,0)            |PNH; FK naar uitleggerPortaal_l; als armatuur daarop is gemonteerd; Nullable: True; Default: None|
|PAAL                                |String(255,0,0)            |PNH; FK naar paalDraagconstructie_p; Nullable: True; Default: None|
|INONDERZOEK                         |String(1,0,0)              |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible:No|
|TIJDSTIPREGISTRATIE                 |Date(8,0,0)                |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|EINDREGISTRATIE                     |Date(8,0,0)                |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|LV_PUBLICATIEDATUM                  |Date(8,0,0)                |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|BERICHT_ID                          |String(128,0,0)            |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|DATALEVERANCIER                     |String(255,0,0)            |PNH; Leverancier van de data; Nullable: True; Default: None|
|CREATED_USER                        |String(255,0,0)            |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)                |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)             |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)                |PNH; Datum van de laatste mutatie; Nullable: True|
|SHAPE                               |Geometry(0,0,0)            |PNH; Punt|


***
