# Project 1 Documentation: 
---
## Data Cleaning and Preparation

## What the project required

Project 1 focused on preparing a dataset for analysis by checking and
resolving common data-quality issues such as duplicate or recurring
records, missing values, unwanted spaces or non-printable characters,
inconsistent formatting, and incorrect data types. The cleaned dataset
also needed to remain traceable to the original data so that the
preparation process could be reviewed.

## What I did

I worked with the e-commerce order dataset in Excel and documented the
cleaning steps in an Action Log.

-   Checked the dataset for duplicate or recurring records and cleaned
    unwanted characters using Excel cleaning functions such as `CLEAN`
    and `TRIM`.
-   Reviewed missing values and replaced 309 blank entries in the
    `CouponCode` field with **No Coupon** so that the records were
    retained rather than deleted.
-   Standardized columns to appropriate data types, including text,
    dates, numbers, codes, and currency fields.
-   Preserved a final cleaned dataset of **1,200 order records** for
    subsequent analysis.
-   Maintained an Action Log describing each change, its impact, and its
    resolution status.

## Repository contents

-   `data/raw_data.xlsx` --- original order data used as the starting
    point.
-   `data/cleaned_data.xlsx` --- cleaned and analysis-ready version of
    the dataset.
-   `docs/project_documentation.md` --- brief explanation of the
    requirement and completed work.
-   `visuals/` --- snapshots of the raw data, cleaned data, and cleaning
    Action Log.

## Outcome

The dataset was converted into a consistent, analysis-ready form while
retaining all 1,200 final records. The cleaned data became the source
for the exploratory analysis and visualization projects that followed.
