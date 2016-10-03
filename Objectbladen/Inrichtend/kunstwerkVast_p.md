## AREAALDATA.kunstwerkVast_p

$ Feature dataset: Inrichtend


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

|KOLOM                               |TYPE              |DEFINITIE|
|------                              |----              |-----    |
|TOPCODE                             |String(255,0,0)     |Topcode, keuzelijst [TOPCODE] - Nullable: True Default: None|
|VERKEERSKLASSE                      |String(255,0,0)     |Verkeersklasse object, keuzelijst [VERKEERSKLASSE] - Nullable: True Default: None|
|AANTALOVERSPANNING                  |SmallInteger(0,10,0)|Aantal overspanningen - Nullable: True|
|BIJZONDERHEID                       |String(255,0,0)     |Extra toelichting - Nullable: True Default: None|
|BOUWJAAR                            |SmallInteger(0,10,0)|Bouwjaar - Nullable: True|
|CONFORMNEN                          |String(1,0,0)       |Indicatie of classificatie conform NEN is, keuzelijst [jaNeeOnbekend] - Nullable: True Default: O|
|CONSERVERINGOPPERV                  |SmallInteger(0,10,0)|Soort Oppervlakte conservering toegepast - Nullable: True|
|CONSERVERINGVERVAN                  |SmallInteger(0,10,0)|TODO - Nullable: True|
|OMSCHRIJVING                        |String(255,0,0)    |Extra toelichting - Nullable: True Default: None|
|DOORRIJBREEDTERIJBAAN1              |Float(0,25,10)     |Doorrijbreedte rijbaan 1, Meetnauwkeurigheid +/- 1 cm - Nullable: True|
|DOORRIJBREEDTERIJBAAN2              |Float(0,25,10)     |Doorrijbreedte rijbaan 2, Meetnauwkeurigheid +/- 1 cm - Nullable: True|
|DOORRIJBREEDTERIJBAAN3              |Float(0,25,10)     |Doorrijbreedte rijbaan 3, Meetnauwkeurigheid +/- 1 cm - Nullable: True|
|DOORRIJHOOGTERIJST                  |Float(0,25,10)     |Doorrijbreedte rijstrook 1, Meetnauwkeurigheid +/- 1 cm - Nullable: True|
|DOORRIJHOOGTERIJST_1                |Float(0,25,10)     |Doorrijbreedte rijstrook 2, Meetnauwkeurigheid +/- 1 cm - Nullable: True|
|DOORRIJHOOGTERIJST_2                |Float(0,25,10)     |Doorrijbreedte rijstrook 3, Meetnauwkeurigheid +/- 1 cm - Nullable: True|
|DOORRIJHOOGTERIJST_3                |Float(0,25,10)     |Doorrijbreedte rijstrook 4, Meetnauwkeurigheid +/- 1 cm - Nullable: True|
|DOORRIJHOOGTERIJST_4                |Float(0,25,10)     |Doorrijbreedte rijstrook 5, Meetnauwkeurigheid +/- 1 cm - Nullable: True|
|DOORRIJHOOGTERIJST_5                |Float(0,25,10)     |Doorrijbreedte rijstrook 6, Meetnauwkeurigheid +/- 1 cm - Nullable: True|
|DOORVAARTBREEDTE1                   |Float(0,25,10)      |Doorvaartbreedte doorvaartopening 1, Meetnauwkeurigheid +/- 1 cm - Nullable: True|
|DOORVAARTBREEDTE2                   |Float(0,25,10)      |Doorvaartbreedte doorvaartopening 2, Meetnauwkeurigheid +/- 1 cm - Nullable: True|
|DOORVAARTBREEDTE3                   |Float(0,25,10)      |Doorvaartbreedte doorvaartopening 3, Meetnauwkeurigheid +/- 1 cm - Nullable: True|
|DOORVAARTBREEDTE4                   |Float(0,25,10)      |Doorvaartbreedte doorvaartopening 4, Meetnauwkeurigheid +/- 1 cm - Nullable: True|
|DOORVAARTBREEDTE5                   |Float(0,25,10)      |Doorvaartbreedte doorvaartopening 5, Meetnauwkeurigheid +/- 1 cm - Nullable: True|
|DOORVAARTHOOGTE1                    |Float(0,25,10)      |Doorvaarthoogtemaat doorvaartopening 1 (hoogte t.o.v. NAP, NIET t.o.v. actuele waterpeil), Meetnauwkeurigheid +/- 1 cm - Nullable: True|
|DOORVAARTHOOGTE2                    |Float(0,25,10)      |Doorvaarthoogtemaat doorvaartopening 2 (hoogte t.o.v. NAP, NIET t.o.v. actuele waterpeil), Meetnauwkeurigheid +/- 1 cm - Nullable: True|
|DOORVAARTHOOGTE3                    |Float(0,25,10)      |Doorvaarthoogtemaat doorvaartopening 3 (hoogte t.o.v. NAP, NIET t.o.v. actuele waterpeil), Meetnauwkeurigheid +/- 1 cm - Nullable: True|
|DOORVAARTHOOGTE4                    |Float(0,25,10)      |Doorvaarthoogtemaat doorvaartopening 4 (hoogte t.o.v. NAP, NIET t.o.v. actuele waterpeil), Meetnauwkeurigheid +/- 1 cm - Nullable: True|
|DOORVAARTHOOGTE5                    |Float(0,25,10)      |Doorvaarthoogtemaat doorvaartopening 5 (hoogte t.o.v. NAP, NIET t.o.v. actuele waterpeil), Meetnauwkeurigheid +/- 1 cm - Nullable: True|
|DUIKERBINNENONDERK                  |Float(0,25,10)      |Hoogte t.o.v. NAP van binnen onderkant buis (bij duiker) - Nullable: True|
|DUIKERDOORSTROOMPR                  |String(255,0,0)     |Doorstroomprofiel type(bij duiker) - Nullable: True Default: None|
|FOTO                                |String(255,0,0)     |URL naar Afbeelding - Nullable: True Default: None|
|GELEIDERAILLENGTE                   |Float(0,25,10)      |Totale lengte van alle aanwezige geleiderail op en in het kunstwerk - Nullable: True|
|KILOMETRERING                       |Float(0,25,10)      |Aanduiding Kilometrering ligging kunstwerk - Nullable: True|
|KWBREEDTE                           |Float(0,25,10)      |Breedte kunstwerk - Nullable: True|
|KWHOOGTE                            |Float(0,25,10)      |Hoogte kunstwerk - Nullable: True|
|KWKMEIND                            |Float(0,25,10)      |Kilometrering eind kunstwerk - Nullable: True|
|KWKMSTART                           |Float(0,25,10)      |Kilometrering start kunstwerk - Nullable: True|
|KWLENGTE                            |Float(0,25,10)      |Totale lengte kunstwerk - Nullable: True|
|KWOPPERVLAKTE                       |Float(0,25,10)      |Totale oppervlakte kunstwerk - Nullable: True|
|LEUNINGLENGTE                       |Float(0,25,10)      |Totale lengte leuningen op en in het kunstwerk  - Nullable: True|
|NAAM                                |String(255,0,0)     |Naam van het kunstwerk - Nullable: True Default: None|
|ONDERHOUDBIJZONDER                  |BLOB(60000,0,0)     |Bijzonderheden over onderhoud []- Nullable: True Default: None| 
|ONDERHOUDOPMERKING                  |BLOB(60000,0,0)     |Opmerkingen over het onderhoud [] - Nullable: True Default: None|
|OPLEGGINGAANTAL                     |SmallInteger(0,10,0)|Aantal oplegblokken - Nullable: True|
|PLANJAARPMO                         |SmallInteger(0,10,0)|Planjaar PMO - Nullable: True|
|PLANJAARVIK                         |SmallInteger(0,10,0)|Planjaar VIK - Nullable: True|
|RENOVATIEJAAR                       |SmallInteger(0,10,0)|Renovatie jaar - Nullable: True|
|TALUDBEKLEDINGOPPO                  |Float(0,25,10)      |Oppervlakte taludbekleding, m2, 2 decimalen - Nullable: True|
|VOEGOVERGANGENAANT                  |SmallInteger(0,10,0)|Aantal voegovergangen - Nullable: True|
|VOEGOVERGANGENTOTA                  |Float(0,25,10)      |Totale lengte voegovergangen - Nullable: True|
|BEHEEROBJECTSUBTYP                  |String(255,0,0)     |Beheerobject subtype, keuzelijst [BEHEER_OBJECT_SUBTYPE] - Nullable: True Default: None|
|FUNCTIEBOVEN                        |String(255,0,0)     |Functie boven, keuzelijst [FUNCTIE] - Nullable: True Default: None|
|FUNCTIEONDER                        |String(255,0,0)     |Functie onder, keuzelijst [FUNCTIE] - Nullable: True Default: None|
|GEMEENTE                            |String(255,0,0)     |Gemeente naam, keuzelijst [GEMEENTE] - Nullable: True Default: None|
|GEDEELDBEHEER                       |String(255,0,0)     |Indien van toepassing, tweede beheerder van het object, keuzelijst [GEDEELD_BEHEER] - Nullable: True Default: None|
|LEVENSCYCLUS                        |String(255,0,0)     |Levenscyclus, keuzelijst [LEVENSCYCLUS] - Nullable: True Default: None|
|CONDITIESCORE                       |String(255,0,0)     |Conditiescore conform NEN 2767-4 - Nullable: True Default: None|
|CONDITIESCORE_DATUM                 |Date(8,0,0)         |Datum opname Conditiescore - Nullable: True|
|RELATIEVEHOOGTELIGGING              |SmallInteger(0,0,0) |Beschrijving - [] - Nullable: False Default: 0|
|DEKPLAATMATERIAAL                   |String(255,0,0)     |Dekplaatmateriaal - Nullable: True Default: None|
|MONUMENT                            |String(255,0,0)     |Monument, keuzelijst [MONUMENT] - Nullable: True Default: None|
|NENBEHEEROBJECT                     |String(255,0,0)     |NENBEHEEROBJECT - Nullable: True Default: None|
|OPLEGGINGTYPE                       |String(255,0,0)     |Oplegging type, keuzelijst [OPLEGGING_TYPE] - Nullable: True Default: None|
|SCHOTBALKAANWEZIG                   |String(1,0,0)       |Schotbalk aanwezig, keuzelijst [jaNeeOnbekend] - Nullable: True Default: O|
|TYPEVOEGOVERGANG                    |String(255,0,0)     |Type voegovergang object, keuzelijst [TYPE_VOEGOVERGANG] - Nullable: True Default: None|
|SHAPE                               |Geometry           |Punt|
|XCOORDINAAT                         |Float(0,25,10)     |X coordinaat Middenpunt beheerobject(RD) - Nullable: True|
|YCOORDINAAT                         |Float(0,25,10)     |Y coordinaat Middenpunt beheerobject(RD) - Nullable: True|
|ZCOORDINAAT                         |Float(0,25,10)     |Z coordinaat Middenpunt beheerobject(RD) - Nullable: True|
|HALTE                               |String(255,0,0)    |FK naar halte_v - Nullable: True Default: None|
|VAARWEG                             |String(255,0,0)    |FK naar vaarweg_l - Nullable: True Default: None|
|WEG                                 |String(255,0,0)    |FK naar weg_l - Nullable: True Default: None|
|TRAJECT                             |String(255,0,0)    |FK naar traject_v - Nullable: True Default: None|
|TRAJECT2                            |String(255,0,0)    |FK naar traject_v - Nullable: True Default: None|
|ADRES                               |String(255,0,0)    |FK naar adres_tbl - Nullable: True Default: None|
|IDENTIFICATIE                       |String(255,0,0)    |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecKWV] - Nullable: True Default: None|
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

***
