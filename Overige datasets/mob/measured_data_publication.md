## measured_data_publication

* __Veld:__ onbekend

***

| __KOLOM__                               | __TYPE (length, precision, scale)__          	 | __DEFINITIE__(beschrijving; nullable; default)                                          |
|-----------------------------------------|------------------------------------------------|-----------------------------------------------------------------------------------------|
| measured_data_publication_id            | LONG(?,10,0)                                   | Identifier. Wordt zelf gegenereerd.; Nullable: False; Default: None                     |
| ref_exchange_id                         | LONG(?,10,0)                                   | Referentie aan id van exchange.; Nullable: False; Default: None                         |
| ref_measurement_site_table_reference_id | LONG(?,10,0)                                   | Referentie aan id van measurement_site_table_reference.; Nullable: False; Default: None |
| Language                                | TEXT(60000,00,0)                               | Taal van de publicatie; Nullable: True; Default: nl                                     |
| PublicationTime                         | DATE(?,0,0)                                    | Datum en tijd van de publicatie; Nullable: True; Default: None                          |
| PublicationCreator_Country              | TEXT(60000,0,0)                                | Code van het land van de publicist; Nullable: True; Default: None                       |
| PublicationCreator_NationalIdentifier   | TEXT(60000,0,0)                                | Code van de publicist; Nullable: True; Default: None                                    |
| HeaderInformation_Confidentiality       | TEXT(60000,0,0)                                | Vertrouwelijkheid van de publicatie; Nullable: True; Default: None                      |
| HeaderInformation_InformationStatus     | TEXT(60000,0,0)                                | Soort gegevens in de publicatie; Nullable: True; Default: None                          |

***
