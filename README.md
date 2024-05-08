COVID-19 India Data Scraper
This Python script fetches COVID-19 data for Indian states from the official COVID-19 India website and extracts specific information such as confirmed cases, deceased cases, recovered cases, and active cases for a chosen state (e.g., Maharashtra).

Prerequisites
Python 3.x
Requests library (install using pip install requests)
Usage
Clone or download this repository to your local machine.
Navigate to the directory containing the Python script (covid_data_scraper.py).
Run the script using Python:
python covid_data_scraper.py
The script will fetch the latest COVID-19 data from the COVID-19 India website and display specific information for the chosen state.
Output
The script outputs the following information for the chosen state:

Date
Confirmed cases
Deceased cases
Recovered cases
Active cases (calculated as confirmed - deceased - recovered)
Example
Here's an example of the output for the state of Maharashtra:

Data for Maharashtra:
Date: 2022-04-27
Confirmed cases: 1200000
Deceased cases: 20000
Recovered cases: 1100000
Active cases: 80000
---------------------------------
Date: 2022-04-28
Confirmed cases: 1210000
Deceased cases: 20100
Recovered cases: 1110000
Active cases: 79000
---------------------------------
...
