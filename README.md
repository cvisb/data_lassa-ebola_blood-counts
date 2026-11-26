# Lassa/Ebola Blood Counts Dataset

Blood cell count measurement data of Ebola or Lassa survivors and non-survivors during the acute phase of infection.

| | |
|---|---|
| Records | 615 |
| Samples | 615 |
| With a patient identifier | 615 |
| Cohort | Lassa (597), Ebola (18) |
| Outcome | Unknown (355), Survivor (169), Dead (91) |
| Country | Sierra Leone (615) |
| Years | 2011–2019 |
| Technique | Blood Cell Count |
| Version | 0.4 |

## Files

| File | Rows | Description |
|---|---|---|
| `metadata.csv` | 615 | Sample and patient metadata |
| `blood_counts.csv` | 615 | Blood cell counts and coagulation |
| `dataset.json` | – | Dataset description in schema.org format |

## Columns in `metadata.csv`

| Column | Description |
|---|---|
| `experimentID` | Experiment identifier |
| `sample_id` | Sample identifier, shared across CViSB datasets |
| `timepoint` | Point in care the reading was taken at |
| `patientID` | Patient identifier, where known |
| `cohort` | Ebola, Lassa |
| `outcome` | Dead, Survivor, Unknown |
| `country` | Country of infection |
| `year` | Year of infection |

## Columns in `blood_counts.csv`

| Column | Description |
|---|---|
| `wholeBloodCount` | White blood cell count (cells/µL) |
| `hemoglobin` | Haemoglobin (g/dL) |
| `platelets` | Platelet count |
| `neutrophils` | Neutrophils (% of white cells) |
| `lymphocytes` | Lymphocytes (% of white cells) |
| `monocytes` | Monocytes (% of white cells) |
| `eosinophils` | Eosinophils (% of white cells) |
| `basophils` | Basophils (% of white cells) |
| `bands` | Band neutrophils (%), counted separately from the above |
| `prothrombinTime` | Prothrombin time (seconds) |
| `internationalNormalizedRatio` | International normalised ratio |
| `dDimer` | D-dimer |

## Licence

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Please cite the Center for Viral Systems Biology (CViSB).

Funded by NIAID award U19AI135995.
