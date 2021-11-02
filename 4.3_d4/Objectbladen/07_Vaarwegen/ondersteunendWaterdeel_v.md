## AREAALDATA.ondersteunendWaterdeel_v

*Feature dataset: Opdelend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Ja
* __Herkomst Definitie:__ BGT/PNH
* __Positionele nauwkeurigheid:__ 25 cm
* __Geometrie:__ Vlak
* __Definitie:__ Object dat in het kader van de waterhuishouding periodiek gedeeltelijk of geheel met water is bedekt. Een vegetatie van voornamelijk riet en andere soorten langs een waterloop. In breedte variabel van 0,50 tot 3,00 meter.  De Provincie heeft voornamelijk oevers en slootkanten in het areaal. Oevers en slootkanten zijn de delen die enerzijds begrensd worden door de waterlijn en anderzijds door een kant insteek. Een kantinsteek heeft altijd een bijbehorende taludlijn en hoeft niet te worden ingetekend.
* __Mapping_BGT:__ ondersteunendWaterdeel_v
* __Mapping_Gisib:__ Oeverbescherming, Plasberm
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                          	|----          	          |-----    |
|OBJECTID                           |OID(38,0,0)              |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                           |GlobalID(38,0,0)         |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                              |TEXT(255,0,0)            |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                           |LONG(0,10,0)             |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                      |TEXT(255,0,0)            |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                  |TEXT(255,0,0)            |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|STATUS                             |TEXT(10,0,0)             |BGT; BGT status van het object; keuzelijst [Status]; Nullable: False; Default: bestaand; Visible: No|
|OBJECTBEGINTIJD                    |DATE(8,0,0)              |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                     |DATE(8,0,0)              |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING             |SHORT(0,5,0)             |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                          |TEXT(255,0,0)            |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                        |TEXT(255,0,0)            |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                           |TEXT(255,0,0)            |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|BRONHOUDER                         |TEXT(5,0,0)              |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None; Visible: No|
|TYPESPEC                           |TEXT(255,0,0)            |PNH; Nadere typering van het object; keuzelijst [typeSpecOWA]; Nullable: True; Default: None; Visible: Yes|
|BGTPLUSTYPE                        |TEXT(50,0,0)             |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeOWT]; Nullable: False; Default: None; Visible: No|
|TYPE_BEHEER                        |TEXT(50,0,0)             |PNH; Type beheer (maaien, klepelen, uitzuigen etc); keuzelijst [TYPE_BEHEER]; Nullable: True; Default: None; Visible: No|
|TYPEBODEM                          |TEXT(255,0,0)            |PNH; Type bodem; ; Nullable: True; Default: None; Visible: No|
|TYPEPLAAGSOORT                     |TEXT(255,0,0)            |PNH; Type plaagsoort. De soort wordt  ingevuld die geschat qua oppervlak het meeste voorkomt in dat perceel; keuzelijst [TYPE_PLAAGSOORT_WATER]; Nullable: True; Default: None; Visible: Yes|
|ACTUEELBEELD                       |TEXT(255,0,0)            |PNH; Huidige beeld; ; Nullable: True; Default: None; Visible: No|
|BREEDTE                            |FLOAT(0,25,10)           |PNH; Breedte van de plasberm in m, 2 decimalen; ; Nullable: True; Default: None; Visible: No|
|JAAR_PLAATSING_AANLEG_GESCHAT      |TEXT(1,0,0)              |PNH; Jaar plaatsing of aanleg is geschat: ja of nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|OPMERKING                          |TEXT(255,0,0)            |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|HMBEGIN                            |FLOAT(0,25,10)           |PNH; Hectometrering begin ondersteunendWaterdeel; ; Nullable: True; Default: None; Visible: No|
|HMEIND                             |FLOAT(0,25,10)           |PNH; Hectometrering eind ondersteunendWaterdeel; ; Nullable: True; Default: None; Visible: No|
|LENGTE_VLAK                        |FLOAT(0,10,0)            |PNH; Lengte oever in hele meters, scriptmatig bepaald obv lengterichting waterdeel; ; Nullable: True; Default: None; Visible: Yes|
|PLANJAAR                           |SHORT(0,5,0)             |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|STREEFBEELD                        |TEXT(255,0,0)            |PNH; Concrete visuele doelstelling; ; Nullable: True; Default: None; Visible: No|
|ZIJDE                              |TEXT(10,0,0)             |PNH; Zijde; keuzelijst [ZIJDE]; Nullable: True; Default: None; Visible: No|
|OEVERVAK                           |TEXT(255,0,0)            |PNH; Verwijzende sleutel naar oevervak_v (simpel); ; Nullable: True; Default: None; Visible: Yes|
|TRAJECT                            |TEXT(255,0,0)            |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM]; Nullable: True; Default: None; Visible: Yes|
|INONDERZOEK                        |TEXT(1,0,0)              |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible: No|
|TIJDSTIPREGISTRATIE                |DATE(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|EINDREGISTRATIE                    |DATE(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|LV_PUBLICATIEDATUM                 |DATE(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BERICHT_ID                         |TEXT(128,0,0)            |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                    |TEXT(255,0,0)            |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                       |TEXT(255,0,0)            |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                       |DATE(8,0,0)              |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                   |TEXT(50,0,0)             |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                   |DATE(8,0,0)              |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                              |Geometry(0,0,0)          |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                       |DOUBLE(0,0,0)            |PNH; Omtrek in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|SHAPE_Area                         |DOUBLE(0,0,0)            |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|OMTREK                             |DOUBLE(0,0,0)            |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|
|OPPERVLAKTE                        |DOUBLE(0,0,0)            |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Area; ; Nullable: False; Default: None; Visible: Yes|



***
