## AREAALDATA.bordZwemwater_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH/IMGEO
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Een paneel waarop informatie wordt afgebeeld ten behoeve van zwemwater locaties.

***

|KOLOM                               |TYPE                   |DEFINITIE|
|------                              |----                   |-----    |
|OBJECTID                            |OID(38,0,0)            |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:Yes|
|GLOBALID                            |GlobalID(38,0,0)       |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None; Visible:Yes|
|AD_ID                               |String(255,0,0)        |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None; Visible:Yes|
|GISIB_ID                            |Integer(0,10,0)        |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|IDENTIFICATIE                       |String(255,0,0)        |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None; Visible:No|
|VERWERKINGSSTATUS                   |String(255,0,0)        |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw; Visible:Yes|
|STATUS                              |String(10,0,0)         |BGT; BGT status van het object; keuzelijst [status]; Nullable: False; Default: bestaand; Visible:No|
|OBJECTBEGINTIJD                     |Date(8,0,0)            |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True; Visible:Yes|
|OBJECTEINDTIJD                      |Date(8,0,0)            |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True; Visible:Yes|
|RELATIEVEHOOGTELIGGING              |SmallInteger(0,10,0)   |BGT; Aanduiding voor de relatieve hoogte van het object; Nullable: False; Default: 0; Visible:Yes|
|BEHEERDER                           |String(255,0,0)        |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None; Visible:Yes|
|ONDERHOUDER                         |String(255,0,0)        |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None; Visible:No|
|EIGENAAR                            |String(255,0,0)        |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None; Visible:No|
|BRONHOUDER                          |String(5,0,0)          |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None; Visible:No|
|TYPESPEC                            |String(255,0,0)        |PNH; Nadere typering van het object; keuzelijst [typeSpecBRDZwemwater]; Nullable: True; Default: None; Visible:Yes|
|BGTPLUSTYPE                         |String(50,0,0)         |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeBRD]; Nullable: False; Default: None; Visible:No|
|AFMETINGEN                          |String(255,0,0)        |PNH; Afgeleid van standaard RVV(mm x mm); Nullable: True; Default: None; Visible:No|
|BORDFABRIKANT                       |String(255,0,0)        |PNH; Bord Fabrikant; keuzelijst [BORD_FABRIKANT]; Nullable: True; Default: None; Visible:No|
|BORDNUMMER                          |String(255,0,0)        |PNH; Bordnummer ; Nullable: True; Default: None; Visible:Yes|
|PARTNER                             |String(255,0,0)        |PNH; Partnerorganisatie; Nullable: True; Default: None; Visible:No|
|POSTADRES                           |String(255,0,0)        |PNH; (Post)adres en bijbehorend nummer van de partnerorganisatie; Nullable: True; Default: None; Visible:No|
|POSTCODE_PLAATS                     |String(255,0,0)        |PNH; Postcode en plaatsnaam van de partnerorganisatie. Nullable: True; Default: None; Visible:Yes|
|EMAIL_ADRES                         |String(255,0,0)        |PNH; E-mail adres contactpersoon ; Nullable: True; Default: None; Visible:No|
|BEH_OVEREENK_GEACCEPTEERD           |String(255,0,0)        |PNH; Beheerovereenkomst geaccepteerd: toelichting ; Nullable: True; Default: None; Visible:No|
|TELEFOONLIJST                       |String(255,0,0)        |PNH; Telefoonnummers van contactpersonen ; Nullable: True; Default: None; Visible:No|
|DATUMPLAATSING                      |Date(8,0,0)            |PNH; Datum plaatsing ; Nullable: True; Visible:Yes|
|FOTO                                |String(255,0,0)        |PNH; Locatie van de foto op de S schijf bij PNH. Deze hoeft niet gevuld te worden door de aannemer. Nullable: True; Default: None; Visible:No|
|LOCATIE                             |String(255,0,0)        |PNH; De locatie van het zwemwater bord. Bijvoorbeeld 'Nieuwe Meer, Overlanden' of 'Strandslag Paal 12,0 Jan Eyeslag, Texel); Nullable: True; Default: None; Visible:Yes|
|GEMEENTE                            |String(255,0,0)        |PNH; Gemeente naam; keuzelijst [GEMEENTE]; Nullable: True; Default: None; Visible:No|
|OPMERKING                           |String(255,0,0)        |PNH; Toevoeging van subjectieve informatie met betrekking tot opmerkelijke waarnemingen; Nullable: True; Default: None; Visible:Yes|
|PLAATS                              |String(255,0,0)        |PNH; Plaatsnaam van de locatie van het zwemwater bord; Nullable: True; Default: None; Visible:Yes|
|DATALEVERANCIER                     |String(255,0,0)        |PNH; Leverancier van de data; Nullable: True; Default: None; Visible:No|
|INONDERZOEK                         |String(1,0,0)          |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible:No|
|TIJDSTIPREGISTRATIE                 |Date(8,0,0)            |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|EINDREGISTRATIE                     |Date(8,0,0)            |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|LV_PUBLICATIEDATUM                  |Date(8,0,0)            |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|BERICHT_ID                          |String(128,0,0)        |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|CREATED_USER                        |String(255,0,0)        |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None; Visible:No|
|CREATED_DATE                        |Date(8,0,0)            |PNH; Aanmaakdatum; Nullable: True; Visible:No|
|LAST_EDITED_USER                    |String(50,0,0)         |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None; Visible:No|
|LAST_EDITED_DATE                    |Date(8,0,0)            |PNH; Datum van de laatste mutatie; Nullable: True; Visible:No|
|SHAPE                               |Geometry               |PNH; Punt; Visible:Yes|
|GEBIEDSCONTRACTREGIO                |String(255,0,0)        |PNH; FK naar gebiedscontractregio_v; Nullable: True; Default: None|

***
