## AREAALDATA.oevervak_v

$ Feature dataset: Functioneel


* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ nvt
* __SHAPE:__ Vlak
* __Definitie:__ Een Oevervak is de rand van een kanaal, vaarweg of rivier. Het begint bij bodem van het nautisch profiel en gaat door tot 10m achter de oeverconstructie. __NB:__ Dit is het equivalent van Beheerobject bij Vaarwegen conform de NEN 2767-4 Decompositie. Een oevervak is ongeveer 100 meter lang en bestaat uit een uniforme oeverconstructie.

De Oeverconstructie zelf is vastgelegd in [AREAALDATA.scheidingOevervak_l] en [AREAALDATA.bouwdeelOevervak_tbl]


***

|KOLOM                               |TYPE              |DEFINITIE|
|------                              |----              |-----    |
|ZIJDE                               |String(255,0,0)     |Zijde, keuzelijst [ZIJDE] - Nullable: True Default: None|
|OMSCHRIJVING                        |String(255,0,0)     |Extra toelichting - Nullable: True Default: None|
|GEBRUIK                             |String(255,0,0)     |Daadwerkelijk gebruik vd oever - Nullable: True Default: None|
|HMBEGIN                             |Float(0,25,10)      |Begin Hectometrering van Oevervak - Nullable: True|
|HMEIND                              |Float(0,25,10)      |Eind Hectometrering van Oevervak - Nullable: True|
|LENGTE                              |SmallInteger(0,10,0)|Lengte van Oevervak - Nullable: True|
|OPMERKING                           |String(3000,0,0)    |Extra opmerking - Nullable: True Default: None|
|OEVERFUNCTIE                        |String(255,0,0)     |Oeverfunctie, keuzelijst [OEVER_FUNCTIE] - Nullable: True Default: None|
|NAAM                                |String(255,0,0)     |Naam Oevervak - Nullable: True Default: None|
|FOTO                                |String(255,0,0)     |Foto - Nullable: True Default: None|
|FOTO2                               |String(255,0,0)     |Foto - Nullable: True Default: None|
|HYPERLINK                           |String(255,0,0)     |Hyperlink - Nullable: True Default: None|
|CONDITIESCORE                       |String(255,0,0)     |Conditiescore conform NEN 2767-4 - Nullable: True Default: None|
|CONDITIESCORE_DATUM                 |Date(8,0,0)         |Datum opname Conditiescore - Nullable: True|
|CONDITIESCORE_OPM                   |String(3000,0,0)    |Opmerking bij conditiescore conform NEN 2767-4 - Nullable: True Default: None|
|RAPPORT                             |String(255,0,0)     |Pad naar rapport - Nullable: True Default: None|
|SHAPE                               |Geometry            |Vlak|
|SHAPE_Length                        |Double(0,0,0)       |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|SHAPE_Area                          |Double(0,0,0)       |Beschrijving: - keuzelijst [] Nullable: True Default: None|
|VAARWEGDEELTRAJECT                  |String(255,0,0)     |FK naar vaarwegdeeltraject_v - Nullable: True Default: None|
|RISICO_WATERKERING                  |String(255,0,0)     |Indicatie van de maaiveldhoogte landzijde (achter het eventuele aanwezige dijklichaam) van de kerende constructie.[RISICO_WATERKERING] - Nullable: True Default: None|
|RISICO_AFSTAND_WEG                  |String(255,0,0)     |Indicatie van de afstand tussen een weg op landzijde en de kerende constructie.[RISICO_AFSTAND_WEG] - Nullable: True Default: None|
|RISICO_STEILTE_TALUD                |String(255,0,0)     |Indicatie van het talud aan landzijde direct aansluitend aan de kerende constructie.[RISICO_STEILTE_TALUD] - Nullable: True Default: None|
|RISICO_TOTAAL                       |String(255,0,0)     |BEREKEND VELD, samenvattende waarde voor afzonderlijke risico waardes: Risico waterkering, afstand weg en steilte talud TODO - Nullable: True Default: None|
|IDENTIFICATIE                       |String(255,0,0)      |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID - Nullable: True Default: None|
|TYPESPEC                            |String(255,0,0)    |Nadere typering van het object, keuzelijst [typeSpecOEV] - Nullable: True Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)    |Status van de gegevens, keuzelijst [VERWERKINGSSTATUS] - Nullable: False Default: Nieuw|
|OBJECTID                            |OID(38,0,0)        |Interne ID ArcGIS - Nullable: False|
|GLOBALID                            |GlobalID(38,0,0)   |Global Unique Identifier - Nullable: False|
|GISIB_ID                            |Integer(0,10,0)    |ID beheer openbare ruimte (GISIB) - Nullable: True|
|AD_ID                               |String(255,0,0)    |Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]' - Nullable: False Default: None|
|OBJECTBEGINTIJD                     |Date(8,0,0)        |Datum waarop het object bij de bronhouder is ontstaan - Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)        |Datum waarop het object bij de bronhouder niet meer geldig is - Nullable: True|
|CREATED_USER                        |String(255,0,0)    |Naam van gebruiker die de rij heeft aangemaakt - Nullable: True Default: None|
|CREATED_DATE                        |Date(8,0,0)        |Aanmaakdatum - Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)     |Naam van gebruiker die de laatste mutatie heeft doorgevoerd - Nullable: True Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)        |Datum van de laatste mutatie - Nullable: True|
|BEHEERDER                           |String(255,0,0)    |Beheerder van het object, keuzelijst [BEHEERDER] - Nullable: True Default: None|
|ONDERHOUDER                         |String(255,0,0)    |Onderhouder van het object, keuzelijst [ONDERHOUDER] - Nullable: True Default: None|
|EIGENAAR                            |String(255,0,0)    |Eigenaar van het object, keuzelijst [INSTANTIE] - Nullable: True Default: None| 
|DATALEVERANCIER                     |String(255,0,0)    |Leverancier van de data - Nullable: True Default: None|


***
