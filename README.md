# Week 11 Learning Log: Settling on Data Sources and Acquiring Data

Name: Amelia Pucek

Date: 04/17/2026

Course: CS-215

---

## Dataset Selection

For this project, I decided to work with a global literacy rates dataset from Our World in Data. I chose this dataset because it provides literacy rate information across countries and years, making it useful for analyzing long-term global education trends and differences between countries.

The dataset includes country names, country codes, years, and literacy rates among adults.

---

## Acquiring the Dataset

I successfully obtained the dataset as a CSV file from Our World in Data and imported it into a Google Colab notebook using pandas. After importing the dataset, I performed initial exploratory analysis to better understand its structure and identify potential cleaning issues.

---

## Strengths and Limitations

One strength of this dataset is that it contains literacy information across many countries and years, allowing for broad comparisons and trend analysis.

However, there are several limitations that need to be considered:
- Some country codes are missing
- Coverage is uneven across countries and years
- Literacy may be measured differently across countries

This dataset is useful for identifying large-scale trends and patterns, but it should not be used to make strong causal claims about education systems or policy effectiveness.

---

## Dataset Provenance and Considerations

This dataset was published by Our World in Data and appears to compile literacy statistics from international organizations and national reporting sources. Because the data comes from multiple countries and years, collection methods may differ across observations.

The dataset likely represents a sample of available literacy measurements rather than a perfectly complete global record. Some countries and years are represented more heavily than others, which may affect comparisons and trend analysis.

This is important to consider when interpreting the data, since differences in methodology or reporting standards could influence literacy estimates.

---

## Preliminary Analysis

During exploratory analysis, I found that the dataset contains 1,725 rows and 4 columns. Literacy rates range from 9% to 100%, showing significant variation across countries and years.

I also found that the Code column contains many missing values, while the other columns are mostly complete. No duplicate rows were detected in the dataset.

---

## Initial Visualization

![Average Global Literacy Rate Over Time](literacy_trend.png)

The graph shows a general increase in average literacy rates over time. This suggests that literacy has improved globally across recent decades, although differences in country coverage across years may affect the averages.

---

## Data Cleaning and Wrangling

So far, I have:
- Imported the dataset into Python using pandas
- Checked for missing values
- Verified there are no duplicate rows
- Explored summary statistics and dataset structure

Future cleaning and wrangling steps may include:
- Handling missing country codes
- Checking for inconsistencies in country names
- Preparing the data for additional visualizations and analysis

---

## Challenges and Roadblocks

One challenge is understanding how literacy data was collected across different countries and years, since measurement methods may vary.

Another challenge is handling incomplete country code information and ensuring consistent comparisons across time periods.

---

## Google Colab Notebook

[Click to go to my Google Colab](https://colab.research.google.com/drive/126I5cjCoF5vQQR2Rh44y-D0dL90q7FAX?usp=sharing)