## measured_value_travel_time_data

* __Veld:__ onbekend

***

| __KOLOM__                                                    | __TYPE (length, precision, scale)__          	 | __DEFINITIE__(beschrijving; nullable; default)                                        |
|--------------------------------------------------------------|------------------------------------------------|---------------------------------------------------------------------------------------|
| measured_value_travel_time_id                                | LONG(?,10,0)                                   | Identifier. Wordt zelf gegenereerd.; Nullable: False; Default: ???                    |
| ref_site_measurement_id                                      | LONG(?,10,0)                                   | Referentie aan id van site_measurement; Nullable: False; Default: ???                 |
| ref_measured_data_publication_id                             | LONG(?,10,0)                                   | Referentie aan id van measured_data_publication; Nullable: False; Default: ???        |
| Index                                                        | LONG(?,10,0)                                   | Volgorde van de meetwaarde in de lijst van meetwaarden; Nullable: False; Default: ??? |
| TravelTimeType                                               | TEXT(60000,0,0)                                | Type reistijd (geschat, beste, opgebouwd); Nullable: True; Default: ???               |
| TravelTime_Accuracy                                          | FLOAT(?,0,0)                                   | Nauwkeurigheid van de reistijd; Nullable: True; Default: ???                          |
| TravelTime_NumberOfIncompleteInputs                          | LONG(?,10,0)                                   | Aantal incomplete inputs; Nullable: True; Default: 0                                  |
| TravelTime_NumberOfInputValuesUsed                           | LONG(?,10,0)                                   | Het aantal gebruikte inputs; Nullable: True; Default: ???                             |
| TravelTime_SupplierCalculatedDataQuality                     | FLOAT(?,0,0)                                   | De berekende datakwaliteit van de leverancier; Nullable: True; Default: ???           |
| TravelTime_StandardDeviation                                 | FLOAT(?,0,0)                                   | De standaarddeviatie van de reistijd; Nullable: True; Default: ???                    |
| TravelTime_DataError                                         | SHORT(?,5,0)                                   | Er zit een fout in de meetwaarde; Nullable: True; Default: ???                        |
| TravelTime_Duration                                          | FLOAT(?,0,0)                                   | De duur van de reis; Nullable: True; Default: ???                                     |
| BasicReferenceValue_ReferenceValueType                       | TEXT(60000,0,0)                                | ???; Nullable: True; Default: ???                                                     |
| BasicReferenceValue_TravelTimeType                           | TEXT(60000,0,0)                                | ???; Nullable: True; Default: ???                                                     |
| BasicReferenceValue_TravelTime_Accuracy                      | FLOAT(?,0,0)                                   | ???; Nullable: True; Default: ???                                                     |
| BasicReferenceValue_TravelTime_NumberOfIncompleteInputs      | LONG(?,10,0)                                   | ???; Nullable: True; Default: ???                                                     |
| BasicReferenceValue_TravelTime_NumberOfInputValuesUsed       | LONG(?,10,0)                                   | ???; Nullable: True; Default: ???                                                     |
| BasicReferenceValue_TravelTime_SupplierCalculatedDataQuality | FLOAT(?,0,0)                                   | ???; Nullable: True; Default: ???                                                     |
| BasicReferenceValue_TravelTime_StandardDeviation             | FLOAT(?,0,0)                                   | ???; Nullable: True; Default: ???                                                     |
| BasicReferenceValue_TravelTime_DataError                     | SHORT(?,5,0)                                   | ???; Nullable: True; Default: ???                                                     |
| BasicReferenceValue_TravelTime_Duration                      | FLOAT(?,0,0)                                   | ???; Nullable: True; Default: ???                                                     |

***
