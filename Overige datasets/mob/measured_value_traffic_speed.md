## measured_value_traffic_speed

* __Veld:__ onbekend

***

| __KOLOM__                                   | __TYPE (length, precision, scale)__          	 | __DEFINITIE__(beschrijving; nullable; default)                                          |
|---------------------------------------------|------------------------------------------------|-----------------------------------------------------------------------------------------|
| measured_value_traffic_speed_id             | LONG(?,10,0)                                   | Identifier. Wordt zelf gegenereerd.; Nullable: False; Default: ???                      |
| ref_site_measurement_id                     | LONG(?,10,0)                                   | Referentie aan id van site_measurement; Nullable: False; Default: ???                   |
| Index                                       | LONG(?,10,0)                                   | Volgorde van de meetwaarde in de lijst van meetwaarden; Nullable: False; Default: ???   |
| AverageVehicleSpeed_NumberofInputValuesUsed | LONG(?,10,0)                                   | Het aantal voertuigen waarover dit gemiddelde is berekend; Nullable: True; Default: ??? |
| AverageVehicleSpeed_StandardDeviation       | FLOAT(?,0,0)                                   | De standaarddeviatie van dit gemiddelde; Nullable: True; Default: ???                   |
| AverageVehicleSpeed_Speed                   | LONG(?,10,0)                                   | De gemiddelde snelheid; Nullable: True; Default: ???                                    |

***
