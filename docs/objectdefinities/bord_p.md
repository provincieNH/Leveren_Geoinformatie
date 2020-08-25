## AREAALDATA.bord_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH/IMGEO
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Een paneel waarop informatie wordt afgebeeld. Dit zijn zowel RVV borden als matrix borden (voor automobilisten);  DRIP panelen zijn in Areaaldata te vinden als matrix borden met een TOPdesk ID
__LET OP:__ Bebording voor scheepvaartverkeer, wegwijzers, zwemwaterbebording en DRIS Panelen (voor OV reizigers) worden apart geadministreerd.
* __Mapping_BGT:__ bord_p
* __Mapping_Gisib:__ Bord, Matrix


***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__(oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                          	 |----          	    |-----    |
|OBJECTID                            |OID(38,0,0)           |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)      |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: No|
|AD_ID                               |String(255,0,0)       |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |Integer(0,10,0)       |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                       |String(255,0,0)       |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |String(255,0,0)       |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.html); Nullable: False; Default: Nieuw; Visible: Yes|
|STATUS                              |String(10,0,0)        |BGT; BGT status van het object; keuzelijst [status](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/status.html); Nullable: False; Default: bestaand; Visible: No|
|OBJECTBEGINTIJD                     |Date(8,0,0)           |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)           |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING              |SmallInteger(0,5,0)   |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: No|
|BEHEERDER                           |String(255,0,0)       |PNH; Beheerder van het object; keuzelijst [BEHEERDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEERDER.html); Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |String(255,0,0)       |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ONDERHOUDER.html); Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |String(255,0,0)       |PNH; Eigenaar van het object; keuzelijst [INSTANTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/INSTANTIE.html); Nullable: True; Default: None; Visible: Yes|
|BRONHOUDER                          |String(5,0,0)         |BGT; De bronhoudercode van het object; keuzelijst [bronhouder](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/bronhouder.html); Nullable: False; Default: None; Visible: No|
|TYPESPEC                            |String(255,0,0)       |PNH; Nadere typering van het object; keuzelijst [typeSpecBRD](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecBRD.html); Nullable: True; Default: None; Visible: Yes|
|BGTPLUSTYPE                         |String(50,0,0)        |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeBRD](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeBRD.html); Nullable: False; Default: None; Visible: No|
|MATERIAALTYPE                       |String(255,0,0)       |PNH; Materiaalkeuze; keuzelijst [MATERIAALTYPE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/MATERIAALTYPE.html); Nullable: True; Default: None; Visible: No|
|REFLECTIEKLASSE                     |String(255,0,0)       |PNH; Reflectieklasse; keuzelijst [REFLECTIEKLASSE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/REFLECTIEKLASSE.html); Nullable: True; Default: None; Visible: Yes|
|RVVTYPEBORD                         |String(255,0,0)       |PNH; RVV Type Bord; ; Nullable: True; Default: None; Visible: Yes|
|BEVESTIGINGSWIJZE                   |String(255,0,0)       |PNH; BevestigingsWijze; keuzelijst [BEVESTIGINGSWIJZE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEVESTIGINGSWIJZE.html); Nullable: True; Default: None; Visible: No|
|AFMETINGEN                          |String(255,0,0)       |PNH; Afmeting klasse opgeven, indien afwijkend in mm; ; Nullable: True; Default: None; Visible: No|
|DATUMPLAATSING                      |Date(8,0,0)           |PNH; Datum Plaatsing; ; Nullable: True; Default: None; Visible: No|
|HECTOMETER                          |String(255,0,0)       |PNH; Hectometrering; ; Nullable: True; Default: None; Visible: No|
|MAXIMUMSNELHEIDGEM                  |String(1,0,0)         |PNH; MaximunSnelheidGemeld: veld om aan te geven als de toegestane max. snelheid is gemeld op het (hectometerings)bord: Ja/Nee/Onbekend; keuzelijst [jaNeeOnbekend](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNeeOnbekend.html); Nullable: True; Default: O; Visible: No|
|PLANJAAR                            |SmallInteger(0,5,0)   |PNH; Planjaar TODO; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |String(255,0,0)       |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|TOPDESK_ID                          |String(255,0,0)       |PNH; Verwijzing naar ObjectID TOPdesk; ; Nullable: True; Default: None; Visible: No|
|HALTE                               |String(255,0,0)       |PNH; Verwijzende sleutel naar halte_v (simpel); ; Nullable: True; Default: None; Visible: No|
|TRAJECT                             |String(255,0,0)       |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/TRAJECT_NAAM.html); Nullable: True; Default: None; Visible: Yes|
|UITLEGGERPORTAAL                    |String(255,0,0)       |PNH; Verwijzende sleutel naar uitleggerPortaal_l (simpel); ; Nullable: True; Default: None; Visible: No|
|PAAL                                |String(255,0,0)       |PNH; Verwijzende sleutel naar paalDraagconstructie_p (simpel); ; Nullable: True; Default: None; Visible: No|
|INONDERZOEK                         |String(1,0,0)         |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.html); Nullable: False; Default: N; Visible: No|
|TIJDSTIPREGISTRATIE                 |Date(8,0,0)           |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|EINDREGISTRATIE                     |Date(8,0,0)           |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; ; Nullable: Tru; Default: None; Visible: No|
|LV_PUBLICATIEDATUM                  |Date(8,0,0)           |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BERICHT_ID                          |String(128,0,0)       |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |String(255,0,0)       |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)           |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)        |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)           |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |String(255,0,0)       |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry(0,0,0)       |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|

***
