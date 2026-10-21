# Child Health & Lifestyle Analysis

## Project Overview

This project explores how daily screen time and physical activity relate
to common health problems among school-age children aged 6--17. Using
Python, the analysis cleans and prepares the dataset, summarizes
lifestyle patterns, measures the prevalence of health conditions, and
visualizes relationships between lifestyle habits and health indicators.

## Project Objectives

-   Clean and prepare the dataset by checking duplicates, missing
    values, inconsistent categories, invalid values, and outliers.
-   Measure the prevalence of eye problems, sleeping issues, obesity,
    vitamin D deficiency, and chronic constipation.
-   Explore the relationship between screen time and eye problems or
    sleeping issues.
-   Explore the relationship between physical activity and obesity,
    vitamin D deficiency, sleeping issues, and chronic constipation.
-   Count the number of co-occurring health issues per child.
-   Present findings through clear charts and practical recommendations.

## Dataset

-   **Source:** Kaggle --- `child_health_lifestyle`
-   **Initial dataset:** 6,064 records and 14 columns, as documented in
    the notebook.
-   **Final cleaned dataset:** 6,054 children aged 6--17.
-   **Geographic coverage:** 8 schools across 16 US cities, according to
    the notebook.

### Main features

-   **Demographics:** `Name`, `Gender`, `Age`, `School`, `City`,
    `Country`
-   **Lifestyle:** `Physical_Activity_hours_per_day`,
    `Screen_Time_hours_per_day`
-   **Health indicators:** `Eye_Problems`, `Sleeping_Issues`, `Obesity`,
    `Vitamin_D_Deficiency`, `Chronic_Constipation`

## Tools & Libraries

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Plotly
-   Jupyter Notebook

## Workflow

1.  **Load and inspect the data** --- review the dataset structure,
    column names, data types, summary statistics, and dimensions.
2.  **Clean the data** --- identify and remove duplicate records, handle
    missing values, standardize inconsistent categories, and address
    invalid age values.
3.  **Perform exploratory data analysis (EDA)** --- summarize numerical
    and categorical variables and compare lifestyle measures across
    ages, schools, and cities.
4.  **Visualize patterns** --- use histograms, pie charts, line charts,
    bar charts, box plots, scatter plots, a heatmap, and count plots.
5.  **Summarize findings** --- report health-condition prevalence,
    examine lifestyle associations, and count co-occurring health
    issues.

## Key Findings

### Lifestyle patterns

-   Average screen time: **2.77 hours per day** (median: 3 hours).
-   Average physical activity: **1.29 hours per day** (median: 1 hour).
-   Approximately **1,000 children (16.5%)** report zero hours of
    physical activity.
-   Average screen time rises from approximately **2.51 hours at age 6**
    to **3.01 hours at age 17**.

### Health-condition prevalence

  Health condition         Children   Percentage
  ---------------------- ---------- ------------
  Eye problems                1,373       22.68%
  Vitamin D deficiency        1,348       22.27%
  Sleeping issues             1,086       17.94%
  Obesity                     1,035       17.10%
  Chronic constipation          421        6.95%

### Patterns observed in the notebook

-   Higher screen-time groups show higher reported prevalence of eye
    problems and sleeping issues in this dataset.
-   Higher physical-activity groups show lower reported prevalence of
    obesity, vitamin D deficiency, sleeping issues, and chronic
    constipation.
-   Eye-problem prevalence does not show the same clear pattern across
    physical-activity groups.
-   Most children have zero or one reported health condition; a smaller
    group has multiple co-occurring conditions.

These are observational patterns in this dataset. They do not establish
that screen time or physical activity causes a health condition. The
results may also be affected by data quality, sample characteristics,
and other factors.

## Visualizations

The notebook includes: 1. Histograms for numerical variables 2.
Gender-distribution pie chart 3. Average screen time by age line chart
4. Student counts by school bar chart 5. Age box plot 6. Age versus
physical activity scatter plot 7. Health-condition prevalence bar chart
8. Physical activity and health-condition heatmap 9. Screen time and
selected health conditions bar chart 10. Distribution of children by
number of co-occurring health issues

## Recommendations Suggested by the Analysis

-   Encourage balanced, age-appropriate screen use and screen-free time
    before bedtime.
-   Provide opportunities for regular physical activity, including for
    children reporting zero activity.
-   Consider outdoor activity and appropriate follow-up for children who
    may be at risk of vitamin D deficiency.
-   Support routine school health checks, including vision and general
    health screening.
-   Pay attention to children reporting multiple health issues and refer
    concerns to qualified healthcare professionals.

These are general suggestions based on the observed patterns, not
medical advice or proof of cause and effect.

## How to Run the Project

1.  Download or clone this repository.

2.  Install the required libraries:

    ``` bash
    pip install pandas numpy matplotlib seaborn plotly openpyxl jupyter
    ```

3.  Place the source Excel dataset in the expected location or update
    the file path in the notebook.

4.  Open `child_health_lifestyle_analysis.ipynb` in Jupyter Notebook or
    JupyterLab.

5.  Run the notebook cells in order.

**Note:** The notebook currently loads the Excel file using a Google
Colab path: `/content/MAIN_PROJECT-health_dataset_v7.xlsx` Update this
path to match your local environment before running the notebook.

## Project Files

-   `child_health_lifestyle_analysis.ipynb` --- notebook containing data
    cleaning, EDA, visualizations, and findings.
-   `README.md` --- project overview and documentation.
-   Source Excel dataset --- provide separately if you have permission
    to share it.

## Limitations

-   The analysis describes associations in the available dataset and
    cannot establish causation.
-   Findings depend on the accuracy and representativeness of the source
    data.
-   Health indicators in this dataset should not be treated as clinical
    diagnoses.

## Author

**Shamshad Mansoor**\
Data Analytics Portfolio Project
