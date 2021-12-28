## AREAALDATA.kastOvl_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Kast ten behoeve van de regeling van de openbare verlichting.
* __Mapping_BGT:__ kast_p
* __Mapping_Gisib:__ OVL kast
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__(oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----          	     |-----    |
|OBJECTID                            |OID(38,0,0)            |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)       |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: No|
|AD_ID                               |TEXT(255,0,0)          |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)           |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BGTPLUSTYPE                         |TEXT(50,0,0)           |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeKST](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeKST.html); Nullable: False; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)          |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.html); Nullable: False; Default: Nieuw; Visible: Yes|
|HUIDIGESTATUS                       |TEXT(50,0,0)           |PNH; Huidige status; keuzelijst [ConditionOfFacilityValue](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ConditionOfFacilityValue.html); Nullable: False; Default: functional; Visible: No|
|OBJECTBEGINTIJD                     |DATE(8,0,0)            |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)            |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING              |SHORT(0,5,0)           |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                           |TEXT(255,0,0)          |PNH; Beheerder van het object; keuzelijst [BEHEERDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEERDER.html); Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)          |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ONDERHOUDER.html); Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |TEXT(255,0,0)          |PNH; Eigenaar van het object; keuzelijst [INSTANTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/INSTANTIE.html); Nullable: True; Default: None; Visible: Yes|
|VERTICALE_POSITIE                   |LONG(0,10,0)           |PNH; Verticale positie; keuzelijst [VerticalePositie](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VerticalePositie.html); Nullable: False; Default: 3; Visible: No|
|TYPESPEC                            |TEXT(255,0,0)          |PNH; Nadere typering van het object; keuzelijst [typeSpecKST](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecKST.html); Nullable: True; Default: None; Visible: Yes|
|OPMERKING                           |TEXT(255,0,0)          |PNH; Toevoeging van subjectieve informatie met betrekking tot opmerkelijke waarnemingen; ; Nullable: True; Default: None; Visible: No|
|AANTALGROEPEN                       |SHORT(0,5,0)           |PNH; Aantal elektriciteitsgroepen aanwezig in de kast; ; Nullable: True; Default: None; Visible: No|
|TYPECOMMUNICATIE                    |TEXT(30,0,0)           |PNH; Type communicatie; keuzelijst [TYPE_COMMUNICATIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/TYPE_COMMUNICATIE.html); Nullable: True; Default: None; Visible: No|
|DATUMPLAATSING                      |DATE(8,0,0)            |PNH; Datum plaatsing; ; Nullable: True; Default: None; Visible: No|
|AANWEZGIHEIDDIM                     |TEXT(1,0,0)            |PNH; Aanwezigheid van een diminstallatie in de kast: Ja/Nee; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.html); Nullable: True; Default: N; Visible: No|
|AANWTELEMANAGEMENT                  |TEXT(1,0,0)            |PNH; Aanwezigheid van een telemanagementvoorziening in de kast (t.b.v. het op afstand kunnen instellen): Ja/Nee; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.html); Nullable: True; Default: N; Visible: No|
|AUTOMAATKOPPELING                   |TEXT(20,0,0)           |PNH; Aangeven of er een koppeling is tussen automaat en Ovlkast; keuzelijst [jaNeeOnbekend](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNeeOnbekend.html); Nullable: True; Default: None; Visible: Yes|
|AUTOMAATNUMMER                      |LONG(0,10,0)           |PNH; Indien een een automaat gekoppeld is aan een Ovlkast, het kastnummer invullen; ; Nullable: True; Default: None; Visible: Yes|
|LEVENSVERWACHTING                   |SHORT(0,5,0)           |PNH; Levensverwachting; ; Nullable: True; Default: None; Visible: No|
|PLANJAAR                            |SHORT(0,5,0)           |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|RALKLEUR                            |TEXT(30,0,0)           |PNH; De RAL-kleur(en) die gebruikt zijn voor het object. Eerst de kleurcode gevolgd door de naam van de kleur; ; Nullable: True; Default: None; Visible: No|
|FABRIKANTTYPECODE                   |TEXT(255,0,0)          |PNH; Fabrikanttypecode; ; Nullable: True; Default: None; Visible: Yes|
|EANEMETER                           |TEXT(255,0,0)          |PNH; De EAN-code vermeld op de meter; ; Nullable: True; Default: None; Visible: No|
|KASTNUMMER                          |TEXT(255,0,0)          |PNH; Bestaande uit 6 cijfers: de eerste drie het nummerdeel van het wegnummer (N201> 201), de laatste drie het nummer van het dichtstbijzijnde hectometerpaaltje (38,1> 381) = Installatienummer (zie Verlichtingsinstallatie); ; Nullable: True; Default: None; Visible: Yes|
|TYPEDIMSYSTEEM                      |TEXT(20,0,0)           |PNH; Het type dimsysteem mits de kastOvl is aangesloten op een dimsysteem, zie AANWEZIGHEIDDIM; keuzelijst [jaNeeOnbekend](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNeeOnbekend.html); Nullable: True; Default: None; Visible: No|
|MATERIAALTYPE                       |TEXT(255,0,0)          |PNH; Type materiaal; keuzelijst [MATERIAALTYPE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/MATERIAALTYPE.html); Nullable: True; Default: None; Visible: Yes|
|ADRES                               |TEXT(255,0,0)          |PNH; Verwijzende sleutel naar adres_tbl (simpel); ; Nullable: True; Default: None; Visible: No|
|INNETWERK                           |TEXT(255,0,0)          |PNH; Verwijzende sleutel naar utiliteitsNet_tbl (simpel); ; Nullable: True; Default: None; Visible: No|
|EISVOORZORGSMAATRBUFFER             |LONG(0,10,0)           |PNH; Wanneer de asset een verhoogd risico op graafschade heeft, kan hier een veiligheidsbuffer in meters worden opgegeven. Wanneer binnen deze buffer gegraven wordt, ontvangt de grondroerder een eisvoorzorgsmaatregelbrief; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |TEXT(255,0,0)          |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |TEXT(255,0,0)          |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)            |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)           |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)            |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry(0,0,0)        |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|



***
