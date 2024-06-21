## measured_value_traffic_flow

* __Veld:__ onbekend

***

| __KOLOM__                      | __TYPE (length, precision, scale)__          	 | __DEFINITIE__(beschrijving; nullable; default)                                        |
|--------------------------------|------------------------------------------------|---------------------------------------------------------------------------------------|
| measured_value_traffic_flow_id | LONG(?,10,0)                                   | Identifier. Wordt zelf gegenereerd.; Nullable: False; Default: ???                    |
| ref_site_measurement_id        | LONG(?,10,0)                                   | Referentie aan id van site_measurement; Nullable: False; Default: ???                 |
| Index                          | LONG(?,10,0)                                   | Volgorde van de meetwaarde in de lijst van meetwaarden; Nullable: False; Default: ??? |
| VehicleFlowRate                | LONG(?,10,0)                                   | Ratio van de doorvoer van voertuigen; Nullable: True; Default: ???                    |

***
