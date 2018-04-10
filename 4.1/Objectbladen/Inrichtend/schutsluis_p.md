﻿## AREAALDATA.schutsluis_p

$ Feature dataset: Inrichtend


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ NEN 2767-4 / PNH
* __Positionele nauwkeurigheid:__ 5 cm
* __SHAPE:__ Punt
* __Definitie:__ Onderdeel van een civiel-technisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen. De NEN 2767-4 decompositie wordt gevolgd. 

Een SCHUTSLUIS is een beheerobject van het type:  

* Schutsluizen

***

|KOLOM                               |TYPE                     |DEFINITIE|
|------                              |----                     |-----    |
|OBJECTID                            |OID(38,0,0)              |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None|
|GLOBALID                            |GlobalID(38,0,0)         |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None|
|AD_ID                               |String(255,0,0)          |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None|
|GISIB_ID                            |Integer(0,10,0)          |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None|
|TOPCODE                             |String(255,0,0)          |PNH; Topcode; keuzelijst [TOPCODE]; Nullable: True; Default: None|
|IDENTIFICATIE                       |String(255,0,0)          |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)          |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|OBJECTBEGINTIJD                     |Date(8,0,0)              |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)              |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|RELATIEVEHOOGTELIGGING              |SmallInteger(0,10,0)     |BGT; Aanduiding voor de relatieve hoogte van het object; Nullable: False; Default: 0|
|BEHEERDER                           |String(255,0,0)          |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None|
|ONDERHOUDER                         |String(255,0,0)          |PNH; Onderhouder van het object: kan meerdere door puntkomma gescheiden waardes bevatten; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None|
|EIGENAAR                            |String(255,0,0)          |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None|
|TYPESPEC                            |String(255,0,0)          |PNH; Nadere typering van het object; keuzelijst [typeSpecSSS]; Nullable: True; Default: None|
|BIJZONDERHEID                       |String(255,0,0)          |PNH; Extra toelichting; Nullable: True; Default: None|
|CONFORMNEN                          |String(1,0,0)            |PNH; Indicatie of classificatie conform NEN is, Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend]; Nullable: False; Default: O|
|OMSCHRIJVING                        |String(255,0,0)          |PNH; Extra toelichting; Nullable: True; Default: None|
|DEURENAANTAL                        |SmallInteger(0,10,0)     |PNH; Aantal deuren (bij sluis); Nullable: True|
|FOTO                                |String(255,0,0)          |PNH; URL naar Afbeelding; Nullable: True; Default: None|
|KWBREEDTE                           |Float(0,25,10)           |PNH; Breedte kunstwerk; Nullable: True|
|KWHOOGTE                            |Float(0,25,10)           |PNH; Hoogte kunstwerk; Nullable: True|
|KWLENGTE                            |Float(0,25,10)           |PNH; Totale lengte kunstwerk; Nullable: True|
|KWOPPERVLAKTE                       |Float(0,10,2)            |PNH; Oppervlakte van het kunstwerk in m2, afgerond op 2 decimalen; Nullable: True; Default: None|
|NAAM                                |String(255,0,0)          |PNH; Naam van het kunstwerk; Nullable: True; Default: None|
|REMMINGSWERKVERVANGINGSJAAR         |SmallInteger(0,10,0)     |PNH; Vervangingsjaar Remwerk ; Nullable: True|
|RENOVATIEJAAR                       |SmallInteger(0,10,0)     |PNH; Renovatiejaar ; Nullable: True; Default: None|
|WACHTPLAATSVERVANGINGSJAAR          |SmallInteger(0,10,0)     |PNH; Vervangingsjaar wachtplaats ; Nullable: True|
|BEHEEROBJECTSUBTYP                  |String(255,0,0)          |PNH; Beheerobject subtype; keuzelijst [BEHEER_OBJECT_SUBTYPE]; Nullable: True; Default: None|
|CEMTKLASSE                          |String(255,0,0)          |PNH; Klasse van het cement; keuzelijst [CEMT_KLASSE]; Nullable: True; Default: None|
|GEMEENTE                            |String(255,0,0)          |PNH; Gemeente naam; keuzelijst [GEMEENTE]; Nullable: True; Default: None|
|GEDEELDBEHEER                       |String(255,0,0)          |PNH; Indien van toepassing, tweede beheerder van het object; keuzelijst [GEDEELD_BEHEER]; Nullable: True; Default: None|
|LEVENSCYCLUS                        |String(255,0,0)          |PNH; Levenscyclus; keuzelijst [LEVENSCYCLUS]; Nullable: True; Default: None|
|MONUMENT                            |String(20,0,0)           |PNH; Monumentale status; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: None|
|NENBEHEEROBJECT                     |String(255,0,0)          |PNH; NENBEHEEROBJECT; keuzelijst [LEVENSCYCLUS]; Nullable: True; Default: None|
|SCHOTBALKAANWEZIG                   |String(1,0,0)            |PNH; Schotbalk aanwezig; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: None|
|ARBO_RIE_UITGEVOERD                 |Date(8,0,0)              |PNH; Laatst uitgevoerde RIE (datum); Nullable: True|
|ARBO_RIE_GEPLAND                    |Date(8,0,0)              |PNH; Volgende geplande RIE (datum); Nullable: True|
|CE_MARKERING                        |String(1,0,0)            |PNH; CE markering: Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: O|
|CE_MARKERING_DATUM                  |Date(8,0,0)              |PNH; CE markering sinds (datum); Nullable: True|
|AFSTANDSBEDIENING                   |String(1,0,0)            |PNH; Afstandsbediening (Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend]; Nullable: False; Default: O|
|CONDITIESCORE                       |Integer(0,10,0)          |PNH; Conditiescore conform NEN 2767-4; Nullable: True; Default: None|
|CONDITIESCORE_DATUM                 |Date(8,0,0)              |PNH; Datum opname Conditiescore; Nullable: True|
|VAARWEGDEELTRAJECT                  |String(255,0,0)          |PNH; FK naar vaarwegdeeltraject_v; Nullable: True; Default: None|
|TRAJECT                             |String(255,0,0)          |PNH; FK naar traject_v; Nullable: True; Default: None|
|TRAJECT2                            |String(255,0,0)          |PNH; Foreign Key naar traject_v, in het geval van een tweede traject; Nullable: True; Default: None|
|ADRES                               |String(255,0,0)          |PNH; FK naar adres_tbl; Nullable: True; Default: None|
|DATALEVERANCIER                     |String(255,0,0)          |PNH; Leverancier van de data; Nullable: True; Default: None|
|CREATED_USER                        |String(255,0,0)          |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)              |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)           |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)              |PNH; Datum van de laatste mutatie; Nullable: True|
|SHAPE                               |Geometry                 |PNH; Punt|



***

