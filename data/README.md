# Data information

## AllEffects_long.csv
Period-wise effects defined as post - pre, i.e., M1 - M0 and M3 - M2, with one observation per row.<br><br>
Columns:
- 0 [NA]: Index
- 1 [ID]: Identifier for each participant
- 2 [sequence]: Two levels encoding vibraion first then control (VC) and control first then vibration (CV)
- 3 [tries]: Three levels V1, V2, and V3 for three tries at each assessment day, except 2 min walk test, and health-related visual analog scale
- 4 [value]: The period specific post - pre effect in origial units
- 5 [intervention]: Two levels encoding vibration period effect (V) and control period effect (C)
- 6 [period]: Two levels encoding the timely order where 1 was earlier than 2
- 7 [test]: The short-name of the test or assessment (abbreviations listed below).
- 8 [scaler]: The scaling value as defined in supplement Equations 1 and 2 (page 9)
- 9 [scaled_value]: The result of scaling, i.e., value/scaler

## FSST_M0_M1_M2_M3_wide.csv
Four Square Step Test original data [seconds] from four assessment days, 3 tries<br><br>
Columns:
- 0 [NA]: Index
- 1 [ID]: Identifier for each participant
- 2 [sequence]: Two levels encoding vibraion first then control (VC) and control first then vibration (CV)
- 3 [tries]: Three levels V1, V2, and V3 for three tries at each assessment day
- 4 [M0]: Measurements on the assessment day before receiving the Suralis vibration feedback system
- 5 [M1]: Measurements on the assessment day after receiving the Suralis vibration feedback system
- 6 [M2]: Measurements on the assessment day before the control period
- 7 [M3]: Measurements on the assessment day after the control period

## HealthVAS_M0_M1_M2_M3_wide.csv
General health-related Visual Analog Scale original data [mm] from four assessment days<br><br>
Columns:
- 0 [NA]: Index
- 1 [ID]: Identifier for each participant
- 2 [sequence]: Two levels encoding vibraion first then control (VC) and control first then vibration (CV)
- 3 [tries]: NA, empty
- 4 [M0]: Measurements on the assessment day before receiving the Suralis vibration feedback system
- 5 [M1]: Measurements on the assessment day after receiving the Suralis vibration feedback system
- 6 [M2]: Measurements on the assessment day before the control period
- 7 [M3]: Measurements on the assessment day after the control period

## StanceT_diff_M0_M1_M2_M3_wide.csv
Stance Time Difference Affected Leg (prosthesis side) minus Unaffected Leg original data [seconds] from four assessment days from the GAITRite system, 3 tries.<br>
*Cave: data sampled at a too low frequency of 80 Hz, but >125 Hz would be required. Thus, this data correponds to white noise.*
<br><br>
Columns:
- 0 [NA]: Index
- 1 [ID]: Identifier for each participant
- 2 [sequence]: Two levels encoding vibraion first then control (VC) and control first then vibration (CV)
- 3 [tries]: Three levels V1, V2, and V3 for three tries at each assessment day
- 4 [M0]: Measurements on the assessment day before receiving the Suralis vibration feedback system
- 5 [M1]: Measurements on the assessment day after receiving the Suralis vibration feedback system
- 6 [M2]: Measurements on the assessment day before the control period
- 7 [M3]: Measurements on the assessment day after the control period

## StanceTimeAL_M0_M1_M2_M3_wide.csv
Stance Time of the Affected Leg (prosthesis side) original data [seconds] from four assessment days from the GAITRite system, 3 tries<br><br>
Columns:
- 0 [NA]: Index
- 1 [ID]: Identifier for each participant
- 2 [sequence]: Two levels encoding vibraion first then control (VC) and control first then vibration (CV)
- 3 [tries]: Three levels V1, V2, and V3 for three tries at each assessment day
- 4 [M0]: Measurements on the assessment day before receiving the Suralis vibration feedback system
- 5 [M1]: Measurements on the assessment day after receiving the Suralis vibration feedback system
- 6 [M2]: Measurements on the assessment day before the control period
- 7 [M3]: Measurements on the assessment day after the control period

