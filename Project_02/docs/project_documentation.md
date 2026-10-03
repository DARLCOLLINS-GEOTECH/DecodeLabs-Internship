# Project 2 Documentation --- Exploratory Data Analysis

## What the project required

Project 2 was the exploratory data analysis stage. The requirement was
to analyze a dataset to understand its patterns, trends, and
distributions; calculate basic descriptive statistics such as **mean,
median, and count**; identify trends and outliers; and summarize the
most important observations.

## What I did

I used the cleaned e-commerce dataset containing **1,200 orders** and
performed the analysis in Excel.

-   Generated descriptive statistics for `Quantity`, `ItemsInCart`, and
    `TotalPrice`.
-   Calculated quartiles, interquartile range, and upper/lower bounds to
    investigate outliers.
-   Identified **8 TotalPrice observations above the IQR upper bound of
    3,333.53** and treated them as values requiring investigation rather
    than automatically deleting them.
-   Built PivotTables to explore monthly and annual order value, product
    performance, order fulfilment status, promotional offers, customer
    acquisition channels, and payment methods.
-   Summarized the dataset using key measures including **1,200
    orders**, **3,535 units ordered**, and **\$1,264,761.96 total
    recorded order value**.

## Selected findings

-   Average order value was approximately **\$1,053.97**, while the
    median was **\$823.62**, showing a positively skewed order-value
    distribution.
-   Chairs generated the highest recorded product order value at
    approximately **\$195,620.11**, closely followed by Printers.
-   Instagram was the largest customer acquisition channel by both order
    count (**259**) and recorded order value (approximately
    **\$275,285.45**).
-   Cancelled and Returned orders totalled **497 records**, representing
    approximately **41.4%** of all orders and warranting further
    investigation.
-   June 2024 recorded the highest individual month-year order value in
    the dataset at approximately **\$68,068.54**.

## Repository contents

-   `data/cleaned_data.xlsx` --- analysis-ready dataset.
-   `data/eda_analysis.xlsx` --- descriptive statistics and PivotTable
    analysis.
-   `docs/project_documentation.md` --- summary of the project
    requirement, method, and findings.
-   `visuals/` --- descriptive-statistics, PivotTable, and EDA
    visualization snapshots.

## Outcome

The analysis converted the cleaned order records into a structured
understanding of the dataset's distributions, trends, outliers, and
category-level performance. These findings then provided the analytical
foundation for the visualization and data-storytelling work in Project
4.
