# ACS_Juvenile_Justice_Project
This project is based on ACS updated Flash report. The Flash report provides monthly performance data on key ACS child welfare, child care, and juvenile justice functions such as children using vouchers for child care, child protective caseloads, and the number of admissions to detention. Each row of data in the Excel file posted to Open Data is a distinct measure in the Flash Report.The columns are the month of the data. Data are updated semiannually in September and April using data from queries of administrative data systems and data provided directly from program areas.<br>
This project focuses on Juvenile Justice and detention rates of the youth residing in New York City. After examining the key features of the dataset, I will create an ARIMA model to attempt to predict youth detention levels in fiscal year 2025. The IDE used in this project will be Google Colab notebook. <br> 
<br>
Dataset and data definitions can be found here:
https://data.cityofnewyork.us/City-Government/Monthly-Flash-Report-indicators/2ubh-v9er/about_data
<br>
First we import the following libraries: <br>
![image](https://github.com/user-attachments/assets/8a1b2aa8-5f18-4407-871e-dc22cf0761e2) <br>
<br>
After importing the dataset provided from the City of New York, we can see that the shape of the dataset is 86 rows and 115 columns:
![image](https://github.com/user-attachments/assets/39a3cec5-558c-4487-aad2-664459c33530)