## StepLengthDiff_M0_M1_M2_M3_wide.csv
Step Length Difference of the of unaffected - affected (prosthesis side) leg step length original data [cm] from four assessment days from the GAITRite system, 3 tries. (*cave: ICC 3,1 was only at 0.36 with a standard error of measurement of 5.1 cm*)<br><br>
Columns:
- 0 [NA]: Index
- 1 [ID]: Identifier for each participant
- 2 [sequence]: Two levels encoding vibraion first then control (VC) and control first then vibration (CV)
- 3 [tries]: Three levels V1, V2, and V3 for three tries at each assessment day
- 4 [M0]: Measurements on the assessment day before receiving the Suralis vibration feedback system
- 5 [M1]: Measurements on the assessment day after receiving the Suralis vibration feedback system
- 6 [M2]: Measurements on the assessment day before the control period
- 7 [M3]: Measurements on the assessment day after the control period

## StepLengthUL_M0_M1_M2_M3_wide.csv
Step Length of the Unaffected Leg original data [cm] from four assessment days from the GAITRite system, 3 tries<br><br>
Columns:
- 0 [NA]: Index
- 1 [ID]: Identifier for each participant
- 2 [sequence]: Two levels encoding vibraion first then control (VC) and control first then vibration (CV)
- 3 [tries]: Three levels V1, V2, and V3 for three tries at each assessment day
- 4 [M0]: Measurements on the assessment day before receiving the Suralis vibration feedback system
- 5 [M1]: Measurements on the assessment day after receiving the Suralis vibration feedback system
- 6 [M2]: Measurements on the assessment day before the control period
- 7 [M3]: Measurements on the assessment day after the control period

## TUG_M0_M1_M2_M3_wide.csv
Timed Up and Go test original data [seconds] from four assessment days, 3 tries<br><br>
Columns:
- 0 [NA]: Index
- 1 [ID]: Identifier for each participant
- 2 [sequence]: Two levels encoding vibraion first then control (VC) and control first then vibration (CV)
- 3 [tries]: Three levels V1, V2, and V3 for three tries at each assessment day
- 4 [M0]: Measurements on the assessment day before receiving the Suralis vibration feedback system
- 5 [M1]: Measurements on the assessment day after receiving the Suralis vibration feedback system
- 6 [M2]: Measurements on the assessment day before the control period
- 7 [M3]: Measurements on the assessment day after the control period

## Velocity_M0_M1_M2_M3_wide.csv
Gait speed original data  [cm/second] from four assessment days from the GAITRite system, 3 tries<br><br>
Columns:
- 0 [NA]: Index
- 1 [ID]: Identifier for each participant
- 2 [sequence]: Two levels encoding vibraion first then control (VC) and control first then vibration (CV)
- 3 [tries]: Three levels V1, V2, and V3 for three tries at each assessment day
- 4 [M0]: Measurements on the assessment day before receiving the Suralis vibration feedback system
- 5 [M1]: Measurements on the assessment day after receiving the Suralis vibration feedback system
- 6 [M2]: Measurements on the assessment day before the control period
- 7 [M3]: Measurements on the assessment day after the control period

## WT10m_M0_M1_M2_M3_wide.csv
*(cave: this test was not correctly performed due to insufficient instructions, i.e., the test included in total only 10 m instead of 14 m walking, and it is not clear if the noted unit of measure is meters or metres/second (sheet vs. instruction), and a participant ran. Finally, the values range between 2.7 and 12.8, which is implausible. Thus, this test should be excluded from further analysis.)*
Ten meter Walk Test original data [???] from four assessment days, 3 tries<br><br>
Columns:
- 0 [NA]: Index
- 1 [ID]: Identifier for each participant
- 2 [sequence]: Two levels encoding vibraion first then control (VC) and control first then vibration (CV)
- 3 [tries]: Three levels V1, V2, and V3 for three tries at each assessment day
- 4 [M0]: Measurements on the assessment day before receiving the Suralis vibration feedback system
- 5 [M1]: Measurements on the assessment day after receiving the Suralis vibration feedback system
- 6 [M2]: Measurements on the assessment day before the control period
- 7 [M3]: Measurements on the assessment day after the control period

## WT2min_M0_M1_M2_M3_wide.csv
Two minutes Walk Test original data [meters] from four assessment days, 3 tries<br><br>
Columns:
- 0 [NA]: Index
- 1 [ID]: Identifier for each participant
- 2 [sequence]: Two levels encoding vibraion first then control (VC) and control first then vibration (CV)
- 3 [tries]: NA, empty
- 4 [M0]: Measurements on the assessment day before receiving the Suralis vibration feedback system
- 5 [M1]: Measurements on the assessment day after receiving the Suralis vibration feedback system
- 6 [M2]: Measurements on the assessment day before the control period
- 7 [M3]: Measurements on the assessment day after the control period
