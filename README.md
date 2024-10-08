# ACS Juvenile Justice Project
This project is based on the Administration for Children's Services's (ACS) updated Flash report hosted on NYC's Open Data website. The Flash report provides monthly performance data on key ACS child welfare, child care, and juvenile justice functions such as children using vouchers for child care, child protective caseloads, and the number of admissions to detention. Each row of data in the Excel file posted to Open Data is a distinct measure in the Flash Report. The columns are the month of the data. Data are updated semiannually in September and April using data from queries of administrative data systems and data provided directly from program areas.<br>
This project focuses on the ACS juvenile justice demographics and the detention rates of the youth residing in New York City. After examining the key features of the dataset, I will create an ARIMA model to attempt to predict youth detention levels in fiscal year 2025. This project is applicable to determining budgets for upcoming fiscal years and addressing capacity concerns in the event of an unforeseen influx or decrease in new clients. 
<br>
Dataset and data definitions can be found [here](https://data.cityofnewyork.us/City-Government/Monthly-Flash-Report-indicators/2ubh-v9er/about_data): <br>

## Installation
1. Clone the repository: `git clone https://github.com/WilliamHallPortfolio/ACS_Juvenile_Justice_Project.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the Google Colab Notebook: `(https://colab.research.google.com/github/WilliamHallPortfolio/ACS_Juvenile_Justice_Project/blob/main/ACS%20Flash%20Report%20Project.ipynb)`

## Usage
Click the Open in Colab button in `ACS Flash Report Project.ipynb` to load data, preprocess it, and train predictive models.

## Project Structure
- `data/` - Contains datasets used in the analysis.
- `ACS Flash Report Project.ipynb` - Main analysis notebook.

## Contributing
Feel free to submit issues or pull requests. Contributions are welcome!

## License
This project is licensed under the MIT License.

## Contact
For questions, contact William Hall at `w.hallds2024@gmail.com`

