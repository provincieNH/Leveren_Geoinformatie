## AREAALDATA.kunstwerkVast_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ NEN 2767-4 / PNH
* __Positionele nauwkeurigheid:__ 5 cm
* __SHAPE:__ Punt
* __Definitie:__ Onderdeel van een civiel-technisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen. De NEN 2767-4 decompositie wordt gevolgd. 


Een vast kunstwerk is een beheerobject van het type:  

* Aquaducten
* Bruggen (vast)
* Duikers
* Gemalen
* Object Overstijgende Voorzieningen
* Onderdoorgangen
* Overkluizingen
* Sifons
* Spoorwegen
* Spuisluizen
* Tunnels
* Viaducten
* Wateren en watergangen (niet lijnvormig), overig
* Waterreguleringswerken
* Onbekend


***

|KOLOM                               |TYPE                   |DEFINITIE|
|------                              |----                   |-----    |
|OBJECTID                            |OID(38,0,0)            |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:Yes|
|GLOBALID                            |GlobalID(38,0,0)       |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:No|
|AD_ID                               |String(255,0,0)        |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None; Visible:Yes|
|GISIB_ID                            |Integer(0,10,0)        |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|IDENTIFICATIE                       |String(255,0,0)        |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None; Visible:No|
|VERWERKINGSSTATUS                   |String(255,0,0)        |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible:Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)            |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True; Visible:Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)            |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True; Visible:Yes|
|BEHEERDER                           |String(255,0,0)        |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible:Yes|
|ONDERHOUDER                         |String(255,0,0)        |PNH; Onderhouder van het object: kan meerdere door puntkomma gescheiden waardes bevatten; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible:No|
|EIGENAAR                            |String(255,0,0)        |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible:No|
|TYPESPEC                            |String(255,0,0)        |PNH; Nadere typering van het object; keuzelijst [typeSpecKWV]; Nullable: True; Default: None; Visible:Yes|
|TOPCODE                             |String(255,0,0)        |PNH; Topcode; keuzelijst [TOPCODE]; Nullable: True; Default: None; Visible:Yes|
|VERKEERSKLASSE                      |String(255,0,0)        |PNH; Verkeersklasse object; keuzelijst [VERKEERSKLASSE]; Nullable: True; Default: None; Visible:No|
|AANTALOVERSPANNING                  |SmallInteger(0,10,0)   |PNH; Aantal overspanningen; Nullable: True; Visible:Yes|
|BIJZONDERHEID                       |String(255,0,0)        |PNH; Extra toelichting; Nullable: True; Default: None; Visible:No|
|BOUWJAAR                            |SmallInteger(0,10,0)   |PNH; Bouwjaar; Nullable: True; Visible:No|
|CONFORMNEN                          |String(1,0,0)          |PNH; Indicatie of classificatie conform NEN is; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: O; Visible:No|
|OMSCHRIJVING                        |String(255,0,0)        |PNH; Extra toelichting; Nullable: True; Default: None; Visible:Yes|
|DOORRIJBREEDTERIJBAAN1              |Float(0,25,10)         |PNH; Doorrijbreedte rijbaan 1, Meetnauwkeurigheid +/- 1 cm; Nullable: True; Visible:No|
|DOORRIJBREEDTERIJBAAN2              |Float(0,25,10)         |PNH; Doorrijbreedte rijbaan 2, Meetnauwkeurigheid +/- 1 cm; Nullable: True; Visible:No|
|DOORRIJBREEDTERIJBAAN3              |Float(0,25,10)         |PNH; Doorrijbreedte rijbaan 3, Meetnauwkeurigheid +/- 1 cm; Nullable: True; Visible:No|
|DOORRIJHOOGTERIJST                  |Float(0,25,10)         |PNH; Doorrijbreedte rijstrook 1, Meetnauwkeurigheid +/- 1 cm; Nullable: True; Visible:Yes|
|DOORRIJHOOGTERIJST_1                |Float(0,25,10)         |PNH; Doorrijbreedte rijstrook 2, Meetnauwkeurigheid +/- 1 cm; Nullable: True; Visible:Yes|
|DOORRIJHOOGTERIJST_2                |Float(0,25,10)         |PNH; Doorrijbreedte rijstrook 3, Meetnauwkeurigheid +/- 1 cm; Nullable: True; Visible:Yes|
|DOORRIJHOOGTERIJST_3                |Float(0,25,10)         |PNH; Doorrijbreedte rijstrook 4, Meetnauwkeurigheid +/- 1 cm; Nullable: True; Visible:Yes|
|DOORRIJHOOGTERIJST_4                |Float(0,25,10)         |PNH; Doorrijbreedte rijstrook 5, Meetnauwkeurigheid +/- 1 cm; Nullable: True; Visible:Yes|
|DOORRIJHOOGTERIJST_5                |Float(0,25,10)         |PNH; Doorrijbreedte rijstrook 6, Meetnauwkeurigheid +/- 1 cm; Nullable: True; Visible:Yes|
|DOORVAARTBREEDTE1                   |Float(0,25,10)         |PNH; Doorvaartbreedte doorvaartopening 1, Meetnauwkeurigheid +/- 1 cm; Nullable: True; Visible:No|
|DOORVAARTBREEDTE2                   |Float(0,25,10)         |PNH; Doorvaartbreedte doorvaartopening 2, Meetnauwkeurigheid +/- 1 cm; Nullable: True; Visible:No|
|DOORVAARTBREEDTE3                   |Float(0,25,10)         |PNH; Doorvaartbreedte doorvaartopening 3, Meetnauwkeurigheid +/- 1 cm; Nullable: True; Visible:No|
|DOORVAARTBREEDTE4                   |Float(0,25,10)         |PNH; Doorvaartbreedte doorvaartopening 4, Meetnauwkeurigheid +/- 1 cm; Nullable: True; Visible:No|
|DOORVAARTBREEDTE5                   |Float(0,25,10)         |PNH; Doorvaartbreedte doorvaartopening 5, Meetnauwkeurigheid +/- 1 cm; Nullable: True; Visible:No|
|DOORVAARTHOOGTE1                    |Float(0,25,10)         |PNH; Doorvaarthoogtemaat doorvaartopening 1 (hoogte t.o.v. NAP, NIET t.o.v. actuele waterpeil), Meetnauwkeurigheid +/- 1 cm; Nullable: True; Visible:Yes|
|DOORVAARTHOOGTE2                    |Float(0,25,10)         |PNH; Doorvaarthoogtemaat doorvaartopening 2 (hoogte t.o.v. NAP, NIET t.o.v. actuele waterpeil), Meetnauwkeurigheid +/- 1 cm; Nullable: True; Visible:Yes|
|DOORVAARTHOOGTE3                    |Float(0,25,10)         |PNH; Doorvaarthoogtemaat doorvaartopening 3 (hoogte t.o.v. NAP, NIET t.o.v. actuele waterpeil), Meetnauwkeurigheid +/- 1 cm; Nullable: True; Visible:Yes|
|DOORVAARTHOOGTE4                    |Float(0,25,10)         |PNH; Doorvaarthoogtemaat doorvaartopening 4 (hoogte t.o.v. NAP, NIET t.o.v. actuele waterpeil), Meetnauwkeurigheid +/- 1 cm; Nullable: True; Visible:Yes|
|DOORVAARTHOOGTE5                    |Float(0,25,10)         |PNH; Doorvaarthoogtemaat doorvaartopening 5 (hoogte t.o.v. NAP, NIET t.o.v. actuele waterpeil), Meetnauwkeurigheid +/- 1 cm; Nullable: True; Visible:Yes|
|FOTO                                |String(255,0,0)        |PNH; Locatie van de foto op de S schijf bij PNH. Deze hoeft niet gevuld te worden door de aannemer. Nullable: True; Default: None; Visible:No|
|KWBREEDTE                           |Float(0,25,10)         |PNH; Breedte kunstwerk; Nullable: True; Visible:Yes|
|KWHOOGTE                            |Float(0,25,10)         |PNH; Hoogte kunstwerk; Nullable: True; Visible:Yes|
|KWLENGTE                            |Float(0,25,10)         |PNH; Totale lengte kunstwerk; Nullable: True; Visible:Yes|
|KWOPPERVLAKTE                       |Float(0,10,2)          |PNH; Totale oppervlakte kunstwerk; Nullable: True; Visible:No|
|NAAM                                |String(255,0,0)        |PNH; Naam van het kunstwerk; Nullable: True; Default: None; Visible:Yes|
|ONDERHOUDBIJZONDER                  |BLOB(60000,0,0)        |PNH; Bijzonderheden over onderhoud []; Nullable: True; Default: None; Visible:No|
|ONDERHOUDOPMERKING                  |BLOB(60000,0,0)        |PNH; Opmerkingen over het onderhoud []; Nullable: True; Default: None; Visible:No|
|OPLEGGINGAANTAL                     |SmallInteger(0,10,0)   |PNH; Aantal oplegblokken; Nullable: True; Visible:No|
|RENOVATIEJAAR                       |SmallInteger(0,10,0)   |PNH; Renovatiejaar; Nullable: True; Visible:No|
|TALUDBEKLEDINGOPPO                  |Float(0,25,10)         |PNH; Oppervlakte taludbekleding, m2, 2 decimalen; Nullable: True; Visible:No|
|VOEGOVERGANGENAANT                  |SmallInteger(0,10,0)   |PNH; Aantal voegovergangen; Nullable: True; Visible:No|
|VOEGOVERGANGENTOTA                  |Float(0,25,10)         |PNH; Totale lengte voegovergangen; Nullable: True; Visible:No|
|BEHEEROBJECTSUBTYP                  |String(255,0,0)        |PNH; Beheerobject subtype; keuzelijst [BEHEER_OBJECT_SUBTYPE]; Nullable: True; Default: None; Visible:Yes|
|GEMEENTE                            |String(255,0,0)        |PNH; Gemeente naam; keuzelijst [GEMEENTE]; Nullable: True; Default: None; Visible:No|
|GEDEELDBEHEER                       |String(255,0,0)        |PNH; Indien van toepassing, tweede beheerder van het object; keuzelijst [GEDEELD_BEHEER]; Nullable: True; Default: None; Visible:No|
|LEVENSCYCLUS                        |String(255,0,0)        |PNH; Levenscyclus; keuzelijst [LEVENSCYCLUS]; Nullable: True; Default: None; Visible:No|
|CONDITIESCORE                       |Integer(0,10,0)        |PNH; Conditiescore conform NEN 2767-4; Nullable: True; Default: None; Visible:No|
|CONDITIESCORE_DATUM                 |Date(8,0,0)            |PNH; Datum opname Conditiescore; Nullable: True; Visible:No|
|RELATIEVEHOOGTELIGGING              |SmallInteger(0,10,0)   |BGT; Aanduiding voor de relatieve hoogte van het object; Nullable: False; Default: 0; Visible:Yes|
|MONUMENT                            |String(255,0,0)        |PNH; Monumentale status; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: None; Visible:No|
|NENBEHEEROBJECT                     |String(255,0,0)        |PNH; NENBEHEEROBJECT; keuzelijst [NENBEHEEROBJECT]; Nullable: True; Default: None; Visible:Yes|
|SCHOTBALKAANWEZIG                   |String(1,0,0)          |PNH; Schotbalk aanwezig; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: O; Visible:No|
|TYPEVOEGOVERGANG                    |String(255,0,0)        |PNH; Type voegovergang object; keuzelijst [TYPE_VOEGOVERGANG]; Nullable: True; Default: None; Visible:No|
|TRAJECT                             |String(255,0,0)        |PNH; FK naar traject_v; Nullable: True; Default: None; Visible:Yes|
|TRAJECT2                            |String(255,0,0)        |PNH; Foreign Key naar traject_v, in het geval van een tweede traject; Nullable: True; Default: None; Visible:Yes|
|ADRES                               |String(255,0,0)        |PNH; FK naar adres_tbl; Nullable: True; Default: None; Visible:No|
|DATALEVERANCIER                     |String(255,0,0)        |PNH; Leverancier van de data; Nullable: True; Default: None; Visible:No|
|CREATED_USER                        |String(255,0,0)        |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None; Visible:No|
|CREATED_DATE                        |Date(8,0,0)            |PNH; Aanmaakdatum; Nullable: True; Visible:No|
|LAST_EDITED_USER                    |String(50,0,0)         |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None; Visible:No|
|LAST_EDITED_DATE                    |Date(8,0,0)            |PNH; Datum van de laatste mutatie; Nullable: True; Visible:No|
|SHAPE                               |Geometry               |PNH; Punt; Visible:Yes|


***
