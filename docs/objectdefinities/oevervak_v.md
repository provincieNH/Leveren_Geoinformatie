## AREAALDATA.oevervak_v

*Feature dataset: Functioneel*



* __Areaaldata model versie:__ 4.2
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ n.v.t.
* __Geometrie:__ Vlak
* __Definitie:__ Een Oevervak is de rand van een kanaal, vaarweg of rivier. Het begint bij bodem van het nautisch profiel en gaat door tot 1m achter de oeverconstructie. __NB:__ Dit is het equivalent van Beheerobject bij Vaarwegen conform de NEN 2767-4 Decompositie. Een oevervak is ongeveer 100 meter lang en bestaat uit een uniforme oeverconstructie. De Oeverconstructie zelf is vastgelegd in [AREAALDATA.scheidingWater_l] en [AREAALDATA.bouwdeelOevervak_tbl]
* __Mapping_BGT:__ x
* __Mapping_Gisib:__ Oevervak

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__| (oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                 |-----    |
|OBJECTID                            |OID(38,0,0)          |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)     |PNH; Global Unique Identifier, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |String(255,0,0)      |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |Integer(0,10,0)      |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |String(255,0,0)      |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.html); Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |Date(8,0,0)          |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)          |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|BEHEERDER                           |String(255,0,0)      |PNH; Beheerder van het object; keuzelijst [BEHEERDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEERDER.html); Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |String(255,0,0)      |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ONDERHOUDER.html); Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |String(255,0,0)      |PNH; Eigenaar van het object; keuzelijst [INSTANTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/INSTANTIE.html); Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |String(255,0,0)      |PNH; Nadere typering van het object; keuzelijst [typeSpecOEV](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecOEV.html); Nullable: True; Default: None; Visible: Yes|
|ZIJDE                               |String(255,0,0)      |PNH; Zijde; keuzelijst [ZIJDE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ZIJDE.html); Nullable: True; Default: None; Visible: No|
|OPMERKING                           |String(255,0,0)      |PNH; Algemene opmerking voor het object, zoals een omschrijving of toelichting; ; Nullable: True; Default: None; Visible: Yes|
|GEBRUIK                             |String(255,0,0)      |PNH; Daadwerkelijk gebruik vd oever; ; Nullable: True; Default: None; Visible: No|
|HMBEGIN                             |Float(0,25,10)       |PNH; Begin Hectometrering van Oevervak; ; Nullable: True; Default: None; Visible: No|
|HMEIND                              |Float(0,25,10)       |PNH; Eind Hectometrering van Oevervak; ; Nullable: True; Default: None; Visible: No|
|LENGTE                              |Float(0,10,0)        |PNH; Lengte van het oevervak in meter; ; Nullable: True; Default: None; Visible: Yes|
|NAAM                                |String(255,0,0)      |PNH; Naam Oevervak; ; Nullable: True; Default: None; Visible: Yes|
|FOTO                                |String(255,0,0)      |PNH; Locatie van de foto op de S schijf bij PNH. Deze hoeft niet gevuld te worden door de aannemer; ; Nullable: True; Default: None; Visible: No|
|FOTO2                               |String(255,0,0)      |PNH; Locatie van de foto op de S schijf bij PNH bij een tweede foto. Deze hoeft niet gevuld te worden door de aannemer; ; Nullable: True; Default: None; Visible: No|
|HYPERLINK                           |String(255,0,0)      |PNH; Hyperlink naar de locatie op de s-schijf waar het rapport zich bevindt; ; Nullable: True; Default: None; Visible: No|
|CONDITIESCORE                       |Integer(0,10,0)      |PNH; Conditiescore conform NEN 2767-4; ; Nullable: True; Default: None; Visible: No|
|CONDITIESCORE_DATUM                 |Date(8,0,0)          |PNH; Datum opname Conditiescore; ; Nullable: True; Default: None; Visible: No|
|CONDITIESCORE_OPM                   |String(3000,0,0)     |PNH; Opmerking bij conditiescore conform NEN 2767-4; ; Nullable: True; Default: None; Visible: Yes|
|RISICO_WATERKERING                  |String(255,0,0)      |PNH; Indicatie van de maaiveldhoogte landzijde (achter het eventuele aanwezige dijklichaam) van de kerende constructie; keuzelijst [RISICO_WATERKERING](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/RISICO_WATERKERING.html); Nullable: True; Default: None; Visible: No|
|RISICO_AFSTAND_WEG                  |String(255,0,0)      |PNH; Indicatie van de afstand tussen een weg op landzijde en de kerende constructie; keuzelijst [RISICO_AFSTAND_WEG](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/RISICO_AFSTAND_WEG.html); Nullable: True; Default: None; Visible: No|
|RISICO_STEILTE_TALUD                |String(255,0,0)      |PNH; Indicatie van het talud aan landzijde direct aansluitend aan de kerende constructie; keuzelijst [RISICO_STEILTE_TALUD](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/RISICO_STEILTE_TALUD.html); Nullable: True; Default: None; Visible: No|
|RISICO_TOTAAL                       |String(255,0,0)      |PNH; BEREKEND VELD, samenvattende waarde voor afzonderlijke risico waardes: Risico waterkering, afstand weg en steilte talud; ; Nullable: True; Default: None; Visible: No|
|DATALEVERANCIER                     |String(255,0,0)      |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |String(255,0,0)      |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |Date(8,0,0)          |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |String(50,0,0)       |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |Date(8,0,0)          |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry             |PNH; Vlak; ; Nullable: True; Default: None; Visible: Yes|
|SHAPE_Length                      |Double(0,0,0)           |PNH; Omtrek in meters, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|SHAPE_Area                        |Double(0,0,0)           |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt berekend in bepaalde applicaties; ; Nullable: False; Default: None; Visible: No|
|OMTREK                            |Double(0,0,0)           |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Length; ; Nullable: False; Default: None; Visible: Yes|
|OPPERVLAKTE                       |Double(0,0,0)           |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld uit SHAPE_Area; ; Nullable: False; Default: None; Visible: Yes|
|VAARWEGDEELTRAJECT                  |String(255,0,0)      |PNH; Verwijzende sleutel naar vaarwegdeeltraject_v (simpel); ; Nullable: True; Default: None; Visible: Yes|


***
