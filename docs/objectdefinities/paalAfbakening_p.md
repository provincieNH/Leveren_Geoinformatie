## AREAALDATA.paalAfbakening_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Paal; Langwerpig stuk hout, ijzer, steen enz., dat in de grond staat. __LET OP:__ Areaaldata maakt onderscheidt in objecten die een primaire functie hebben als draagconstructie, deze worden in paalDraagconstructie_P of mastDraagconstructie_p geadministreerd. Objecten die primair bedoelt zijn om iets af te bakenen worden in dit objecttype geadministreerd. Dit zijn o.a. Bermplanken, Indexeringspalen en Schamppalen. ![Bermplank](D:\git\bu_geodata_beheer\gereedschap\documentatie\areaaldata_datamodel\4.3d4\Objectbladen\06_Meubilair\bermplank.png)
* __Mapping_BGT:__ paal_p
* __Mapping_Gisib:__ Paal, Bermplank, Indexeringspaal
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__(oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                            	 |----          	      |-----    |
|OBJECTID                            |OID(38,0,0)             |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)        |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |TEXT(255,0,0)           |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)            |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BGTPLUSTYPE                         |TEXT(50,0,0)            |BGT; Nadere type omschrijving in de BGT; keuzelijst [typePAL](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typePAL.html); Nullable: False; Default: None; Visible: No|
|IDENTIFICATIE                       |TEXT(255,0,0)           |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)           |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.html); Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |DATE(8,0,0)             |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)             |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING              |SHORT(0,5,0)            |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                           |TEXT(255,0,0)           |PNH; Beheerder van het object; keuzelijst [BEHEERDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEERDER.html); Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)           |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ONDERHOUDER.html); Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |TEXT(255,0,0)           |PNH; Eigenaar van het object; keuzelijst [INSTANTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/INSTANTIE.html); Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |TEXT(255,0,0)           |PNH; Nadere typering van het object; keuzelijst [typeSpecPALAfbakening](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecPALAfbakening.html); Nullable: True; Default: None; Visible: Yes|
|MATERIAALTYPE                       |TEXT(255,0,0)           |PNH; Type materiaal; keuzelijst [MATERIAALTYPE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/MATERIAALTYPE.html); Nullable: True; Default: None; Visible: Yes|
|HECTOMETER                          |TEXT(255,0,0)           |PNH; Hectometrering; ; Nullable: True; Default: None; Visible: Yes|
|ZIJDE                               |TEXT(255,0,0)           |PNH; Zijde; keuzelijst [Zijde](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/Zijde.html); Nullable: True; Default: None; Visible: No|
|WILDREFLECTOR                       |TEXT(1,0,0)             |PNH; Wildreflector aanwezig, Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNeeOnbekend.html); Nullable: True; Default: O; Visible: No|
|ANTI_KERKUIL_ROL                    |TEXT(1,0,0)             |PNH; Aanwezigheid van een roller (al dan niet) ter voorkoming gebruik als zitplaats door kerkuilen (ter voorkoming van sterfte door aanrijding): Ja/Nee;	 keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.html);	 Nullable: False;	 Default: N;	 Visible: No|	
|DATUMPLAATSING                      |DATE(8,0,0)             |PNH; Datum plaatsing; ; Nullable: True; Default: None; Visible: No|
|LEVENSVERWACHTING                   |SHORT(0,5,0)            |PNH; Levensverwachting; ; Nullable: True; Default: None; Visible: No|
|PLANJAAR                            |SHORT(0,5,0)            |PNH; Planjaar; ; Nullable: True; Default: None; Visible: No|
|SNELHEID                            |SHORT(0,5,0)            |PNH; Snelheid aangegeven op het bord; ; Nullable: True; Default: None; Visible: No|
|TEKST                               |TEXT(255,0,0)           |PNH; Tekst aangegeven op het bord; ; Nullable: True; Default: None; Visible: Yes|
|TRAJECT                             |TEXT(255,0,0)           |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/TRAJECT_NAAM.html); Nullable: True; Default: None; Visible: Yes|
|DATALEVERANCIER                     |TEXT(255,0,0)           |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |TEXT(255,0,0)           |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|CREATED_USER                        |TEXT(255,0,0)           |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)             |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)            |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)             |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry(0,0,0)         |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|



***
