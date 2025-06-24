#  India Gender-wise Population Distribution (1960–2023)

This project visualizes India's gender-wise population distribution over time (1960–2023) using a stacked bar chart. It leverages population and gender percentage datasets from the World Bank to calculate and represent the actual male and female population each year.



##  Objective

To analyze and visualize how India's male and female populations have evolved from 1960 to 2023 by combining total population and gender percentage data.



##  Dataset Sources

The following datasets are obtained from the World Bank Open Data Portal:

- **Total Population**  
  **File:** `API_SP.POP.TOTL_DS2_en_csv_v2_76034.csv`  
  **Indicator:** *Population, total (SP.POP.TOTL)*

- **Male Population (% of total)**  
  **File:** `API_SP.POP.TOTL.MA.ZS_DS2_en_csv_v2_7765.csv`  
  **Indicator:** *Population, male (% of total) (SP.POP.TOTL.MA.ZS)*

- **Female Population (% of total)**  
  **File:** `API_SP.POP.TOTL.FE.ZS_DS2_en_csv_v2_7756.csv`  
  **Indicator:** *Population, female (% of total) (SP.POP.TOTL.FE.ZS)*

> **NOTE** Only these 3 main CSV files are used. Metadata CSVs are excluded.



##  Tools Used

- **Python**
- **Pandas** – For data loading and cleaning
- **Matplotlib** – For stacked bar chart visualization



##  Visualization

- **India Gender-wise Population Distribution (1960–2023):**  
  A stacked bar chart showing the male and female population each year from 1960 to 2023.



##  How to Run

1. Make sure Python is installed.
2. Download and place the 3 datasets in the same directory as the notebook.
3. Open and run:  
   `India_Population_Trends_BarChart.ipynb`



##  Folder Structure

 -API_SP.POP.TOTL_DS2_en_csv_v2_76034.csv
 
 -API_SP.POP.TOTL.MA.ZS_DS2_en_csv_v2_7765.csv
 
 -API_SP.POP.TOTL.FE.ZS_DS2_en_csv_v2_7756.csv
 
 -India_Population_Trends_BarChart.ipynb



##  Learning Points

- How to extract and clean structured CSV data from the World Bank
- How to handle and analyze large datasets using **Pandas**
- How to filter country-specific data for focused analysis
- How to create **Matplotlib** bar charts for temporal data
- How to calculate male and female population from percentage indicators
