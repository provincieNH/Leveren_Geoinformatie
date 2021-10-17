## AREAALDATA.plaaginvasiesoortInspectie_p

*Feature dataset: -*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Geen
* __Definitie:__ Inspectieobject met alle inspectiegegevens die ingewonnen zijn m.b.t. plaaginvasiesoorten. Invasieve soorten zijn soorten die zich buiten hun oorspronkelijke verspreidingsgebied hebben gevestigd en door hun aanwezigheid of door de groei van hun populaties een bedreiging vormen voor inheemse soorten. Invasieve soorten kunnen een bedreiging vormen voor de biodiversiteit. 
(landschap en milieu)
* __Mapping_NTA8035:__ bs:InformationObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                  |-----    |
|VERWERKINGSSTATUS                   |TEXT(255,0,0)         |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|INVASIESOORT                        |TEXT(255,0,0)         |PNH; Waargenomen invasieve soort; keuzelijst [INVASIEVE_SOORT]; Nullable: True; Default: None; Visible: No|
|BESTRIJDING                         |TEXT(1,0,0)           |PNH; Bestijding nodig? (Ja/Nee); keuzelijst [jaNee]; Nullable: True; Default: N; Visible: No|
|TYPE_BESTRIJDING                    |TEXT(255,0,0)         |PNH; De soort bestrijdingsmethode; keuzelijst [TYPE_BESTRIJDING]; Nullable: True; Default: None; Visible: No|
|AANGETAST_OPPERVLAKTE               |TEXT(255,0,0)         |PNH; De aangetaste oppervlakte in m2's;; Nullable: True; Default: None; Visible: No|
|DATUM_INSPECTIE                     |DATE(8,0,0)           |PNH; Datum van inspectie; ; Nullable: True; Default: None; Visible: No|
|ONDERHOUDER                         |TEXT(255,0,0)         |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible: No|
|BEHEERDER                           |TEXT(255,0,0)         |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible: Yes|
|TRAJECT                             |TEXT(255,0,0)         |PNH; Verwijzende sleutel naar traject_v (simpel); keuzelijst [TRAJECT_NAAM]; Nullable: True; Default: None; Visible: No|
|ZIJDE                               |TEXT(10,0,0)          |PNH; Zijde; keuzelijst [ZIJDE]; Nullable: True; Default: None; Visible: No|
|OBJECTID                            |OID(38,0,0)           |PNH; Interne ID ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)      |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |TEXT(255,0,0)         |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; ; Nullable: False; Default: None; Visible: Yes|
|OBJECTBEGINTIJD                     |DATE(8,0,0)           |PNH; Datum waarop het object bij de opdrachtgever is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)           |PNH; Datum waarop de plaagsoort niet meer voorkomt op de betreffende locatie; ; Nullable: True; Default: None; Visible: Yes|
|OPMERKING                           |TEXT(255,0,0)         |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|CREATED_USER                        |TEXT(255,0,0)         |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)           |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)          |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)           |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry(0,0,0)       |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|


***

