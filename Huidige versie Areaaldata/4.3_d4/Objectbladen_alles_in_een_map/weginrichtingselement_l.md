## AREAALDATA.weginrichtingselement_l

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH/IMGEO
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Lijn
* __Definitie:__ Een ruimtelijk object dat dient voor de inrichting van de openbare weg. __LET OP:__ Voornamelijk bedoelt om Geleideconstructies te administreren. Een geleiderail of vangrail is een barrière die naast wegen wordt geplaatst om te voorkomen 
dat voertuigen de weg in zijdelingse richting verlaten, kantelen of de middenberm doorkruisen
* __Mapping_BGT:__ weginrichtingselement_l
* __Mapping_Gisib:__ Geleiderail
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__(oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                            |----          	         |-----    |
|OBJECTID                          |OID(38,0,0)              |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                          |GlobalID(38,0,0)         |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                             |TEXT(255,0,0)            |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                          |LONG(0,10,0)             |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                 |TEXT(255,0,0)            |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                   |DATE(8,0,0)              |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                    |DATE(8,0,0)              |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING            |SHORT(0,5,0)             |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                         |TEXT(255,0,0)            |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                       |TEXT(255,0,0)            |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                          |TEXT(255,0,0)            |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|JAARAANLEG                        |SHORT(0,5,0)             |PNH; Jaar aanleg van de weg; ; Nullable: True; Default: None; Visible: No|
|JAARDEKLAAG                       |SHORT(0,5,0)             |PNH; Jaar deklaag gelegd; ; Nullable: True; Default: None; Visible: No|
|JAARHERSTRATEN                    |SHORT(0,5,0)             |PNH; Jaar Herbestrating gelegd; ; Nullable: True; Default: None; Visible: No|
|SITUERING                         |TEXT(255,0,0)            |PNH; Situering conform CROW (L: Links, M: Midden en R: Rechts); keuzelijst [SITUERING]; Nullable: True; Default: None; Visible: Yes|
|GEBRUIKSFUNCTIE                   |TEXT(255,0,0)            |PNH; Gebruiksfunctie conform CROW; keuzelijst [GEBRUIKSFUNCTIE]; Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                          |TEXT(255,0,0)            |PNH; Nadere typering van het object; keuzelijst [typeSpecWGILijn]; Nullable: True; Default: None; Visible: Yes|
|BGTPLUSTYPE                       |TEXT(50,0,0)             |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeWGILijn]; Nullable: False; Default: None; Visible: No|
|ZIJDE                             |TEXT(10,0,0)             |PNH; Zijde; keuzelijst [Zijde]; Nullable: True; Default: None; Visible: No|
|ANTIVERBLINDINGSSC                |TEXT(1,0,0)              |PNH; AntiVerblindingsScherm: Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|BEVESTIGING                       |TEXT(255,0,0)            |PNH; Bevestiging; ; Nullable: True; Default: None; Visible: No|
|DATUMPLAATSING                    |DATE(8,0,0)              |PNH; Datum Plaatsing; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                         |TEXT(255,0,0)            |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|FUNDERING                         |TEXT(255,0,0)            |PNH; Fundering; ; Nullable: True; Default: None; Visible: No|
|HMBEGIN                           |FLOAT(0,25,10)           |PNH; Hectometrering in kilometers; ; Nullable: True; Default: None; Visible: No|
|HMEIND                            |FLOAT(0,25,10)           |PNH; Hectometrering in kilometers; ; Nullable: True; Default: None; Visible: No|
|HOOGTESCHILD                      |TEXT(30,0,0)             |PNH; Hoogte van het schild: kort 600mm / middel 900mm . Hoog 1200mm; ; Nullable: True; Default: None; Visible: Yes|
|MOTORVRIENDELIJK                  |TEXT(1,0,0)              |PNH; MotorVriendelijk: Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|PLANJAAR                          |SHORT(0,5,0)             |PNH; Het geplande jaar dat het object vervangen wordt; ; Nullable: True; Default: None; Visible: No|
|REFLECTOR                         |TEXT(1,0,0)              |PNH; Reflector: Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N; Visible: Yes|
|RESTLEVENSDUUR                    |SHORT(0,5,0)             |PNH; Restlevensduur in maanden; ; Nullable: True; Default: None; Visible: No|
|MATERIAALTYPE                     |TEXT(20,0,0)             |PNH; Materiaalkeuze; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None; Visible: Yes|
|CEKEUR                            |TEXT(255,0,0)            |PNH; CE-Keurmerk aanwezig; ; Nullable: True; Default: None; Visible: No|
|FOTO                              |TEXT(255,0,0)            |PNH; Locatie van de foto op de S schijf bij PNH. Deze hoeft niet gevuld te worden door de aannemer; ; Nullable: True; Default: None; Visible: No|
|FABRIKANT                         |TEXT(255,0,0)            |PNH; Fabrikant; ; Nullable: True; Default: None; Visible: No|
|TRAJECT                           |TEXT(255,0,0)            |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM]; Nullable: True; Default: None; Visible: Yes|
|DATALEVERANCIER                   |TEXT(255,0,0)            |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                      |TEXT(255,0,0)            |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                      |DATE(8,0,0)              |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                  |TEXT(50,0,0)             |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                  |DATE(8,0,0)              |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                             |Geometry                 |PNH; Lijn; ; Nullable: False; Default: None; Visible: Yes|
|SHAPE_Length                      |DOUBLE(0,0,0)            |PNH; Lengte in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|LENGTE                            |DOUBLE(0,0,0)            |PNH; Lengte in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|

***
