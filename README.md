# diabetic-hospital-readmission-analysis
Healthcare data analysis exploring factors associated with 30-day hospital readmission among diabetic patients.

## About the Project

I used a dataset containing 101,766 hospital encounters to explore which patient and hospitalization characteristics were associated with 30-day readmission.

I focused mainly on medication burden, number of diagnoses, length of stay, age, medication changes, and insulin treatment. I first explored the data in Excel, then built an interactive dashboard in Tableau to make the main patterns easier to interpret.

## What I Wanted to Find Out

The main question was:

**Which characteristics are associated with a higher observed 30-day readmission rate among diabetic patients?**

In particular, I wanted to see whether medication and clinical complexity showed noticeable differences in readmission rates.

## Key Findings

### Medication burden

The clearest medication-related pattern was seen with the number of medications. The observed 30-day readmission rate increased from 4.2% among patients receiving one medication to about 13.8% among those receiving 24 medications.

### Number of diagnoses

Patients with more diagnoses generally had higher observed 30-day readmission rates. Among the larger diagnosis groups, the rate increased from 5.9% for one diagnosis to 12.4% for nine diagnoses.

### Length of stay

Readmission rates also increased with longer hospital stays. The observed rate rose from 8.2% for a one-day stay to about 14.4% for a ten-day stay.

### Age

Age showed a much weaker pattern. Most adult age groups had fairly similar observed 30-day readmission rates, suggesting that age alone was less informative than medication burden, clinical complexity, and length of stay in this analysis.

### Medication and insulin changes

I also compared readmission across medication-change and insulin-treatment groups. These differences were smaller than the patterns seen with medication burden, number of diagnoses, and length of stay, but they provided additional context around treatment complexity.

## What These Findings Could Mean

The results suggest that patients with a higher treatment burden, more complex clinical profiles, or longer hospital stays may be more likely to experience a 30-day readmission.

From a pharmacy perspective, these groups could be worth considering for more thorough medication reconciliation, discharge counseling, and follow-up after hospitalization.

These are observed associations from an exploratory analysis, not evidence that any of these factors directly cause readmission.

## Recommendations

Based on the patterns in the data, some practical areas to consider are:

* More detailed medication review for patients taking many medications.
* Closer discharge planning for patients with prolonged hospital stays.
* Additional follow-up for patients with multiple diagnoses or more complex treatment regimens.
* Greater involvement of pharmacists in medication reconciliation and transitions of care for higher-complexity patients.

## Dashboard

I built the final dashboard in Tableau Public.

**View the interactive dashboard:**
https://public.tableau.com/shared/Y24JTY2W5?:display_count=n&:origin=viz_share_link

## Tools

* Microsoft Excel
* Tableau Public
* GitHub

## Workflow

```text
Raw data
↓
Excel exploration and PivotTable analysis
↓
Identify patterns and key findings
↓
Tableau visualization
↓
Interactive dashboard
↓
Healthcare interpretation and recommendations
```

## Project Snapshot

* **101,766** hospital encounters
* **11.2%** overall observed 30-day readmission rate
* Medication burden analysis
* Clinical complexity analysis
* Length-of-stay analysis
* Interactive Tableau dashboard

## Important Note

This project is an exploratory portfolio analysis. The findings describe associations observed in the dataset and should not be treated as a validated clinical risk score or predictive model.
