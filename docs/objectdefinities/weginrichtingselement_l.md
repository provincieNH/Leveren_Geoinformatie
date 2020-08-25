## AREAALDATA.weginrichtingselement_l

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH/IMGEO
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Lijn
* __Definitie:__ Een ruimtelijk object dat dient voor de inrichting van de openbare weg. __LET OP:__ Voornamelijk bedoelt om Geleideconstructies te administreren. Een geleiderail of vangrail is een barrière die naast wegen wordt geplaatst om te voorkomen 
dat voertuigen de weg in zijdelingse richting verlaten, kantelen of de middenberm doorkruisen
* __Mapping_BGT:__ weginrichtingselement_l
* __Mapping_Gisib:__ Geleiderail

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__(oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                            |----          	         |-----    |
|OBJECTID                          |OID(38,0,0)              |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                          |GlobalID(38,0,0)         |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                             |String(255,0,0)          |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                          |Integer(0,10,0)          |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                     |String(255,0,0)          |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                 |String(255,0,0)          |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.html); Nullable: False; Default: Nieuw; Visible: Yes|
|STATUS                            |String(10,0,0)           |BGT; BGT status van het object; keuzelijst [status](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/status.html); Nullable: False; Default: bestaand; Visible: No|
|OBJECTBEGINTIJD                   |Date(8,0,0)              |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                    |Date(8,0,0)              |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING            |SmallInteger(0,5,0)      |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                         |String(255,0,0)          |PNH; Beheerder van het object; keuzelijst [BEHEERDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEERDER.html); Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                       |String(255,0,0)          |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ONDERHOUDER.html); Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                          |String(255,0,0)          |PNH; Eigenaar van het object; keuzelijst [INSTANTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/INSTANTIE.html); Nullable: True; Default: None; Visible: Yes|
|BRONHOUDER                        |String(5,0,0)            |BGT; De bronhoudercode van het object; keuzelijst [bronhouder](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/bronhouder.html); Nullable: False; Default: None; Visible: No|
|TYPESPEC                          |String(255,0,0)          |PNH; Nadere typering van het object; keuzelijst [typeSpecWGILijn](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecWGILijn.html); Nullable: True; Default: None; Visible: Yes|
|BGTPLUSTYPE                       |String(50,0,0)           |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeWGILijn](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeWGILijn.html); Nullable: False; Default: None; Visible: No|
|ZIJDE                             |String(10,0,0)           |PNH; Zijde; keuzelijst [ZIJDE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ZIJDE.html); Nullable: True; Default: None; Visible: No|
|ANTIVERBLINDINGSSC                |String(1,0,0)            |PNH; AntiVerblindingsScherm: Ja/Nee; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.html); Nullable: True; Default: N; Visible: No|
|BEVESTIGING                       |String(255,0,0)          |PNH; Bevestiging; ; Nullable: True; Default: None; Visible: No|
|DATUMPLAATSING                    |Date(8,0,0)              |PNH; Datum Plaatsing; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                         |String(255,0,0)          |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|FUNDERING                         |String(255,0,0)          |PNH; Fundering; ; Nullable: True; Default: None; Visible: No|
|HMBEGIN                           |Float(0,25,10)           |PNH; Hectometrering in kilometers; ; Nullable: True; Default: None; Visible: No|
|HMEIND                            |Float(0,25,10)           |PNH; Hectometrering in kilometers; ; Nullable: True; Default: None; Visible: No|
|HOOGTESCHILD                      |String(30,0,0)           |PNH; Hoogte van het schild: kort 600mm / middel 900mm . Hoog 1200mm; ; Nullable: True; Default: None; Visible: Yes|
|MOTORVRIENDELIJK                  |String(1,0,0)            |PNH; MotorVriendelijk: Ja/Nee; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.html); Nullable: True; Default: N; Visible: No|
|PLANJAAR                          |SmallInteger(0,5,0)      |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|REFLECTOR                         |String(1,0,0)            |PNH; Reflector: Ja/Nee; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.html); Nullable: True; Default: N; Visible: Yes|
|RESTLEVENSDUUR                    |SmallInteger(0,5,0)      |PNH; Restlevensduur in maanden; ; Nullable: True; Default: None; Visible: No|
|MATERIAALTYPE                     |String(20,0,0)           |PNH; Materiaalkeuze; keuzelijst [MATERIAALTYPE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/MATERIAALTYPE.html); Nullable: True; Default: None; Visible: Yes|
|CEKEUR                            |String(255,0,0)          |PNH; CE-Keurmerk aanwezig; ; Nullable: True; Default: None; Visible: No|
|FOTO                              |String(255,0,0)          |PNH; Locatie van de foto op de S schijf bij PNH. Deze hoeft niet gevuld te worden door de aannemer; ; Nullable: True; Default: None; Visible: No|
|FABRIKANT                         |String(255,0,0)          |PNH; Fabrikant; ; Nullable: True; Default: None; Visible: No|
|TRAJECT                           |String(255,0,0)          |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/TRAJECT_NAAM.html); Nullable: True; Default: None; Visible: Yes|
|INONDERZOEK                       |String(1,0,0)            |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/jaNee.html); Nullable: False; Default: N; Visible: No|
|TIJDSTIPREGISTRATIE               |Date(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|EINDREGISTRATIE                   |Date(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|LV_PUBLICATIEDATUM                |Date(8,0,0)              |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|BERICHT_ID                        |String(128,0,0)          |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                   |String(255,0,0)          |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                      |String(255,0,0)          |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                      |Date(8,0,0)              |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                  |String(50,0,0)           |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                  |Date(8,0,0)              |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                             |Geometry                 |PNH; Lijn; ; Nullable: False; Default: None; Visible: Yes|
|SHAPE_Length                      |Double(0,0,0)           |PNH; Lengte in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|LENGTE                            |Double(0,0,0)           |PNH; Lengte in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|

***
