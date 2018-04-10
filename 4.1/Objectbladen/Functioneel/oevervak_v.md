﻿## AREAALDATA.oevervak_v

$ Feature dataset: Functioneel



* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt
* __SHAPE:__ Vlak
* __Definitie:__ Een Oevervak is de rand van een kanaal, vaarweg of rivier. Het begint bij bodem van het nautisch profiel en gaat door tot 10m achter de oeverconstructie. __NB:__ Dit is het equivalent van Beheerobject bij Vaarwegen conform de NEN 2767-4 Decompositie. Een oevervak is ongeveer 100 meter lang en bestaat uit een uniforme oeverconstructie.

De Oeverconstructie zelf is vastgelegd in [AREAALDATA.scheidingOevervak_l] en [AREAALDATA.bouwdeelOevervak_tbl]


***

|KOLOM                               |TYPE                 |DEFINITIE|
|------                              |----                 |-----    |
|OBJECTID                            |OID(38,0,0)          |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None|
|GLOBALID                            |GlobalID(38,0,0)     |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None|
|AD_ID                               |String(255,0,0)      |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None|
|GISIB_ID                            |Integer(0,10,0)      |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer.; Nullable: True; Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)      |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|OBJECTBEGINTIJD                     |Date(8,0,0)          |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)          |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|BEHEERDER                           |String(255,0,0)      |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None|
|ONDERHOUDER                         |String(255,0,0)      |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None|
|EIGENAAR                            |String(255,0,0)      |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None|
|TYPESPEC                            |String(255,0,0)      |PNH; Nadere typering van het object; keuzelijst [typeSpecOEV]; Nullable: True; Default: None|
|ZIJDE                               |String(255,0,0)      |PNH; Zijde; keuzelijst [ZIJDE]; Nullable: True; Default: None|
|OMSCHRIJVING                        |String(255,0,0)      |PNH; Extra toelichting; Nullable: True; Default: None|
|GEBRUIK                             |String(255,0,0)      |PNH; Daadwerkelijk gebruik vd oever; Nullable: True; Default: None|
|HMBEGIN                             |Float(0,25,10)       |PNH; Begin Hectometrering van Oevervak; Nullable: True|
|HMEIND                              |Float(0,25,10)       |PNH; Eind Hectometrering van Oevervak; Nullable: True|
|LENGTE                              |Float(0,10,0)        |PNH; Lengte van het oevervak in meter; Nullable: True|
|OPMERKING                           |String(3000,0,0)     |PNH; Extra opmerking; Nullable: True; Default: None|
|NAAM                                |String(255,0,0)      |PNH; Naam Oevervak; Nullable: True; Default: None|
|FOTO                                |String(255,0,0)      |PNH; Locatie van de foto op de S schijf bij PNH. Deze hoeft niet gevuld te worden door de aannemer. Nullable: True; Default: None|
|FOTO2                               |String(255,0,0)      |PNH; Locatie van de foto op de S schijf bij PNH bij een tweede foto. Deze hoeft niet gevuld te worden door de aannemer. Nullable: True; Default: None|
|HYPERLINK                           |String(255,0,0)      |PNH; Hyperlink naar de locatie op de s-schijf waar het rapport zich bevindt; Nullable: True; Default: None|
|CONDITIESCORE                       |Integer(0,10,0)      |PNH; Conditiescore conform NEN 2767-4; Nullable: True; Default: None|
|CONDITIESCORE_DATUM                 |Date(8,0,0)          |PNH; Datum opname Conditiescore; Nullable: True|
|CONDITIESCORE_OPM                   |String(3000,0,0)     |PNH; Opmerking bij conditiescore conform NEN 2767-4; Nullable: True; Default: None|
|RISICO_WATERKERING                  |String(255,0,0)      |PNH; Indicatie van de maaiveldhoogte landzijde (achter het eventuele aanwezige dijklichaam) van de kerende constructie.[RISICO_WATERKERING]; Nullable: True; Default: None|
|RISICO_AFSTAND_WEG                  |String(255,0,0)      |PNH; Indicatie van de afstand tussen een weg op landzijde en de kerende constructie.[RISICO_AFSTAND_WEG]; Nullable: True; Default: None|
|RISICO_STEILTE_TALUD                |String(255,0,0)      |PNH; Indicatie van het talud aan landzijde direct aansluitend aan de kerende constructie.[RISICO_STEILTE_TALUD]; Nullable: True; Default: None|
|RISICO_TOTAAL                       |String(255,0,0)      |PNH; BEREKEND VELD, samenvattende waarde voor afzonderlijke risico waardes: Risico waterkering, afstand weg en steilte talud; Nullable: True; Default: None|
|DATALEVERANCIER                     |String(255,0,0)      |PNH; Leverancier van de data; Nullable: True; Default: None|
|CREATED_USER                        |String(255,0,0)      |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)          |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)       |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)          |PNH; Datum van de laatste mutatie; Nullable: True|
|SHAPE                               |Geometry             |PNH; Vlak|
|SHAPE_Length                        |Double(0,0,0)        |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None|
|SHAPE_Area                          |Double(0,0,0)        |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None|
|VAARWEGDEELTRAJECT                  |String(255,0,0)      |PNH; FK naar vaarwegdeeltraject_v; Nullable: True; Default: None|


***
