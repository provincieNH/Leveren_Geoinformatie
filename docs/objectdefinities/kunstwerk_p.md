## AREAALDATA.kunstwerk_p

*Feature dataset: Functioneel*


* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ NEN 2767-4 / PNH
* __Positionele nauwkeurigheid:__ 5 cm
* __Geometrie:__ Punt
* __Definitie:__ Onderdeel van een civiel-technisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen. De NEN 2767-4 decompositie wordt gevolgd. Dit is een samenvattende feature class van de vorige feature classes: KunstwerkBeweegbaar_p, Kunstwerkvast_p en Schutsluis_p
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ Beheerobject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                    |-----    |
|OBJECTID                            |OID(38,0,0)             |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)        |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: No|
|AD_ID                               |String(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |Integer(0,10,0)         |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |String(255,0,0)         |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.md); Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)             |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|BEHEERDER                           |String(255,0,0)         |PNH; Beheerder van het object; keuzelijst [BEHEERDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEERDER.md); Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |String(255,0,0)         |PNH; Onderhouder van het object: kan meerdere door puntkomma gescheiden waardes bevatten; keuzelijst [ONDERHOUDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ONDERHOUDER.md); Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |String(255,0,0)         |PNH; Eigenaar van het object; keuzelijst [INSTANTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/INSTANTIE.md); Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |String(255,0,0)         |PNH; Nadere typering van het object; keuzelijst [typeSpecKSW](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecKSW.md); Nullable: True; Default: None; Visible: Yes|
|TOPCODE                             |String(10,0,0)          |PNH; Topcode. De aannemer mag dit niet invullen; ; Nullable: False; Default: None; Visible: Yes|
|VERKEERSKLASSE                      |String(255,0,0)         |PNH; Verkeersklasse object; keuzelijst [VERKEERSKLASSE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERKEERSKLASSE.md); Nullable: True; Default: None; Visible: No|
|AANTALOVERSPANNING                  |SmallInteger(0,5,0)     |PNH; Aantal overspanningen; ; Nullable: True; Default: None; Visible: Yes|
|BOUWJAARBEWEGINGSW                  |SmallInteger(0,5,0)     |PNH; Bouwjaar Bewegingswerk; ; Nullable: True; Default: None; Visible: No|
|BOUWJAARBOVENBOUW                   |SmallInteger(0,5,0)     |PNH; Bouwjaar Bovenbouw; ; Nullable: True; Default: None; Visible: No|
|BOUWJAARELECTRISCH                  |SmallInteger(0,5,0)     |PNH; Bouwjaar Electrische Installatie; ; Nullable: True; Default: None; Visible: No|
|BOUWJAARHYDRAULISC                  |String(255,0,0)         |PNH; Bouwjaar Hydraulische Installatie; ; Nullable: True; Default: None; Visible: No|
|BOUWJAARONDERBOUW                   |SmallInteger(0,5,0)     |PNH; Bouwjaar Onderbouw; ; Nullable: True; Default: None; Visible: No|
|BOUWJAARVAL                         |SmallInteger(0,5,0)     |PNH; Bouwjaar Val; ; Nullable: True; Default: None; Visible: No|
|CONFORMNEN                          |String(1,0,0)           |PNH; Indicatie of classificatie conform NEN is: Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNeeOnbekend.md); Nullable: True; Default: O; Visible: No|
|OPMERKING                           |String(3000,0,0)        |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|DOORRIJBREEDTERIJBAAN1              |Float(0,25,10)          |PNH; Doorrijbreedte rijbaan 1, Meetnauwkeurigheid +/- 1 cm; ; Nullable: True; Default: None; Visible: No|
|DOORRIJBREEDTERIJBAAN2              |Float(0,25,10)          |PNH; Doorrijbreedte rijbaan 2, Meetnauwkeurigheid +/- 1 cm; ; Nullable: True; Default: None; Visible: No|
|DOORRIJBREEDTERIJBAAN3              |Float(0,25,10)          |PNH; Doorrijbreedte rijbaan 3, Meetnauwkeurigheid +/- 1 cm; ; Nullable: True; Default: None; Visible: No|
|DOORRIJHOOGTERIJST                  |Float(0,25,10)          |PNH; Doorrijbreedte rijstrook 1, Meetnauwkeurigheid +/- 1 cm; ; Nullable: True; Default: None; Visible: Yes|
|DOORRIJHOOGTERIJST_1                |Float(0,25,10)          |PNH; Doorrijbreedte rijstrook 2, Meetnauwkeurigheid +/- 1 cm; ; Nullable: True; Default: None; Visible: Yes|
|DOORRIJHOOGTERIJST_2                |Float(0,25,10)          |PNH; Doorrijbreedte rijstrook 3, Meetnauwkeurigheid +/- 1 cm; ; Nullable: True; Default: None; Visible: Yes|
|DOORRIJHOOGTERIJST_3                |Float(0,25,10)          |PNH; Doorrijbreedte rijstrook 4, Meetnauwkeurigheid +/- 1 cm; ; Nullable: True; Default: None; Visible: Yes|
|DOORRIJHOOGTERIJST_4                |Float(0,25,10)          |PNH; Doorrijbreedte rijstrook 5, Meetnauwkeurigheid +/- 1 cm; ; Nullable: True; Default: None; Visible: Yes|
|DOORRIJHOOGTERIJST_5                |Float(0,25,10)          |PNH; Doorrijbreedte rijstrook 6, Meetnauwkeurigheid +/- 1 cm; ; Nullable: True; Default: None; Visible: Yes|
|DOORVAARTBREEDTE1                   |Float(0,25,10)          |PNH; Doorvaartbreedte doorvaartopening 1, Meetnauwkeurigheid +/- 1 cm; ; Nullable: True; Default: None; Visible: No|
|DOORVAARTBREEDTE2                   |Float(0,25,10)          |PNH; Doorvaartbreedte doorvaartopening 2, Meetnauwkeurigheid +/- 1 cm; ; Nullable: True; Default: None; Visible: No|
|DOORVAARTBREEDTE3                   |Float(0,25,10)          |PNH; Doorvaartbreedte doorvaartopening 3, Meetnauwkeurigheid +/- 1 cm; ; Nullable: True; Default: None; Visible: No|
|DOORVAARTBREEDTE4                   |Float(0,25,10)          |PNH; Doorvaartbreedte doorvaartopening 4, Meetnauwkeurigheid +/- 1 cm; ; Nullable: True; Default: None; Visible: No|
|DOORVAARTBREEDTE5                   |Float(0,25,10)          |PNH; Doorvaartbreedte doorvaartopening 5, Meetnauwkeurigheid +/- 1 cm; ; Nullable: True; Default: None; Visible: No|
|DOORVAARTHOOGTE1                    |Float(0,25,10)          |PNH; Doorvaarthoogtemaat doorvaartopening 1 (hoogte t.o.v. NAP, NIET t.o.v. actuele waterpeil), Meetnauwkeurigheid +/- 1 cm; ; Nullable: True; Default: None; Visible: Yes|
|DOORVAARTHOOGTE2                    |Float(0,25,10)          |PNH; Doorvaarthoogtemaat doorvaartopening 2 (hoogte t.o.v. NAP, NIET t.o.v. actuele waterpeil), Meetnauwkeurigheid +/- 1 cm; ; Nullable: True; Default: None; Visible: Yes|
|DOORVAARTHOOGTE3                    |Float(0,25,10)          |PNH; Doorvaarthoogtemaat doorvaartopening 3 (hoogte t.o.v. NAP, NIET t.o.v. actuele waterpeil), Meetnauwkeurigheid +/- 1 cm; ; Nullable: True; Default: None; Visible: Yes|
|DOORVAARTHOOGTE4                    |Float(0,25,10)          |PNH; Doorvaarthoogtemaat doorvaartopening 4 (hoogte t.o.v. NAP, NIET t.o.v. actuele waterpeil), Meetnauwkeurigheid +/- 1 cm; ; Nullable: True; Default: None; Visible: Yes|
|DOORVAARTHOOGTE5                    |Float(0,25,10)          |PNH; Doorvaarthoogtemaat doorvaartopening 5 (hoogte t.o.v. NAP, NIET t.o.v. actuele waterpeil), Meetnauwkeurigheid +/- 1 cm; ; Nullable: True; Default: None; Visible: Yes|
|FOTO                                |String(255,0,0)         |PNH; Locatie van de foto op de S schijf bij PNH. Deze hoeft niet gevuld te worden door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BOUWJAAR                            |SmallInteger(0,5,0)     |PNH; Bouwjaar; ; Nullable: True; Default: None; Visible: No|
|RENOVATIEJAAR                       |SmallInteger(0,5,0)     |PNH; Renovatiejaar; ; Nullable: True; Default: None; Visible: No|
|TALUDBEKLEDINGOPPO                  |Float(0,25,10)          |PNH; Oppervlakte taludbekleding, m2, 2 decimalen; ; Nullable: True; Default: None; Visible: No|
|BEHEEROBJECTSUBTYP                  |String(255,0,0)         |PNH; Beheerobject subtype; keuzelijst [BEHEER_OBJECT_SUBTYPE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEER_OBJECT_SUBTYPE.md); Nullable: True; Default: None; Visible: Yes|
|TYPEVOEGOVERGANG                    |String(255,0,0)         |PNH; Type voegovergang object; keuzelijst [TYPE_VOEGOVERGANG](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/TYPE_VOEGOVERGANG.md); Nullable: True; Default: None; Visible: No|
|DEURENAANTAL                        |SmallInteger(0,5,0)     |PNH; Aantal deuren (bij sluis); ; Nullable: True; Default: None; Visible: No|
|REMMINGSWERKVERVANGINGSJAAR         |SmallInteger(0,5,0)     |PNH; Vervangingsjaar Remwerk; ; Nullable: True; Default: None; Visible: No|
|WACHTPLAATSVERVANGINGSJAAR          |SmallInteger(0,5,0)     |PNH; Vervangingsjaar wachtplaats; ; Nullable: True; Default: None; Visible: No|
|CEMTKLASSE                          |String(255,0,0)         |PNH; Klasse van het cement; keuzelijst [CEMT_KLASSE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/CEMT_KLASSE.md); Nullable: True; Default: None; Visible: No|
|INBOUWJAARPLC                       |SmallInteger(0,5,0)     |PNH; Inbouwjaar PLC; ; Nullable: True; Default: None; Visible: No|
|INSPECTIEJAARCMEH                   |SmallInteger(0,5,0)     |PNH; Inspectie jaar CMEH Installaties; ; Nullable: True; Default: None; Visible: No|
|INSPECTIEJAARHEFKA                  |SmallInteger(0,5,0)     |PNH; Inspectie jaar Hefkabels; ; Nullable: True; Default: None; Visible: No|
|KWBREEDTE                           |Float(0,25,10)          |PNH; Breedte kunstwerk, m, 2 decimalen; ; Nullable: True; Default: None; Visible: Yes|
|KWHOOGTE                            |Float(0,25,10)          |PNH; Hoogte kunstwerk, m, 2 decimalen; ; Nullable: True; Default: None; Visible: Yes|
|KWLENGTE                            |Float(0,25,10)          |PNH; Totale lengte kunstwerk; ; Nullable: True; Default: None; Visible: Yes|
|KWOPPERVLAKTE                       |Float(0,25,10)          |PNH; Oppervlakte van het kunstwerk in m2, afgerond op 2 decimalen; ; Nullable: True; Default: None; Visible: No|
|NAAM                                |String(255,0,0)         |PNH; Naam van het kunstwerk; ; Nullable: True; Default: None; Visible: Yes|
|OPLEGGINGAANTAL                     |SmallInteger(0,5,0)     |PNH; Aantal oplegblokken; ; Nullable: True; Default: None; Visible: No|
|BOUWJAARREMMINGSWERK                |SmallInteger(0,5,0)     |PNH; Vervangingsjaar Remwerk; ; Nullable: True; Default: None; Visible: No|
|VOEGOVERGANGENAANT                  |SmallInteger(0,5,0)     |PNH; Aantal voegovergangen; ; Nullable: True; Default: None; Visible: No|
|VOEGOVERGANGENTOTA                  |Float(0,25,10)          |PNH; Totale lengte voegovergangen; ; Nullable: True; Default: None; Visible: No|
|WACHTPLAATSVERVANG                  |SmallInteger(0,5,0)     |PNH; Vervangingsjaar wachtplaats; ; Nullable: True; Default: None; Visible: No|
|GEMEENTE                            |String(255,0,0)         |PNH; Gemeentenaam; keuzelijst [GEMEENTE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/GEMEENTE.md); Nullable: True; Default: None; Visible: No|
|GEDEELDBEHEER                       |String(255,0,0)         |PNH; Indien van toepassing, tweede beheerder van het object; keuzelijst [GEDEELD_BEHEER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/GEDEELD_BEHEER.md); Nullable: True; Default: None; Visible: No|
|LEVENSCYCLUS                        |String(255,0,0)         |PNH; Levenscyclus; keuzelijst [LEVENSCYCLUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/LEVENSCYCLUS.md); Nullable: True; Default: None; Visible: No|
|MONUMENT                            |String(20,0,0)          |PNH; Monumentale status; keuzelijst [jaNeeOnbekend](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNeeOnbekend.md); Nullable: True; Default: None; Visible: No|
|NENBEHEEROBJECT                     |String(255,0,0)         |PNH; NENBEHEEROBJECT; keuzelijst [NENBEHEEROBJECT](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/NENBEHEEROBJECT.md); Nullable: True; Default: None; Visible: Yes|
|SCHOTBALKAANWEZIG                   |String(1,0,0)           |PNH; Schotbalk aanwezig; keuzelijst [jaNeeOnbekend](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNeeOnbekend.md); Nullable: True; Default: None; Visible: No|
|ARBO_RIE_UITGEVOERD                 |Date(8,0,0)             |PNH; Laatst uitgevoerde RIE (datum); ; Nullable: True; Default: None; Visible: No|
|ARBO_RIE_GEPLAND                    |Date(8,0,0)             |PNH; Volgende geplande RIE (datum); ; Nullable: True; Default: None; Visible: No|
|CE_MARKERING                        |String(1,0,0)           |PNH; CE markering: Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNeeOnbekend.md); Nullable: True; Default: O; Visible: No|
|CE_MARKERING_DATUM                  |Date(8,0,0)             |PNH; CE markering sinds (datum); ; Nullable: True; Default: None; Visible: No|
|AFSTANDSBEDIENING                   |String(1,0,0)           |PNH; Afstandsbediening (Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNeeOnbekend.md); Nullable: True; Default: O; Visible: No|
|CONDITIESCORE                       |Integer(0,10,0)         |PNH; Conditiescore conform NEN 2767-4; ; Nullable: True; Default: None; Visible: No|
|CONDITIESCORE_DATUM                 |Date(8,0,0)             |PNH; Datum opname Conditiescore; ; Nullable: True; Default: None; Visible: No|
|TRAJECT                             |String(255,0,0)         |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/TRAJECT_NAAM.md); Nullable: True; Default: None; Visible: Yes|
|TRAJECT2                            |String(255,0,0)         |PNH; Tweede verwijzende sleutel naar traject_v, in het geval van een tweede traject; ; Nullable: True; Default: None; Visible: Yes|
|VAARWEGDEELTRAJECT                  |String(255,0,0)         |PNH; Verwijzende sleutel naar vaarwegdeeltraject_v (simpel); ; Nullable: True; Default: None; Visible: No|
|ADRES                               |String(255,0,0)         |PNH; Verwijzende sleutel naar adres_tbl (simpel); ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |String(255,0,0)         |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)             |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)          |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)             |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry                |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|
|DATALEVERANCIER                     |String(255,0,0)         |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|


***

