# Panic Attack Data Analysis Dashboard

## Dashboard Link : 

## Problem Statement

This dashboard provides insights into panic attack symptoms and related behaviors in patients. By visually exploring symptom frequencies, lifestyle patterns, and demographic breakdowns, healthcare professionals and researchers can identify key factors associated with panic attacks.

### Steps followed 

Step 1: Stored the raw dataset in Snowflake, created tables and columns for patient data and symptoms.

Step 2: Connected Power BI to the Snowflake data warehouse using proper credentials.

Step 3: Loaded and transformed the data within Power BI, ensuring columns (symptoms, drinks per week, sleep hours, etc.) were imported correctly.

Step 4: Cleaned and profiled the data for errors and missing entries.

Step 5: Used DAX Power Queries (with IF and SWITCH functions) to create a custom Age Category column: Child, Adolescent, Adult.

Step 6: Created visuals like bar charts for symptom counts, card visuals for summary metrics, and slicers to filter by demographic or trigger type.

Step 7: Published the dashboard to the Power BI service for sharing and collaboration.

Dashboard Snapshots
Insert images/snapshots here of your Power BI dashboard displaying symptom counts, age categories, and summary insights.


## Snapshot of Dashboard (Power BI Service)



 

# Insights

## |Symptom | Frequency|

Dizziness || 620 patients reported; 580 did not.

Trembling || 590 reported; 610 did not.

Sweating || reported; 364 did not.

Shortness of breath || 746 reported; 454 did not.

Chest pain: 487 reported || 713 did not.


### Behavioral Factors

Drinks per week data show varied distributions, e.g. 127 at 0 drinks, 125 at 2 drinks, etc.

Sleep hours distribution is visualized from 4 to 10 hours per night.

Panic attack duration varies commonly between 10 and 40 minutes.

### Age Category

Age categories created via DAX: Child, Adolescent, Adult; used for group-wise analysis.

### Medical History & Triggers

Dashboard displays medical history categories (Anxiety, Depression, None) and triggers (Caffeine, Phobia, PTSD).

## Aggregated Statistics

Average sleep hours, panic score, attack frequency analyzed by age group and trigger type for better understanding patterns.
 
 
 ## Conclusions
 
This BI dashboard demonstrates how panic attack data can be visually analyzed by **symptom, lifestyle, triggers, and age group**. The dashboard makes it easier to spot patterns and explore demographic variations, providing a solid foundation for further health analytics projects.
