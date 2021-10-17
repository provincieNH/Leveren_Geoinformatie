## AREAALDATA.kast_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Object met een permanent karakter dat dient om iets in te bergen en te beschermen. __LET OP:__ OVL- en VRI-Kasten worden apart geadministreerd.
* __Mapping_BGT:__ kast_p
* __Mapping_Gisib:__ GMS Kast, Kast, Telkast
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__(oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                            |----          	       |-----    |
|OBJECTID                          |OID(38,0,0)            |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                          |GlobalID(38,0,0)       |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                             |TEXT(255,0,0)          |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                          |LONG(0,10,0)           |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                 |TEXT(255,0,0)          |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                   |DATE(8,0,0)            |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                    |DATE(8,0,0)            |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING            |SHORT(0,5,0)           |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                         |TEXT(255,0,0)          |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                       |TEXT(255,0,0)          |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                          |TEXT(255,0,0)          |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible: Yes|
|BGTPLUSTYPE                       |TEXT(50,0,0)           |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeKST]; Nullable: False; Default: None; Visible: No|
|TYPESPEC                          |TEXT(255,0,0)          |PNH; Nadere typering van het object; keuzelijst [typeSpecKST]; Nullable: True; Default: None; Visible: Yes|
|DATALEVERANCIER                   |TEXT(255,0,0)          |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|ZIJDE                             |TEXT(10,0,0)           |PNH; Zijde; keuzelijst [ZIJDE]; Nullable: True; Default: None; Visible: No|
|OPMERKING                         |TEXT(255,0,0)          |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|HECTOMETER                        |TEXT(255,0,0)          |PNH; Hectometrering; ; Nullable: True; Default: None; Visible: Yes|
|FABRIKANT                         |TEXT(255,0,0)          |PNH; Fabrikant; ; Nullable: True; Default: None; Visible: No|
|ENERGIELEVERANCIER                |TEXT(255,0,0)          |PNH; Energieleverancier (opmerking: attribuut wordt nog niet gevuld); ; Nullable: True; Default: None; Visible: No|
|DATUMGARANTIE                     |DATE(8,0,0)            |PNH; Datum en jaartal tot wanneer de garantie geldig is; ; Nullable: True; Default: None; Visible: No|
|DATUMPLAATSING                    |DATE(8,0,0)            |PNH; Datum plaatsing; ; Nullable: True; Default: None; Visible: No|
|SIMNUMMER                         |TEXT(20,0,0)           |PNH; Nummer van de SIM kaart; ; Nullable: True; Default: None; Visible: Yes|
|AANTALLUSSEN                      |TEXT(255,0,0)          |PNH; Aantal lussen dat in het asfalt is aangelegd voor verkeertellingen; ; Nullable: True; Default: None; Visible: No|
|DATATRANSPORT                     |TEXT(255,0,0)          |PNH; Manier van datatransport. Keuze uit:Vaste lijn (KPN lijn), GSM; ; Nullable: True; Default: None; Visible: No|
|GSMNUMMER                         |TEXT(255,0,0)          |PNH; GSM nummer dat gekoppeld is aan de betreffende SIM kaart; ; Nullable: True; Default: None; Visible: Yes|
|GMS_NAAM                          |TEXT(255,0,0)          |PNH; Naam van het GMS; ; Nullable: True; Default: None; Visible: Yes|
|TELPUNTCODE                       |TEXT(255,0,0)          |PNH; Administratieve code om de ligging van de telkast/telpaal aan te duiden; ; Nullable: True; Default: None; Visible: Yes|
|NDW_CODE                          |TEXT(255,0,0)          |PNH; Administratieve code van het NDW; ; Nullable: True; Default: None; Visible: Yes|
|VOEDING                           |TEXT(255,0,0)          |PNH; Manier van energieverzorging. Keuze uit:220, Zonne-energie; ; Nullable: True; Default: None; Visible: No|
|MATERIAALTYPE                     |TEXT(255,0,0)          |PNH; Type materiaal; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None; Visible: Yes|
|ADRES                             |TEXT(255,0,0)          |PNH; Verwijzende sleutel naar adres_tbl (simpel); ; Nullable: True; Default: None; Visible: No|
|INNETWERK                         |TEXT(255,0,0)          |PNH; Verwijzende sleutel naar utiliteitsNet_tbl (simpel); ; Nullable: True; Default: None; Visible: No|
|TRAJECT                           |TEXT(255,0,0)          |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM]; Nullable: True; Default: None; Visible: Yes|
|CREATED_USER                      |TEXT(255,0,0)          |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                      |DATE(8,0,0)            |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                  |TEXT(50,0,0)           |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                  |DATE(8,0,0)            |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                             |Geometry(0,0,0)        |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|


***
