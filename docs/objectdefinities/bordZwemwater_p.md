## AREAALDATA.bordZwemwater_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.3
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH/IMGEO
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Een paneel waarop informatie wordt afgebeeld ten behoeve van zwemwater locaties.
* __Mapping_BGT:__ bord_p
* __Mapping_Gisib:__ Zwemwaterbord
* __Mapping_NTA8035:__ bs:PhysicalObject

***

|__KOLOM__                             |__TYPE (length, precision, scale)__          	          |__DEFINITIE__(oorsprong; beschrijving; keuzelijst; nullable; default; zichtbaar in Areaalviewer)|
|------                              |----                   |-----    |
|OBJECTID                            |OID(38,0,0)            |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; ; Nullable: False; Default: None; Visible: Yes|
|GLOBALID                            |GlobalID(38,0,0)       |PNH; Elk object heeft een unieke GlobalID (Global Unique Identifier). Dit is een systeemveld van de ArcGIS software welke noodzakelijk is om een aantal functionaliteiten binnen deze software te kunnen gebruiken; ; Nullable: False; Default: None; Visible: Yes|
|AD_ID                               |TEXT(255,0,0)          |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; ; Nullable: False; Default: None; Visible: Yes|
|GISIB_ID                            |LONG(0,10,0)           |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; ; Nullable: True; Default: None; Visible: No|
|VERWERKINGSSTATUS                   |TEXT(255,0,0)          |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/VERWERKINGSSTATUS.html); Nullable: False; Default: Nieuw; Visible: Yes|
|OBJECTBEGINTIJD                     |DATE(8,0,0)            |PNH; Datum waarop het object bij de bronhouder is ontstaan; ; Nullable: True; Default: None; Visible: Yes|
|OBJECTEINDTIJD                      |DATE(8,0,0)            |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; ; Nullable: True; Default: None; Visible: Yes|
|RELATIEVEHOOGTELIGGING              |SHORT(0,5,0)           |BGT; Aanduiding voor de relatieve hoogte van het object; ; Nullable: False; Default: 0; Visible: Yes|
|BEHEERDER                           |TEXT(255,0,0)          |PNH; Beheerder van het object; keuzelijst [BEHEERDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BEHEERDER.html); Nullable: True; Default: None; Visible: Yes|
|ONDERHOUDER                         |TEXT(255,0,0)          |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/ONDERHOUDER.html); Nullable: True; Default: None; Visible: Yes|
|EIGENAAR                            |TEXT(255,0,0)          |PNH; Eigenaar van het object; keuzelijst [INSTANTIE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/INSTANTIE.html); Nullable: True; Default: None; Visible: Yes|
|TYPESPEC                            |TEXT(255,0,0)          |PNH; Nadere typering van het object; keuzelijst [typeSpecBRDZwemwater](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeSpecBRDZwemwater.html); Nullable: True; Default: None; Visible: Yes|
|BGTPLUSTYPE                         |TEXT(50,0,0)           |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeBRD](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/typeBRD.html); Nullable: False; Default: None; Visible: No|
|AFMETINGEN                          |TEXT(255,0,0)          |PNH; Afgeleid van standaard RVV(mm x mm); ; Nullable: True; Default: None; Visible: No|
|BORDFABRIKANT                       |TEXT(255,0,0)          |PNH; Bord Fabrikant; keuzelijst [BORD_FABRIKANT](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/BORD_FABRIKANT.html); Nullable: True; Default: None; Visible: No|
|BORDNUMMER                          |TEXT(255,0,0)          |PNH; Bordnummer; ; Nullable: True; Default: None; Visible: Yes|
|PARTNER                             |TEXT(255,0,0)          |PNH; Partnerorganisatie; ; Nullable: True; Default: None; Visible: No|
|POSTADRES                           |TEXT(255,0,0)          |PNH; (Post)adres en bijbehorend nummer van de partnerorganisatie; ; Nullable: True; Default: None; Visible: No|
|POSTCODE_PLAATS                     |TEXT(255,0,0)          |PNH; Postcode en plaatsnaam van de partnerorganisatie; ; Nullable: True; Default: None; Visible: Yes|
|EMAIL_ADRES                         |TEXT(255,0,0)          |PNH; E-mail adres contactpersoon; ; Nullable: True; Default: None; Visible: No|
|BEH_OVEREENK_GEACCEPTEERD           |TEXT(255,0,0)          |PNH; Beheerovereenkomst geaccepteerd: toelichting; ; Nullable: True; Default: None; Visible: No|
|TELEFOONLIJST                       |TEXT(255,0,0)          |PNH; Telefoonnummers van contactpersonen; ; Nullable: True; Default: None; Visible: No|
|DATUMPLAATSING                      |DATE(8,0,0)            |PNH; Datum plaatsing; ; Nullable: True; Default: None; Visible: Yes|
|FOTO                                |TEXT(255,0,0)          |PNH; Locatie van de foto op de S schijf bij PNH. Deze hoeft niet gevuld te worden door de aannemer; ; Nullable: True; Default: None; Visible: No|
|LOCATIE                             |TEXT(255,0,0)          |PNH; De locatie van het zwemwater bord. Bijvoorbeeld 'Nieuwe Meer, Overlanden' of 'Strandslag Paal 12,0 Jan Eyeslag, Texel); ; Nullable: True; Default: None; Visible: Yes|
|GEMEENTE                            |TEXT(255,0,0)          |PNH; Gemeente naam; keuzelijst [GEMEENTE](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/GEMEENTE.html); Nullable: True; Default: None; Visible: No|
|OPMERKING                           |TEXT(255,0,0)          |PNH; Toevoeging van subjectieve informatie met betrekking tot opmerkelijke waarnemingen; ; Nullable: True; Default: None; Visible: Yes|
|PLAATS                              |TEXT(255,0,0)          |PNH; Plaatsnaam van de locatie van het zwemwater bord; ; Nullable: True; Default: None; Visible: Yes|
|DATALEVERANCIER                     |TEXT(255,0,0)          |PNH; Leverancier van de data; ; Nullable: True; Default: None; Visible: No|
|CREATED_USER                        |TEXT(255,0,0)          |PNH; Naam van gebruiker die de rij heeft aangemaakt, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|CREATED_DATE                        |DATE(8,0,0)            |PNH; Datum waarop de rij aan de database is toegevoegd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_USER                    |TEXT(50,0,0)           |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|LAST_EDITED_DATE                    |DATE(8,0,0)            |PNH; Datum van de laatste mutatie, gegenereerd door ArcGIS; ; Nullable: True; Default: None; Visible: No|
|SHAPE                               |Geometry               |PNH; Punt; ; Nullable: False; Default: None; Visible: Yes|
|GEBIEDSCONTRACTREGIO                |TEXT(255,0,0)          |PNH; Verwijzende sleutel naar gebiedscontractregio_v (simpel); keuzelijst [GCR_NAAM](http://provincienh.github.io/Leveren_Geoinformatie/keuzelijsten/GCR_NAAM.html); Nullable: True; Default: None; Visible: No|

***
