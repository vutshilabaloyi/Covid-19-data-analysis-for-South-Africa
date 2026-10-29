# Covid-19-data-analysis-for-South-Africa
## Project Overview
The project does analysis of Covid-19 data for South Africa in comparison to six other Southern African countries: Namibia, Botswana, Zimbabwe, Eswatini, Mozambique and Lesotho.

Using Python, Pandas and Matplotlib, I looked at the recorded Covid-19 data and identified trends, visualized changes in the reported cases and deaths and compared the impact of the pandemic across these countries. 

## Objectives
* Explore and understand a large Covid-19 dataset
* Filter records by country and date
* Look at changes in Covid-19 cases and deaths over time
* Compare the cumulative cases and deaths across seven Southern African countries
* Visualize the trends using python
* Interpret the results but also looking at the limitations of the data

## Tools and Technologies
* Python - data analysis and processing
* Pandas - Data loading, filtering and manipulation
* Matplotlib - Data visualization
* Juptyer Notebook - Interactive analysis and documantation

## Countries
1. South Africa
2. Namibia
3. Botswana
4. Zimbabwe
5. Eswatini
6. Mozambique
7. Lesotho










## Project Workflow
1. Data Loading and Exploration:

I loaded the COVID-19 dataset into a Pandas DataFrame and explored its structure, columns, and available observations. The dataset contains multiple COVID-19 indicators recorded over time for different countries.

2. Data Filtering

I used Pandas to select specific countries and filter observations by date, allowing me to focus on the period relevant to the analysis.

3. Data Visualisation

I used Matplotlib to create graphs showing how reported COVID-19 cases and deaths changed over time. These visualisations made it possible to examine trends and compare recorded figures across countries.

4. Country Comparison

I compared the reported figures for the seven selected countries. Because countries have different population sizes, comparisons based on deaths per million people can provide additional context beyond cumulative death totals.

5. Interpretation

I examined the patterns shown by the graphs and considered how differences in population size, testing capacity, and reporting practices could affect comparisons between countries.

## Key Findings

The visualisations show differences in the recorded COVID-19 cases and deaths across the selected Southern African countries.

South Africa has the highest cumulative recorded death total among the countries compared in the analysis. Its larger totals also make it difficult to see the trends of countries with smaller totals when all countries are displayed on the same vertical scale.

Comparing deaths per million people provides another perspective by accounting for differences in population size.

The graphs also demonstrate how reported COVID-19 figures changed over time, allowing periods of increasing totals and slower growth to be identified.

These findings describe patterns in the dataset and should not be interpreted as definitive evidence that one country experienced a more severe pandemic impact than another.

## Limitations

* Reported data: Recorded cases and deaths may not capture every COVID-19 infection or death associated with the pandemic.
* Population differences: Countries have different population sizes, making raw totals difficult to compare directly.
* Reporting differences: Testing capacity, reporting practices, and healthcare resources may differ between countries.
* Data quality: Missing values, reporting delays, and revisions may affect the observed trends.
* Interpretation: Differences in reported figures alone do not establish the effectiveness of a country's pandemic response.

## Dataset

The dataset used in this project is approximately 178 MB and is not included in this repository because of its size.

Original source: https://ourworldindata.org/covid-deaths

To reproduce the analysis, obtain the dataset from its original source and place the CSV file in the same directory as the Jupyter Notebook.

The notebook currently expects the dataset to be named: covid19data.csv

## How to Run the Project
Install Python and Jupyter Notebook, then install the required libraries.
pip install pandas matplotlib jupyter
### Instructions
1. Clone or download this repository.
2. Obtain the COVID-19 dataset from its documented original source.
3. Place covid19data.csv in the same directory as the notebook.
4. Launch Jupyter Notebook.
5. Open covid19_data_analysis.ipynb.
6. Run the notebook cells to reproduce the analysis and visualisations.

## Conclusion

This project demonstrates how Python can be used to explore real-world public health data, visualise trends over time, and compare reported COVID-19 outcomes across Southern African countries.

It also highlights the importance of data quality, appropriate comparisons, and careful interpretation when working with real-world datasets.

The project forms part of my ongoing development in Python, data analysis, and data visualisation.

Author: Vutshila Ayliff Baloyi
