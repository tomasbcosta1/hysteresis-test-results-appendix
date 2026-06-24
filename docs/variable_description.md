# Variable description

The CSV files use normalized variable names to support reuse and analysis.

| Variable | Description | Unit / format |
|---|---|---|
| `table_number` | Number of the source table in the appendix | integer |
| `source_caption` | Original table caption from the appendix | text |
| `loading_N` | Applied loading used in the hysteresis test | N |
| `manufacturing_process` | Manufacturing process identified in the original table | VB or CM |
| `stacking_sequence` | Laminate stacking sequence identified in the original table | text |
| `infill_condition` | Indicates whether the test was conducted with or without infill | text |
| `specimen_id` | Specimen/configuration identifier | text |
| `n_disc` | Number of discs in the assembly | integer |
| `arrangement` | Disc arrangement notation | text |
| `infill_thickness_mm` | Infill thickness; blank for tests without infill | mm |
| `stiffness_kN_per_mm` | Stiffness obtained from hysteresis response | kN/mm |
| `E_load_J` | Loading energy | J |
| `E_unload_J` | Unloading energy | J |
| `E_dissipated_J` | Dissipated energy | J |
| `E_dissipated_percent` | Percentage of dissipated energy | % |
| `displacement_max_mm` | Maximum displacement | mm |

The numerical values were transcribed directly from the uploaded appendix file and were not modified.
