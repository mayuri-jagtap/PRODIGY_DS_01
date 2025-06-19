

📌India Population Trends (1960–2023)

This project visualizes the total population trends of India from 1960 to 2023 using a bar chart, based on authentic data from the World Bank. It also provides the gender-wise distribution (male and female) using additional population percentage datasets.

📌Objective:
To create a clear and informative visualization of India’s population growth over time, and understand gender distribution based on percentage data.

📌Dataset Sources:
The datasets are downloaded from the World Bank Open Data Portal:

1. Total Population
   File: API\_SP.POP.TOTL\_DS2\_en\_csv\_v2\_76034.csv
   Indicator: Population, total (SP.POP.TOTL)

2. Male Population (% of total)
   File: API\_SP.POP.TOTL.MA.ZS\_DS2\_en\_csv\_v2\_7765.csv
   Indicator: Population, male (% of total) (SP.POP.TOTL.MA.ZS)

3. Female Population (% of total)
   File: API\_SP.POP.TOTL.FE.ZS\_DS2\_en\_csv\_v2\_7756.csv
   Indicator: Population, female (% of total) (SP.POP.TOTL.FE.ZS)

📌Note: Only these 3 main CSV files are used. Metadata files have been excluded.

📌Tools Used:

* Python
* Pandas – Data loading and manipulation
* Matplotlib – Visualization

📌Visualizations:

1. India Total Population (1960–2023):
   A bar chart showing population change over time.

2. (Optional) 2022 Gender Distribution in India:
   A bar chart showing male vs female population counts for the year 2022, based on percentage.

📌How to Run:

1. Make sure you have Python installed.
2. Place the 3 datasets in the same directory as the notebook.
3. Run the notebook: India\_Population\_Trends\_BarChart.ipynb

📌Output Sample:
(You can add a screenshot later)

📌Folder Structure:

India\_Population\_Trends\_BarChart
├── API\_SP.POP.TOTL\_DS2\_en\_csv\_v2\_76034.csv
├── API\_SP.POP.TOTL.MA.ZS\_DS2\_en\_csv\_v2\_7765.csv
├── API\_SP.POP.TOTL.FE.ZS\_DS2\_en\_csv\_v2\_7756.csv
├── India\_Population\_Trends\_BarChart.ipynb

📌Learning Points:

* How to extract and clean structured CSV data from the World Bank
* How to work with large datasets using Pandas
* How to filter country-specific data for analysis
* How to visualize data using Matplotlib bar charts
* How to calculate male and female population values from percentage data

