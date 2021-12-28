## AREAALDATA.kunstwerkdeel_l

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ IMGeo BGT 
* __Positionele nauwkeurigheid:__ 5 cm
* __Geometrie:__ Lijn
* __Definitie:__ Onderdeel van een civiel-technisch werk voor de infrastructuur van wegen, water, spoorbanen, waterkeringen en/of leidingen met een breedte <30cm, bijvoorbeeld een duiker.
* __Mapping_BGT:__ kunstwerkdeel_l
* __Mapping_Gisib:__ Overig kunstwerk
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                            |----          	        |-----    |
|OBJECTID                          |OID(38,0,0)             |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                          |GlobalID(38,0,0)        |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: No|
|AD_ID                             |TEXT(255,0,0)           |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                          |LONG(0,10,0)            |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                     |TEXT(255,0,0)           |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                 |TEXT(255,0,0)           |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|STATUS                            |TEXT(10,0,0)            |BGT; BGT status van het object; keuzelijst [Status]; Nullable: False; Default: bestaand; Visible: No|
|OBJECTBEGINTIJD                   |DATE(8,0,0)             |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                    |DATE(8,0,0)             |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING            |SHORT(0,5,0)            |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                         |TEXT(255,0,0)           |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                       |TEXT(255,0,0)           |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                          |TEXT(255,0,0)           |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|BRONHOUDER                        |TEXT(5,0,0)             |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None; Visible: No|
|TYPESPEC                          |TEXT(255,0,0)           |PNH; Nadere typering van het object; keuzelijst [typeSpecKWDLijn]; Nullable: True; Default: None; Visible: Yes|
|BGTPLUSTYPE                       |TEXT(50,0,0)            |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeKWDLijn]; Nullable: False; Default: None; Visible: No|
|NENBEHEEROBJECT                   |TEXT(255,0,0)           |PNH; NENBEHEEROBJECT; keuzelijst [NENBEHEEROBJECT]; Nullable: True; Default: None; Visible: Yes|
|CONFORMNEN                        |TEXT(1,0,0)             |PNH; Indicatie of classificatie conform NEN is; keuzelijst [jaNeeOnbekend]; Nullable: True; Default: O; Visible: No|
|OPMERKING                         |TEXT(255,0,0)           |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|KILOMETRERING                     |FLOAT(0,25,10)          |PNH; Aanduiding Kilometrering ligging kunstwerk; ; Nullable: True; Default: None; Visible: Yes|
|KWLENGTE                          |FLOAT(0,25,10)          |PNH; Totale lengte kunstwerk; ; Nullable: True; Default: None; Visible: Yes|
|RENOVATIEJAAR                     |SHORT(0,5,0)            |PNH; Renovatiejaar; ; Nullable: True; Default: None; Visible: No|
|DIAMETER                          |SHORT(0,5,0)            |PNH; Diameter (mm), indien ronde duiker; ; Nullable: True; Default: None; Visible: Yes|
|HOOGTE                            |FLOAT(0,10,2)           |PNH; Hoogte (m, 2 decimalen), indien rechthoekige duiker; ; Nullable: True; Default: None; Visible: Yes|
|BREEDTE                           |FLOAT(0,10,2)           |PNH; Breedte (m, 2 decimalen), indien rechthoekige duiker; ; Nullable: True; Default: None; Visible: No|
|PROFIEL                           |TEXT(255,0,0)           |PNH; Vorm doorstroomprofiel van duiker; ; Nullable: True; Default: None; Visible: No|
|BOUWJAAR                          |SHORT(0,5,0)            |PNH; Bouwjaar; ; Nullable: True; Default: None; Visible: Yes|
|MATERIAALTYPE                     |TEXT(255,0,0)           |PNH; Materiaaltype; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None; Visible: Yes|
|GEMEENTE                          |TEXT(255,0,0)           |PNH; Gemeente naam; keuzelijst [GEMEENTE]; Nullable: True; Default: None; Visible: No|
|DUIKERBINNENONDERK                |FLOAT(0,25,10)          |PNH; Hoogte t.o.v. NAP van binnen onderkant buis (bij duiker); ; Nullable: True; Default: None; Visible: No|
|GEDEELDBEHEER                     |TEXT(255,0,0)           |PNH; Indien van toepassing, tweede beheerder van het object; keuzelijst [GEDEELD_BEHEER]; Nullable: True; Default: None; Visible: No|
|VAARWEG                           |TEXT(255,0,0)           |PNH; Verwijzende sleutel naar vaarweg_l (simpel); ; Nullable: True; Default: None; Visible: No|
|TRAJECT                           |TEXT(255,0,0)           |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM]; Nullable: True; Default: None; Visible: Yes|
|DATALEVERANCIER                   |TEXT(255,0,0)           |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|INONDERZOEK                       |TEXT(1,0,0)             |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible: No|
|TIJDSTIPREGISTRATIE               |DATE(8,0,0)             |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|EINDREGISTRATIE                   |DATE(8,0,0)             |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|LV_PUBLICATIEDATUM                |DATE(8,0,0)             |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BERICHT_ID                        |TEXT(128,0,0)           |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                      |TEXT(255,0,0)           |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                      |DATE(8,0,0)             |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                  |TEXT(50,0,0)            |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                  |DATE(8,0,0)             |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                             |Geometry(0,0,0)         |PNH; Lijn; ; Nullable: False; Default: None; Visible: Yes|
|SHAPE_Length                      |DOUBLE(0,0,0)           |PNH; Lengte in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|LENGTE                            |DOUBLE(0,0,0)           |PNH; Lengte in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|


***
