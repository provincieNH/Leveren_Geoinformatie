## AREAALDATA.kunstwerkBeweegbaar_p

$ Feature dataset: Inrichtend


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ NEN 2767-4 / PNH
* __Positionele nauwkeurigheid:__ 5 cm
* __SHAPE:__ Punt
* __Definitie:__ Onderdeel van een civiel-technisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen. De NEN 2767-4 decompositie wordt gevolgd. 

Een Beweegbaar kunstwerk is een beheerobject van het type:  

* Bruggen (beweegbaar)


***

|KOLOM                               |TYPE                    |DEFINITIE|
|------                              |----                    |-----    |
|OBJECTID                            |OID(38,0,0)             |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None|
|GLOBALID                            |GlobalID(38,0,0)        |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None|
|AD_ID                               |String(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None|
|GISIB_ID                            |Integer(0,10,0)         |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None|
|IDENTIFICATIE                       |String(255,0,0)         |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)         |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|OBJECTBEGINTIJD                     |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|RELATIEVEHOOGTELIGGING              |SmallInteger(0,10,0)    |PNH; Aanduiding voor de relatieve hoogte van het object; Nullable: False;; Default: 0|
|BEHEERDER                           |String(255,0,0)         |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None|
|ONDERHOUDER                         |String(255,0,0)         |PNH; Onderhouder van het object: kan meerdere door puntkomma gescheiden waardes bevatten; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None|
|EIGENAAR                            |String(255,0,0)         |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None|
|TYPESPEC                            |String(255,0,0)         |PNH; Nadere typering van het object; keuzelijst [typeSpecKWB]; Nullable: True; Default: None|
|TOPCODE                             |String(10,0,0)          |PNH; Topcode. De aannemer mag dit niet invullen; keuzelijst [TOPCODE]; Nullable: False; Default: None|
|VERKEERSKLASSE                      |String(255,0,0)         |PNH; Verkeersklasse object; keuzelijst [VERKEERSKLASSE]; Nullable: True; Default: None|
|AANTALOVERSPANNING                  |SmallInteger(0,10,0)    |PNH; Aantal overspanningen; Nullable: True|
|BIJZONDERHEID                       |String(255,0,0)         |PNH; Extra toelichting; Nullable: True; Default: None|
|BOUWJAARBEWEGINGSW                  |SmallInteger(0,10,0)    |PNH; Bouwjaar Bewegingswerk; Nullable: True; Default: None|
|BOUWJAARBOVENBOUW                   |SmallInteger(0,10,0)    |PNH; Bouwjaar Bovenbouw; Nullable: True|
|BOUWJAARELECTRISCH                  |SmallInteger(0,10,0)    |PNH; Bouwjaar Electrische Installatie; Nullable: True|
|BOUWJAARHYDRAULISC                  |String(255,0,0)         |PNH; Bouwjaar Hydraulische Installatie; Nullable: True; Default: None|
|BOUWJAARONDERBOUW                   |SmallInteger(0,10,0)    |PNH; Bouwjaar Onderbouw; Nullable: True|
|BOUWJAARVAL                         |SmallInteger(0,10,0)    |PNH; Bouwjaar Val; Nullable: True|
|CONFORMNEN                          |String(1,0,0)           |PNH; Indicatie of classificatie conform NEN is: Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: O|
|OMSCHRIJVING                        |String(255,0,0)         |PNH; Extra toelichting; Nullable: True; Default: None|
|DOORRIJBREEDTERIJBAAN1              |Float(0,25,10)          |PNH; Doorrijbreedte rijbaan 1, Meetnauwkeurigheid +/- 1 cm; Nullable: True|
|DOORRIJBREEDTERIJBAAN2              |Float(0,25,10)          |PNH; Doorrijbreedte rijbaan 2, Meetnauwkeurigheid +/- 1 cm; Nullable: True|
|DOORRIJBREEDTERIJBAAN3              |Float(0,25,10)          |PNH; Doorrijbreedte rijbaan 3, Meetnauwkeurigheid +/- 1 cm; Nullable: True|
|DOORRIJHOOGTERIJST                  |Float(0,25,10)          |PNH; Doorrijbreedte rijstrook 1, Meetnauwkeurigheid +/- 1 cm; Nullable: True|
|DOORRIJHOOGTERIJST_1                |Float(0,25,10)          |PNH; Doorrijbreedte rijstrook 2, Meetnauwkeurigheid +/- 1 cm; Nullable: True|
|DOORRIJHOOGTERIJST_2                |Float(0,25,10)          |PNH; Doorrijbreedte rijstrook 3, Meetnauwkeurigheid +/- 1 cm; Nullable: True|
|DOORRIJHOOGTERIJST_3                |Float(0,25,10)          |PNH; Doorrijbreedte rijstrook 4, Meetnauwkeurigheid +/- 1 cm; Nullable: True|
|DOORRIJHOOGTERIJST_4                |Float(0,25,10)          |PNH; Doorrijbreedte rijstrook 5, Meetnauwkeurigheid +/- 1 cm; Nullable: True|
|DOORRIJHOOGTERIJST_5                |Float(0,25,10)          |PNH; Doorrijbreedte rijstrook 6, Meetnauwkeurigheid +/- 1 cm; Nullable: True|
|DOORVAARTBREEDTE1                   |Float(0,25,10)          |PNH; Doorvaartbreedte doorvaartopening 1, Meetnauwkeurigheid +/- 1 cm; Nullable: True|
|DOORVAARTBREEDTE2                   |Float(0,25,10)          |PNH; Doorvaartbreedte doorvaartopening 2, Meetnauwkeurigheid +/- 1 cm; Nullable: True|
|DOORVAARTBREEDTE3                   |Float(0,25,10)          |PNH; Doorvaartbreedte doorvaartopening 3, Meetnauwkeurigheid +/- 1 cm; Nullable: True|
|DOORVAARTBREEDTE4                   |Float(0,25,10)          |PNH; Doorvaartbreedte doorvaartopening 4, Meetnauwkeurigheid +/- 1 cm; Nullable: True|
|DOORVAARTBREEDTE5                   |Float(0,25,10)          |PNH; Doorvaartbreedte doorvaartopening 5, Meetnauwkeurigheid +/- 1 cm; Nullable: True|
|DOORVAARTHOOGTE1                    |Float(0,25,10)          |PNH; Doorvaarthoogtemaat doorvaartopening 1 (hoogte t.o.v. NAP, NIET t.o.v. actuele waterpeil), Meetnauwkeurigheid +/- 1 cm; Nullable: True|
|DOORVAARTHOOGTE2                    |Float(0,25,10)          |PNH; Doorvaarthoogtemaat doorvaartopening 2 (hoogte t.o.v. NAP, NIET t.o.v. actuele waterpeil), Meetnauwkeurigheid +/- 1 cm; Nullable: True|
|DOORVAARTHOOGTE3                    |Float(0,25,10)          |PNH; Doorvaarthoogtemaat doorvaartopening 3 (hoogte t.o.v. NAP, NIET t.o.v. actuele waterpeil), Meetnauwkeurigheid +/- 1 cm; Nullable: True|
|DOORVAARTHOOGTE4                    |Float(0,25,10)          |PNH; Doorvaarthoogtemaat doorvaartopening 4 (hoogte t.o.v. NAP, NIET t.o.v. actuele waterpeil), Meetnauwkeurigheid +/- 1 cm; Nullable: True|
|DOORVAARTHOOGTE5                    |Float(0,25,10)          |PNH; Doorvaarthoogtemaat doorvaartopening 5 (hoogte t.o.v. NAP, NIET t.o.v. actuele waterpeil), Meetnauwkeurigheid +/- 1 cm; Nullable: True|
|FOTO                                |String(255,0,0)         |PNH; Locatie van de foto op de S schijf bij PNH. Deze hoeft niet gevuld te worden door de aannemer. Nullable: True; Default: None|
|INBOUWJAARPLC                       |SmallInteger(0,10,0)    |PNH; Inbouwjaar PLC; Nullable: True|
|INSPECTIEJAARCMEH                   |SmallInteger(0,10,0)    |PNH; Inspectie jaar CMEH Installaties; Nullable: True|
|INSPECTIEJAARHEFKA                  |SmallInteger(0,10,0)    |PNH; Inspectie jaar Hefkabels; Nullable: True|
|KWBREEDTE                           |Float(0,25,10)          |PNH; Breedte kunstwerk; Nullable: True|
|KWHOOGTE                            |Float(0,25,10)          |PNH; Hoogte kunstwerk; Nullable: True|
|KWLENGTE                            |Float(0,25,10)          |PNH; Totale lengte kunstwerk; Nullable: True|
|KWOPPERVLAKTE                       |Float(0,25,10)          |PNH; Oppervlakte van het kunstwerk in m2, afgerond op 2 decimalen; Nullable: True; Default: None|
|NAAM                                |String(255,0,0)         |PNH; Naam van het kunstwerk; Nullable: True; Default: None|
|ONDERHOUDBIJZONDER                  |BLOB(60000,0,0)         |PNH; Bijzonderheden over onderhoud; Nullable: True; Default: None|
|ONDERHOUDOPMERKING                  |BLOB(60000,0,0)         |PNH; Opmerkingen over het onderhoud; Nullable: True; Default: None|
|OPLEGGINGAANTAL                     |SmallInteger(0,10,0)    |PNH; Aantal oplegblokken; Nullable: True|
|BOUWJAARREMMINGSWERK                |SmallInteger(0,10,0)    |PNH; Vervangingsjaar Remwerk; Nullable: True; Default: None|
|VOEGOVERGANGENAANT                  |SmallInteger(0,10,0)    |PNH; Aantal voegovergangen; Nullable: True|
|VOEGOVERGANGENTOTA                  |Float(0,25,10)          |PNH; Totale lengte voegovergangen; Nullable: True|
|WACHTPLAATSVERVANG                  |SmallInteger(0,10,0)    |PNH; Vervangingsjaar wachtplaats; Nullable: True|
|GEMEENTE                            |String(255,0,0)         |PNH; Gemeente naam; keuzelijst [GEMEENTE]; Nullable: True; Default: None|
|GEDEELDBEHEER                       |String(255,0,0)         |PNH; Indien van toepassing, tweede beheerder van het object; keuzelijst [GEDEELD_BEHEER]; Nullable: True; Default: None|
|LEVENSCYCLUS                        |String(255,0,0)         |PNH; Levenscyclus; keuzelijst [LEVENSCYCLUS]; Nullable: True; Default: None|
|MONUMENT                            |String(20,0,0)          |PNH; Monumentale status; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: None|
|NENBEHEEROBJECT                     |String(255,0,0)         |PNH; NENBEHEEROBJECT; keuzelijst [NENBEHEEROBJECT]; Nullable: True; Default: None|
|SCHOTBALKAANWEZIG                   |String(1,0,0)           |PNH; Schotbalk aanwezig; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: None|
|ARBO_RIE_UITGEVOERD                 |Date(8,0,0)             |PNH; Laatst uitgevoerde RIE (datum); Nullable: True|
|ARBO_RIE_GEPLAND                    |Date(8,0,0)             |PNH; Volgende geplande RIE (datum); Nullable: True|
|CE_MARKERING                        |String(1,0,0)           |PNH; CE markering: Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: O|
|CE_MARKERING_DATUM                  |Date(8,0,0)             |PNH; CE markering sinds (datum); Nullable: True|
|AFSTANDSBEDIENING                   |String(1,0,0)           |PNH; Afstandsbediening (Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: O|
|CONDITIESCORE                       |Integer(0,10,0)         |PNH; Conditiescore conform NEN 2767-4; Nullable: True; Default: None|
|CONDITIESCORE_DATUM                 |Date(8,0,0)             |PNH; Datum opname Conditiescore; Nullable: True|
|TRAJECT                             |String(255,0,0)         |PNH; FK naar traject_v; Nullable: True; Default: None|
|TRAJECT2                            |String(255,0,0)         |PNH; Foreign Key naar traject_v, in het geval van een tweede traject; Nullable: True; Default: None|
|VAARWEGDEELTRAJECT                  |String(255,0,0)         |PNH; FK naar vaarwegdeeltraject_v; Nullable: True; Default: None|
|ADRES                               |String(255,0,0)         |PNH; FK naar adres_tbl; Nullable: True; Default: None|
|DATALEVERANCIER                     |String(255,0,0)         |PNH; Leverancier van de data; Nullable: True; Default: None|
|CREATED_USER                        |String(255,0,0)         |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)             |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)          |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)             |PNH; Datum van de laatste mutatie; Nullable: True|
|SHAPE                               |Geometry                |PNH; Punt|


***

