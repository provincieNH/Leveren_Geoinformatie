## AREAALDATA.vtaInspectie_tbl

*Feature dataset: -*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Geen
* __Definitie:__ Wettelijk verplichte inspectie van de veiligheid van bomen
* __Mapping_NTA8035:__ bs:InformationObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__ (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                |-----    |
|VERWERKINGSSTATUS                   |TEXT(255,0,0)       |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible: Yes|
|DATUM                               |DATE(8,0,0)         |PNH; Datum Inspectie; ; Nullable: True; Default: None; Visible: No|
|INSPECTEUR                          |TEXT(255,0,0)       |PNH; Naam van de Inspecteur; ; Nullable: True; Default: None; Visible: No|
|OPMERKING                           |TEXT(3000,0,0)      |PNH; Extra toelichting; ; Nullable: True; Default: None; Visible: No|
|OPMERKING2                          |TEXT(3000,0,0)      |PNH; Extra toelichting m.b.t. kroonschade etc; ; Nullable: True; Default: None; Visible: No|
|VTA_GEBREK                          |TEXT(255,0,0)       |PNH; Betreft visueel waarneembare kenmerken die (mogelijk) een negatieve invloed hebben op de boomveiligheid; keuzelijst [VTA_GEBREK]; Nullable: True; Default: None; Visible: No|
|VTA_HERKEURING                      |TEXT(255,0,0)       |PNH; Gewenst moment of termijn van de volgende boomveiligheidscontrole; keuzelijst [VTA_HERKEURING]; Nullable: True; Default: None; Visible: No|
|VTA_NADER_TECHN_ONDERZOEK           |TEXT(255,0,0)       |PNH; Uitvoeren van Nader Technisch Onderzoek door bijv. de inzet van specialistische meetapparatuur of onderzoek op hoogte; keuzelijst [VTA_NTO]; Nullable: True; Default: None; Visible: No|
|VTA_FLORA                           |TEXT(255,0,0)       |PNH; Aanwezigheid nesten, vleermuizen e.d.; ; Nullable: True; Default: None; Visible: No|
|VTA_URGENTIE_NTO                    |TEXT(255,0,0)       |PNH; Gewenst moment of termijn van de NTO (e.e.a. houdt verband met de aard en omvang van de geconstateerde gebreken en de standplaats); keuzelijst [VTA_NTO_URGENTIE]; Nullable: True; Default: None; Visible: No|
|VTA_RISICO                          |TEXT(255,0,0)       |PNH; Klasse van het risico wat een gebrek met zich mee kan brengen; keuzelijst [VTA_RISICO]; Nullable: True; Default: None; Visible: No|
|BOOM                                |TEXT(255,0,0)       |PNH; Verwijzende sleutel naar vegetatieObject_p (simpel); ; Nullable: True; Default: None; Visible: No|
|IDENTIFICATIE                       |TEXT(255,0,0)       |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; ; Nullable: True; Default: None; Visible: No|
|OBJECTID                            |OID(38,0,0)         |PNH; Interne ID ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)    |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)        |PNH; ID beheer openbare ruimte (GISIB); ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |TEXT(255,0,0)       |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|AD_ID                               |TEXT(255,0,0)       |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'; ; Nullable: False; Default: None; Visible: Yes|
|OBJECTBEGINTIJD                     |DATE(8,0,0)         |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)         |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|CREATED_USER                        |TEXT(255,0,0)       |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)         |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)        |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)         |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CONTROLE_POSITIE_BOOMPUNT           |TEXT(255,0,0)       |NIB; Is de boom juist ingemeten/staat de punt op de juiste plaats; keuzelijst [CONTROLEBOOMPUNT]; Nullable: True; Default: None; Visible: No|
|BOOMGROOTTE                         |TEXT(255,0,0)       |NIB; Een classificatie die aangeeft hoe groot een boomsoort in NL kan worden. 1e grootte is >15 m, 2e grootte is 8-15 m en 3e grootte is tot 8 m.; keuzelijst [BOOMGROOTTE]; Nullable: True; Default: None; Visible: No|
|BOOMHOOGTEKLASSE                    |TEXT(255,0,0)       |NIB; Op grond van de actuele boomhoogte.; keuzelijst [BOOMHOOGTEKLASSE]; Nullable: True; Default: None; Visible: No|
|CONDITIE_EN_GROEI                   |TEXT(255,0,0)       |NIB; Actuele groeiontwikkeling op grond van huidige groei(kracht) en gezondheid, gebaseerd op visuele groeikenmerken. Groeikenmerken waaronder: ontwikkeling kroonstuctuur, primaire groei (dominatie doorgaande spil), scheutlengten, wondovergroeiing, knopbezetting, bladbezetting, bladgrootte en bladkleur. En ziekten en aantastingen die primair invloed hebben op de actuele gezondheid (groeiontwikkeling) van de boom.; keuzelijst [CONDITIEGROEI]; Nullable: True; Default: None; Visible: No|
|OPKROONHOOGTE_ACTUEEL               |TEXT(255,0,0)       |NIB; De actuele takvrije stam van maaiveld tot de eerste takaanzet;  keuzelijst [OPKROONHOOGTE]; Nullable: True; Default: None; Visible: No|
|TOEKOMSTVERWACHTING                 |TEXT(255,0,0)       |NIB; Verwachte technische levensduur op grond van boomtechnische aspecten (onderandere conditie, groeiontwikkelig, ziektes, aantastingen of boomtechnische gebreken).; keuzelijst [TOEKOMSTVERWACHTING]; Nullable: True; Default: None; Visible: No|
|BOOMBEELD                           |TEXT(255,0,0)       |NIB; Gebaseerd op de actuele onderhoudsstaat en gerelateerd aan de benodigde snoeiingreep om tot een aanvaard boombeeld te (kunnen) komen. Een boom met een aanvaard boombeeld dient niet gesnoeid te worden. Bij een verwaarloosd boombeeld (niet van toepassing bij vormsnoei) is de benodigde snoeiingreep als gevolg van verwaarloosd onderhoud, zodanig omvangrijk dat deze gefaseerd moet plaatsvinden.; keuzelijst [BOOMBEELD]; Nullable: True; Default: None; Visible: No|
|SPECIFIEKE_ONDERHOUDSMAATREGEL      |TEXT(255,0,0)       |NIB; Aanvullende (relevante) specefieke maatregelen die nu of in de komende beheerperiode benodigd zijn.; keuzelijst [SPECONDERHOUDSMAATREGEL]; Nullable: True; Default: None; Visible: No|
|BOOMONDERDEEL                       |TEXT(255,0,0)       |NIB; Vermelden waar (plaatsaanduidling) gebrek(en) is/zijn aangetroffen.; keuzelijst [BOOMONDERDEEL]; Nullable: True; Default: None; Visible: No|
***
