## measurement_site_record

* __Veld:__ onbekend

***

| __KOLOM__                               | __TYPE (length, precision, scale)__          	 | __DEFINITIE__(beschrijving; nullable; default)                                       |
|-----------------------------------------|------------------------------------------------|--------------------------------------------------------------------------------------|
| measurement_site_record_id              | OBJECTID(?,10,0)                               | Identifier. Wordt zelf gegenereerd.; Nullable: False; Default: ???                   |
| ref_measurement_site_table_id           | LONG(?,10,0)                                   | Referentie aan id van measurement_site_table; Nullable: False; Default: ???          |
| id                                      | TEXT(254,0,0)                                  | Code van het meetpunt; Nullable: False; Default: ???                                 |
| version                                 | LONG(?,10,0)                                   | Versienummer van _; Nullable: False; Default: ???                                    |
| measurement_site_record_version_time    | DATE(?,0,0)                                    | ???; Nullable: False; Default: ???                                                   |
| computation_method                      | LONG(?,0,0)                                    | Berekenwijze; Nullable: False; Default: ???                                          |
| measurement_equipment_reference         | TEXT(1073741822,0,0)                           | Meetapparatuur _; Nullable: True; Default: ???                                       |
| measurement_equipment_type_used         | TEXT(1073741822,0,0)                           | Soort meetapparatuur die gebruikt is; Nullable: True; Default: ???                   |
| measurement_site_name                   | TEXT(1073741822,0,0)                           | ???; Nullable: True; Default: ???                                                    |
| measurement_site_number_of_lanes        | LONG(?,10,0)                                   | Aantal rijstroken op de meetpunt; Nullable: False; Default: ???                      |
| measurement_side                        | SHORT(?,5,0)                                   | Zijde waar het meetpunt is opgesteld; Nullable: True; Default: ???                   |
| ref_measurement_site_location_id        | LONG(?,10,0)                                   | Referentie aan id van measurement_site_location; Nullable: True; Default: ???        |
| ref_measurement_site_record_extended_id | LONG(?,10,0)                                   | Referentie aan id van measurement_site_record_extended; Nullable: True; Default: ??? |

***
