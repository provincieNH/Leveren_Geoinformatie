## AREAALDATA.kunstwerkdeel_l

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ IMGeo BGT 
* __Positionele nauwkeurigheid:__ 5 cm
* __Geometrie:__ Lijn
* __Definitie:__ Onderdeel van een civiel-technisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen.

***

|KOLOM                             |TYPE          	        |DEFINITIE|
|------                            |----          	        |-----    |
|OBJECTID                          |OID(38,0,0)             |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:Yes|
|GLOBALID                          |GlobalID(38,0,0)        |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:Yes|
|AD_ID                             |String(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None; Visible:Yes|
|GISIB_ID                          |Integer(0,10,0)         |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|IDENTIFICATIE                     |String(255,0,0)         |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None; Visible:No|
|VERWERKINGSSTATUS                 |String(255,0,0)         |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible:Yes|
|STATUS                            |String(10,0,0)          |BGT; BGT status van het object; keuzelijst [status]; Nullable: False; Default: bestaand; Visible:No|
|OBJECTBEGINTIJD                   |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True; Visible:Yes|
|OBJECTEINDTIJD                    |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True; Visible:Yes|
|RELATIEVEHOOGTELIGGING            |SmallInteger(0,10,0)    |BGT; Aanduiding voor de relatieve hoogte van het object; Nullable: False; Default: 0; Visible:Yes|
|BEHEERDER                         |String(255,0,0)         |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible:Yes|
|ONDERHOUDER                       |String(255,0,0)         |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible:No|
|EIGENAAR                          |String(255,0,0)         |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible:No|
|BRONHOUDER                        |String(5,0,0)           |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None; Visible:No|
|TYPESPEC                          |String(255,0,0)         |PNH; Nadere typering van het object; keuzelijst [typeSpecKWDLijn]; Nullable: True; Default: None; Visible:Yes|
|BGTPLUSTYPE                       |String(50,0,0)          |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeKWDLijn]; Nullable: False; Default: None; Visible:No|
|BIJZONDERHEID                     |String(255,0,0)         |PNH; Extra toelichting; Nullable: True; Default: None; Visible:No|
|CONFORMNEN                        |String(1,0,0)           |PNH; Indicatie of classificatie conform NEN is; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: O; Visible:No|
|OMSCHRIJVING                      |String(255,0,0)         |PNH; Extra toelichting; Nullable: True; Default: None; Visible:Yes|
|KILOMETRERING                     |Float(0,25,10)          |PNH; Aanduiding Kilometrering ligging kunstwerk; Nullable: True; Visible:Yes|
|KWLENGTE                          |Float(0,25,10)          |PNH; PNH; Totale lengte kunstwerk; Nullable: True; Visible:Yes|
|RENOVATIEJAAR                     |SmallInteger(0,10,0)    |PNH; Renovatiejaar; Nullable: True; Default: None ; Visible:No|
|DIAMETER                          |SmallInteger(0,10,0)    |PNH; Diameter (mm); indien ronde duiker ; Nullable: True; Visible:Yes|
|HOOGTE                            |Float(0,10,2)           |PNH; Hoogte (m, 2 decimalen); indien rechthoekige duiker; Nullable: True; Visible:Yes|
|BREEDTE                           |Float(0,10,2)           |PNH; Breedte (m, 2 decimalen); indien rechthoekige duiker; Nullable: True; Visible:No|
|PROFIEL                           |String(255,0,0)         |PNH; Vorm doorstroomprofiel van duiker; keuzelijst [PROFIEL]; Nullable: True; Default: None; Visible:No|
|BOUWJAAR                          |SmallInteger(0,10,0)    |PNH; Bouwjaar; Nullable: True; Visible:No|
|MATERIAALTYPE                     |String(255,0,0)         |PNH; Materiaaltype; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None; Visible:Yes|
|GEMEENTE                          |String(255,0,0)         |PNH; Gemeente naam; keuzelijst [GEMEENTE]; Nullable: True; Default: None; Visible:No|
|LEVENSCYCLUS                      |String(255,0,0)         |PNH; Levenscyclus; keuzelijst [LEVENSCYCLUS]; Nullable: True; Default: None; Visible:No|
|NENBEHEEROBJECT                   |String(255,0,0)         |PNH; NENBEHEEROBJECT; Nullable: True; Default: None; Visible:Yes|
|DUIKERBINNENONDERK                |Float(0,25,10)          |PNH; Hoogte t.o.v. NAP van binnen onderkant buis (bij duiker); Nullable: True; Visible:No|
|GEDEELDBEHEER                     |String(255,0,0)         |PNH; Indien van toepassing, tweede beheerder van het object; keuzelijst [GEDEELD_BEHEER]; Nullable: True; Default: None; Visible:No|
|VAARWEG                           |String(255,0,0)         |PNH; FK naar vaarweg_l; Nullable: True; Default: None; Visible:No|
|TRAJECT                           |String(255,0,0)         |PNH; FK naar traject_v; Nullable: True; Default: None; Visible:Yes|
|DATALEVERANCIER                   |String(255,0,0)         |PNH; Leverancier van de data; Nullable: True; Default: None; Visible:No|
|INONDERZOEK                       |String(1,0,0)           |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible:No|
|TIJDSTIPREGISTRATIE               |Date(8,0,0)             |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|EINDREGISTRATIE                   |Date(8,0,0)             |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|LV_PUBLICATIEDATUM                |Date(8,0,0)             |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|BERICHT_ID                        |String(128,0,0)         |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|CREATED_USER                      |String(255,0,0)         |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None; Visible:No|
|CREATED_DATE                      |Date(8,0,0)             |PNH; Aanmaakdatum; Nullable: True; Visible:No|
|LAST_EDITED_USER                  |String(50,0,0)          |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None; Visible:No|
|LAST_EDITED_DATE                  |Date(8,0,0)             |PNH; Datum van de laatste mutatie; Nullable: True; Visible:No|
|SHAPE                             |Geometry(0,0,0)         |PNH; Lijn; Visible:Yes|
|SHAPE_Length                      |Double(0,0,0)           |PNH; Lengte in meters, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None; Visible:Yes|


***
