# Keene Kelderman's Data Portfolio

# Project 1: [Flatiron Capstone - MTBS Wildfire Analysis](https://github.com/hkkelderman/FI-MTBS_Fire_Analysis)
Used statistical testing and parametric and nonparametric modeling techniques to explore and model a federally maintained database of wildfires.

- Joined historical climate data from NOAA and geographical data from EPA to the wildfire dataset using GeoPandas
- Used parametric and nonparametric modeling to model fire size based on various climate and geographical data points
- Performed statistical testing in order to determine regions and states at risk for increased wildfire size

<img src="https://raw.githubusercontent.com/hkkelderman/FI-MTBS_Fire_Analysis/main/Images-Used/wildfire_inf.gif" width = "600">

# Project 2: [EPA WebFIRE website scraper](https://github.com/hkkelderman/EIP-WebFIRE-Benzene-Scraper)
This is a Python script written to scrape fenceline benzene data from [EPA's WebFIRE Report Search](https://cfpub.epa.gov/webfire/reports/esearch2.cfm) page, using Selenium. Though this is specific to downloading and unzipping folders containing benzene fenceline data, the code can certainly be modified to bulk download other reports from other subsections of this webpage. This script works only on those results that return fewer than 500 records, as the pagination associated with results that have over 500 records is slightly more complicated and has not yet been accounted for in this program.

# Project 3: [Flatiron Mod 4 Project - Zillow Time Series](https://github.com/hkkelderman/FI-Zillow-Time-Series)
I created an AutoRegressive Integrated Moving Average (ARIMA) time series model to determine the best zipcodes for investment. The model was generated using historical median house sales from Zillow all the way back from 1996 from across the entire United States. There were a lot more factors to consider than what what was accounted for with the dataset provided, which is why this particular dataset was a little too simple for predicting solid investments. By only providing the historical median housing sales by zip code, it was hard to calculate things like risk or account for factors that might affect resale value, like economic growth and proximity to amenities. Some basic investment recommendations were made.

By pairing the Zillow dataset with other datasets, like Census data, economic growth, and other housing datasets that include additional data related to risk, profitability, and proximity, you'd be able to create a much more robust model and be able to recommend better potential targets for investment.

