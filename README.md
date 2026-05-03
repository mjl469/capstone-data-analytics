# capstone-data-analytics
##Capstone Project: Understanding Consumer Spending Depending on the State of the United States Economy

### Overview
This project aims to analyze consumer spending and how it relates to economic indicators.
It analyzes the effectiveness of an economic indicator that describes the economy objectively and an economic indicator that describes the economy based on consumer perception.
It also investigates consumer behavior depending on the state of the economy by analyzing how different spending categories change with respect to the economic indicators.
The project includes a report, Microsoft Power BI dashboard, and several python scripts used to accomplish these goals.

### Technologies Used
Jupyter Notebook (Pandas)
Microsoft Power BI
Microsoft Word

### How to Reproduce Analysis
1. Run the script "PCE_Category_Joining_and_Exporting.ipynb" ensuring the variable "folderpath" points to the appropriate folder containing the files found in "Raw_Data".
2. Compile the data found in "Seasonal_GDP_Growth_2022-2025.csv", "Consumer_Confidence_Index_2022-2025.csv", and "PCE_Joined.csv" into "Data.csv" appropriately.
3. Run the script "Exploratory_Data_Analysis.ipynb" ensuring the variable "folderpath" points to the appropriate folder containing the data.
4. Run the script "Models.ipynb" ensuring the variable "folderpath" points to the appropriate folder containing the data.
5. Follow the guide found in the "Power_BI" folder in this repository titled "Power_BI_Instructional_Report.pdf" establish connections to data for Power BI Dashboard properly.

### File Structure
Data
  Power_BI_Data
    CCI_Predictions_True_Values.csv
    Data.csv
    Economic_Indicator_Evaluation_Table.csv
    Economic_Indicator_Evaluation_Table_KPI_Targets.csv
    GDP_Growth_Predictions_True_Values.csv
    GDP_Growth_vs_CCI.csv
  Raw_Data
    Consumer_Confidence_Index_2022-2025.csv
    Personal_Consumption_Expenditures_2022-2025.csv
    Personal_Consumption_Expenditures_Durable_Goods_2022-2025.csv
    Personal_Consumption_Expenditures_Food_2022-2025.csv
    Personal_Consumption_Expenditures_Services_2022-2025.csv
    Seasonal_GDP_Growth_2022-2025.csv
  Transformed_Data
    Correlations.csv
    Data.csv
    Model_Evaluation_Table.csv
    PCE_Joined.csv
    Summary_Statistics.csv
Power_BI
  Dashboard.pbix
  Power_BI_Instructional_Report.pdf
Report
  Capstone_Project_Final_Report_Michael_Lawlor.docx
  Capstone_Project_Final_Report_Michael_Lawlor.pdf
Scripts
  Exploratory_Data_Analysis.ipynb
  Models.ipynb
  PCE_Category_Joining_and_Exporting.ipynb
README.md

### Author
Michael Lawlor
+1 (480) 262-9296
mlawlor1699@gmail.com
