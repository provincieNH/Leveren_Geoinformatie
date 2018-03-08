## AREAALDATA.kunstwerkdeel_l

$ Feature dataset: Inrichtend

* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ IMGeo BGT 
* __Positionele nauwkeurigheid:__ 5 cm
* __Geometrie:__ Lijn
* __Definitie:__ Onderdeel van een civiel-technisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen.

***

|KOLOM                             |TYPE          	        |DEFINITIE|
|------                            |----          	        |-----    |
|OBJECTID                          |OID(38,0,0)             |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None|
|GLOBALID                          |GlobalID(38,0,0)        |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None|
|AD_ID                             |String(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None|
|GISIB_ID                          |Integer(0,10,0)         |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None|
|IDENTIFICATIE                     |String(255,0,0)         |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None|
|VERWERKINGSSTATUS                 |String(255,0,0)         |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|STATUS                            |String(10,0,0)          |BGT; BGT status van het object; keuzelijst [status]; Nullable: False; Default: bestaand|
|OBJECTBEGINTIJD                   |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                    |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|RELATIEVEHOOGTELIGGING            |SmallInteger(0,10,0)    |BGT; Aanduiding voor de relatieve hoogte van het object; Nullable: False; Default: 0|
|BEHEERDER                         |String(255,0,0)         |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None|
|ONDERHOUDER                       |String(255,0,0)         |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None|
|EIGENAAR                          |String(255,0,0)         |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None|
|BRONHOUDER                        |String(5,0,0)           |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None|
|TYPESPEC                          |String(255,0,0)         |PNH; Nadere typering van het object; keuzelijst [typeSpecKWDLijn]; Nullable: True; Default: None|
|BGTPLUSTYPE                       |String(50,0,0)          |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeKWDLijn]; Nullable: False; Default: None|
|BIJZONDERHEID                     |String(255,0,0)         |PNH; Extra toelichting; Nullable: True; Default: None|
|CONFORMNEN                        |String(1,0,0)           |PNH; Indicatie of classificatie conform NEN is; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: O|
|OMSCHRIJVING                      |String(255,0,0)         |PNH; Extra toelichting; Nullable: True; Default: None|
|KILOMETRERING                     |Float(0,25,10)          |PNH; Aanduiding Kilometrering ligging kunstwerk; Nullable: True|
|KWLENGTE                          |Float(0,25,10)          |PNH; PNH; Totale lengte kunstwerk; Nullable: True|
|RENOVATIEJAAR                     |SmallInteger(0,10,0)    |PNH; Renovatiejaar; Nullable: True; Default: None |
|DIAMETER                          |SmallInteger(0,10,0)    |PNH; Diameter (mm); indien ronde duiker ; Nullable: True|
|HOOGTE                            |Float(0,10,2)           |PNH; Hoogte (m, 2 decimalen); indien rechthoekige duiker; Nullable: True|
|BREEDTE                           |Float(0,10,2)           |PNH; Breedte (m, 2 decimalen); indien rechthoekige duiker; Nullable: True|
|PROFIEL                           |String(255,0,0)         |PNH; Vorm doorstroomprofiel van duiker; keuzelijst [PROFIEL]; Nullable: True; Default: None|
|BOUWJAAR                          |SmallInteger(0,10,0)    |PNH; Bouwjaar; Nullable: True|
|MATERIAALTYPE                     |String(255,0,0)         |PNH; Materiaaltype; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None|
|GEMEENTE                          |String(255,0,0)         |PNH; Gemeente naam; keuzelijst [GEMEENTE]; Nullable: True; Default: None|
|LEVENSCYCLUS                      |String(255,0,0)         |PNH; Levenscyclus; keuzelijst [LEVENSCYCLUS]; Nullable: True; Default: None|
|NENBEHEEROBJECT                   |String(255,0,0)         |PNH; NENBEHEEROBJECT; Nullable: True; Default: None|
|DUIKERBINNENONDERK                |Float(0,25,10)          |PNH; Hoogte t.o.v. NAP van binnen onderkant buis (bij duiker); Nullable: True|
|GEDEELDBEHEER                     |String(255,0,0)         |PNH; Indien van toepassing, tweede beheerder van het object; keuzelijst [GEDEELD_BEHEER]; Nullable: True; Default: None|
|VAARWEG                           |String(255,0,0)         |PNH; FK naar vaarweg_l; Nullable: True; Default: None|
|TRAJECT                           |String(255,0,0)         |PNH; FK naar traject_v; Nullable: True; Default: None|
|DATALEVERANCIER                   |String(255,0,0)         |PNH; Leverancier van de data; Nullable: True; Default: None|
|INONDERZOEK                       |String(1,0,0)           |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible:No|
|TIJDSTIPREGISTRATIE               |Date(8,0,0)             |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|EINDREGISTRATIE                   |Date(8,0,0)             |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|LV_PUBLICATIEDATUM                |Date(8,0,0)             |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|BERICHT_ID                        |String(128,0,0)         |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|CREATED_USER                      |String(255,0,0)         |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                      |Date(8,0,0)             |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                  |String(50,0,0)          |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                  |Date(8,0,0)             |PNH; Datum van de laatste mutatie; Nullable: True|
|SHAPE                             |Geometry(0,0,0)         |PNH; Lijn|
|SHAPE_Length                      |Double(0,0,0)           |PNH; Lengte in meters, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None|


***
