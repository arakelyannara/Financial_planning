# FinanncialPlaning
This repo is a financial planner for emergencies. The second part is a 
useful tool that will forecast the performance of a retirement portfolio 
in 30 and 10 years. The tool will make an Alpaca API call via the Alpaca 
SDK to get historical data to use in Monte Carlo simulation.


---

## Technologies

JupyterLab web application

This project leverages python 3.7 with the following packages:

* [pandas](https://github.com/pandas-dev) 
* [json]
* [requests]
* [alpaca_trade_api]
* [os]
* [dotenv]

MCForecastTools.py should be in the the same folder <https://github.com/ranaroussi/pandas-montecarlo>

---

## Usage


To use the Financial Planning Analysis clone the repository, open it with Jupyterlab and run the 

* financial_planning_tools.ipynb

The folder should have 
* .env
hidden file with Alpaca key and Alpaca Secret key in following format

APCA_API_KEY = "Your API key"

APCA_API_SECRET_KEY = "Your API secret key"


## Contributors

        UC Berkley
---
## License

