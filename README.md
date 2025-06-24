#  India Population Trends (1960–2023)

This project visualizes the total population trends of India from 1960 to 2023 using a bar chart, based on authentic data from the World Bank. It also provides the gender-wise distribution (male and female) using additional population percentage datasets.



##  Objective

To create a clear and informative visualization of India’s population growth over time, and understand gender distribution based on percentage data.



## Dataset Sources

The datasets are downloaded from the World Bank Open Data Portal:

- **Total Population**  
  **File:** `API_SP.POP.TOTL_DS2_en_csv_v2_76034.csv`  
  **Indicator:** *Population, total (SP.POP.TOTL)*

- **Male Population (% of total)**  
  **File:** `API_SP.POP.TOTL.MA.ZS_DS2_en_csv_v2_7765.csv`  
  **Indicator:** *Population, male (% of total) (SP.POP.TOTL.MA.ZS)*

- **Female Population (% of total)**  
  **File:** `API_SP.POP.TOTL.FE.ZS_DS2_en_csv_v2_7756.csv`  
  **Indicator:** *Population, female (% of total) (SP.POP.TOTL.FE.ZS)*

>  *Note: Only these 3 main CSV files are used. Metadata files have been excluded.*



##  Tools Used

- **Python**
- **Pandas** – Data loading and manipulation
- **Matplotlib** – Data visualization



##  Visualizations

- **India Total Population (1960–2023):**  
  A bar chart showing population change over time.

- **(Optional) 2022 Gender Distribution in India:**  
  A bar chart showing male vs female population counts for the year 2022 based on percentage data.



##  How to Run

1. Ensure Python is installed on your system.
2. Place the 3 CSV files in the same directory as the notebook.
3. Open and run the notebook:  
   `India_Population_Trends_BarChart.ipynb`



##  Output Sample

You can add a screenshot of the final visualization here.



##  Folder Structure

India_Population_Trends_BarChart/
│
├── API_SP.POP.TOTL_DS2_en_csv_v2_76034.csv
├── API_SP.POP.TOTL.MA.ZS_DS2_en_csv_v2_7765.csv
├── API_SP.POP.TOTL.FE.ZS_DS2_en_csv_v2_7756.csv
└── India_Population_Trends_BarChart.ipynb



##  Learning Points

- How to extract and clean structured CSV data from the World Bank
- How to handle and analyze large datasets using **Pandas**
- How to filter country-specific data for focused analysis
- How to create **Matplotlib** bar charts for temporal data
- How to calculate male and female population from percentage indicators

