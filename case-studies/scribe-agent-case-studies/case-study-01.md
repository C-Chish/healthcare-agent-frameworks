# Medication Reconciliation & Longitudinal Audit

## Overview
[span_0](start_span)[span_1](start_span)This repository contains the longitudinal medication reconciliation documentation for Michael Thompson, NHI XYZ7890[span_0](end_span)[span_1](end_span). [span_2](start_span)The audit integrates primary care electronic health records[span_2](end_span) [span_3](start_span)with the recent hospital discharge summary following an elective left total hip replacement[span_3](end_span). 

All data processing complies with the Health Information Privacy Code (HIPC) 2020 and utilizes SNOMED CT terminology principles.

## Clinical Context
* **[span_4](start_span)Recent Event:** Elective left total hip replacement for severe osteoarthritis[span_4](end_span).
* **[span_5](start_span)Admission Dates:** 12 January 2026 to 20 January 2026[span_5](end_span).
* **[span_6](start_span)Complications:** Acute Kidney Injury (Stage 2) developed post-operatively[span_6](end_span).
* **[span_7](start_span)Renal Function:** Baseline creatinine was 92 µmol/L[span_7](end_span). [span_8](start_span)Peak creatinine was 168 µmol/L on day 3 post-op[span_8](end_span). [span_9](start_span)Discharge creatinine was 118 µmol/L[span_9](end_span).
* **[span_10](start_span)Medication Changes:** NSAIDs were ceased due to the Acute Kidney Injury[span_10](end_span). 

## Medication Reconciliation Table

| Medication (Generic) | Duration of Therapy | Original Indication | Last Lab Check-up | Review Required? |
| :--- | :--- | :--- | :--- | :--- |
| Metformin | [span_11](start_span)8 years (Started 2018)[span_11](end_span) | [span_12](start_span)Type 2 Diabetes Mellitus[span_12](end_span) | [span_13](start_span)Discharge Creatinine: 118 µmol/L[span_13](end_span) | Yes. [span_14](start_span)Withhold if eGFR < 30[span_14](end_span). [span_15](start_span)Repeat U&E requested 5-7 days post-discharge[span_15](end_span). |
| Amlodipine | [span_16](start_span)5 years (Started 2021)[span_16](end_span) | [span_17](start_span)Hypertension[span_17](end_span) | [span_18](start_span)Discharge Creatinine: 118 µmol/L[span_18](end_span) | Yes. [span_19](start_span)Review blood pressure and adjust antihypertensives as required[span_19](end_span). |
| Atorvastatin | [span_20](start_span)7 years (Started 2019)[span_20](end_span) | [span_21](start_span)Lipid Disorder[span_21](end_span) | [span_22](start_span)LDL: 2.4[span_22](end_span) | No. Routine monitoring. |
| Pantoprazole | [span_23](start_span)8 months (Started Jun 2025)[span_23](end_span) | GI Protection / Unspecified | N/A | Yes. [span_24](start_span)Reassess ongoing need as NSAID therapy has been ceased[span_24](end_span). |
| Ibuprofen | [span_25](start_span)Ceased Jan 2026[span_25](end_span) | [span_26](start_span)Osteoarthritis Hip (Left)[span_26](end_span) | [span_27](start_span)Discharge Creatinine: 118 µmol/L[span_27](end_span) | Yes. [span_28](start_span)Ceased during admission due to AKI[span_28](end_span). Ensure primary care record is updated. |
| Enoxaparin | Started Jan 2026 | Post-operative VTE Prophylaxis | [span_29](start_span)Discharge Creatinine: 118 µmol/L[span_29](end_span) | Yes. [span_30](start_span)Prescribed for 35 days total[span_30](end_span). Discontinue upon completion. |

## Safety Protocol & Clinical Governance
* **Decision Support Notice:** You are decision-support only. Human clinician sign-off is mandatory.
* **Guidelines:** I cannot find current NZ clinical guidance on this topic regarding exact restart protocols for Metformin post-AKI in this specific synthetic scenario. Please consult the NZ Formulary and local HealthPathways for definitive guidance.
