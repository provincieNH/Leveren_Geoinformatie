﻿## AREAALDATA.schutsluis_p

$ Feature dataset: Inrichtend


* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ NEN 2767-4 / PNH
* __Positionele nauwkeurigheid:__ 5 cm
* __SHAPE:__ Punt
* __Definitie:__ Onderdeel van een civiel-technisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen. De NEN 2767-4 decompositie wordt gevolgd. 

Een SCHUTSLUIS is een beheerobject van het type:  

* Schutsluizen

***

|KOLOM                               |TYPE                |DEFINITIE|
|------                              |----                |-----    |
|TOPCODE                             |String(255,0,0)     |Topcode, keuzelijst [TOPCODE] - Nullable: True Default: None|
|BIJZONDERHEID                       |String(255,0,0)     |Extra toelichting - Nullable: True Default: None|
|CONFORMNEN                          |String(1,0,0)       |Indicatie of classificatie conform NEN is, Ja/Nee/Onbekend, keuzelijst [jaNeeOnbekend] Nullable: False Default: O|
|OMSCHRIJVING                        |String(255,0,0)     |Extra toelichting - Nullable: True Default: None|
|DEURENAANTAL                        |SmallInteger(0,10,0)|Aantal deuren (bij sluis) - Nullable: True|
|FOTO                                |String(255,0,0)     |URL naar Afbeelding - Nullable: True Default: None|
|KILOMETRERING                       |Float(0,25,10)      |Aanduiding Kilometrering ligging kunstwerk - Nullable: True|
|KWBREEDTE                           |Float(0,25,10)      |Breedte kunstwerk - Nullable: True|
|KWHOOGTE                            |Float(0,25,10)      |Hoogte kunstwerk - Nullable: True|
|KWKMEIND                            |Float(0,25,10)      |Kilometrering eind kunstwerk - Nullable: True|
|KWKMSTART                           |Float(0,25,10)      |Kilometrering start kunstwerk - Nullable: True|
|KWLENGTE                            |Float(0,25,10)      |Totale lengte kunstwerk - Nullable: True|
|KWOPPERVLAKTE                       |Float(0,25,10)      |Totale oppervlakte kunstwerk - Nullable: True|
|NAAM                                |String(255,0,0)     |Naam van het kunstwerk - Nullable: True Default: None|
|ONDERHOUDBIJZONDER                  |BLOB(60000,0,0)     |Bijzonderheden over onderhoud []- Nullable: True Default: None| 
|ONDERHOUDOPMERKING                  |BLOB(60000,0,0)     |Opmerkingen over het onderhoud [] - Nullable: True Default: None|
|PLANJAARPMO                         |Integer(0,10,0)     |Planjaar PMO  - Nullable: True|
|PLANJAARVIK                         |SmallInteger(0,10,0)|Planjaar VIK  - Nullable: True|
|REMMINGSWERKVERVANGINGSJAAR         |SmallInteger(0,10,0)|Vervangingsjaar Remwerk  - Nullable: True|
|RENOVATIEJAAR                       |SmallInteger(0,10,0)|Renovatie jaar  - Nullable: True|
|WACHTPLAATSVERVANGINGSJAAR          |SmallInteger(0,10,0)|Vervangingsjaar wachtplaats  - Nullable: True|
|BEDIENTIJDEN                        |String(255,0,0)     |Bedientijden waarde, keuzelijst [BEDIENTIJDEN] - Nullable: True Default: None|
|BEHEEROBJECTSUBTYP                  |String(255,0,0)     |Beheerobject subtype, keuzelijst [BEHEER_OBJECT_SUBTYPE] - Nullable: True Default: None|
|CEMTKLASSE                          |String(255,0,0)     |CEMTKLASSE, keuzelijst [CEMT_KLASSE] - Nullable: True Default: None|
|GEMEENTE                            |String(255,0,0)     |Gemeente naam, keuzelijst [GEMEENTE] - Nullable: True Default: None|
|GEDEELDBEHEER                       |String(255,0,0)     |Indien van toepassing, tweede beheerder van het object, keuzelijst [GEDEELD_BEHEER] - Nullable: True Default: None|
|LEVENSCYCLUS                        |String(255,0,0)     |Levenscyclus, keuzelijst [LEVENSCYCLUS] - Nullable: True Default: None|
|MONUMENT                            |String(255,0,0)     |Monument, keuzelijst [MONUMENT] - Nullable: True Default: None|
|NENBEHEEROBJECT                     |String(255,0,0)     |NENBEHEEROBJECT - Nullable: True Default: None|
|SCHOTBALKAANWEZIG                   |String(1,0,0)       |Schotbalk aanwezig, keuzelijst [jaNeeOnbekend] - Nullable: True Default: None|
|ARBO_RIE_UITGEVOERD                 |Date(8,0,0)         |Laatst uitgevoerde RIE (datum) - Nullable: True|
|ARBO_RIE_GEPLAND                    |Date(8,0,0)         |Volgende geplande RIE (datum) - Nullable: True|
|CE_MARKERING                        |String(1,0,0)       |CE markering: Ja/Nee/Onbekend, keuzelijst [jaNeeOnbekend] Nullable: True Default: O|
|CE_MARKERING_DATUM                  |Date(8,0,0)         |CE markering sinds (datum) - Nullable: True|
|AFSTANDSBEDIENING                   |String(1,0,0)       |Afstandsbediening (Ja/Nee/Onbekend, keuzelijst [jaNeeOnbekend] Nullable: False Default: O|
|AFSTANDSBEDIENING_DATUM             |Date(8,0,0)         |Afstandsbediening sinds (datum) - Nullable: True|
|CONDITIESCORE                       |String(255,0,0)     |Conditiescore conform NEN 2767-4 - Nullable: True Default: None|
|CONDITIESCORE_DATUM                 |Date(8,0,0)         |Datum opname Conditiescore - Nullable: True|
|SHAPE                               |Geometry            |Punt|
|XCOORDINAAT                         |Float(0,25,10)      |X coordinaat Middenpunt beheerobject(RD) - Nullable: True|
|YCOORDINAAT                         |Float(0,25,10)      |Y coordinaat Middenpunt beheerobject(RD) - Nullable: True|
|ZCOORDINAAT                         |Float(0,25,10)      |Z coordinaat Middenpunt beheerobject(RD) - Nullable: True|
|RELATIEVEHOOGTELIGGING              |SmallInteger(0,0,0) |Beschrijving - [] - Nullable: False Default: 0|
|TRAJECT                             |String(255,0,0)     |FK naar traject_v - Nullable: True Default: None| 
|TRAJECT2                            |String(255,0,0)     |FK naar traject_v - in het geval van een tweede traject - Nullable: True Default: None|
|VAARWEG                             |String(255,0,0)     |FK naar vaarweg_l - Nullable: True Default: None|
|ADRES                               |String(255,0,0)     |FK naar adres_tbl - Nullable: True Default: None|
|IDENTIFICATIE                       |String(255,0,0)     |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)     |Nadere typering van het object, keuzelijst [typeSpecSSS] - Nullable: True Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)     |Status van de gegevens, keuzelijst [VERWERKINGSSTATUS] - Nullable: False Default: Nieuwl|
|OBJECTID                            |OID(38,0,0)         |Interne ID ArcGIS - Nullable: False|
|GLOBALID                            |GlobalID(38,0,0)    |Global Unique Identifier - Nullable: False|
|GISIB_ID                            |Integer(0,10,0)     |ID beheer openbare ruimte (GISIB) - Nullable: True|
|AD_ID                               |String(255,0,0)     |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]' - Nullable: False Default: None|
|OBJECTBEGINTIJD                     |Date(8,0,0)         |Datum waarop het object bij de bronhouder is ontstaan - Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)         |Datum waarop het object bij de bronhouder niet meer geldig is - Nullable: True|
|CREATED_USER                        |String(255,0,0)     |Naam van gebruiker die de rij heeft aangemaakt - Nullable: True Default: None|
|CREATED_DATE                        |Date(8,0,0)         |Aanmaakdatum - Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)      |Naam van gebruiker die de laatste mutatie heeft doorgevoerd - Nullable: True Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)         |Datum van de laatste mutatie - Nullable: True|
|BEHEERDER                           |String(255,0,0)     |Beheerder van het object, keuzelijst [BEHEERDER] - Nullable: True Default: None|
|ONDERHOUDER                         |String(255,0,0)     |Onderhouder van het object, keuzelijst [ONDERHOUDER] - Nullable: True Default: None|
|EIGENAAR                            |String(255,0,0)     |Eigenaar van het object, keuzelijst [INSTANTIE] - Nullable: True Default: None| 
|DATALEVERANCIER                     |String(255,0,0)     |Leverancier van de data - Nullable: True Default: None|


***

