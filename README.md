# CanHomeOwner
![Header](headerCanhomeOwner.png)
![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-blue)
![Data Analysis](https://img.shields.io/badge/Data-Analysis-brightgreen)
![Machine Learning](https://img.shields.io/badge/Data-Analysis-brightgreen)

A comprehensive analysis tool focusing on the Canadian real estate market. It integrates financial, demographic, and regional data to provide insights into housing affordability, investment opportunities, and market trends.

## Project Overview

This project aims to address critical questions in real estate investment and personal housing decisions by analyzing various economic and demographic factors. It serves as a decision-making tool for individuals exploring the dynamics of the Canadian real estate market.

## Features

- **Economic Factors Analysis:** Correlation of home prices with interest rates, inflation, and immigration.
- **Affordability Assessment:** Visualization of housing prices across Canada considering personal financial constraints.
- **Rent vs. Buy Analysis:** Comparative study of mortgage payments versus rent.
- **School Quality Impact:** Exploration of how school rankings influence real estate values.
- **Income-Based Real Estate Affordability:** Analysis of home prices against different income levels.

## Technologies Used

- **Data Visualization:** Seaborn, HvPlot
- **Data Handling:** Pandas, Python
- **Web Scraping:** BeautifulSoup
- **Geospatial Analysis:** GeoPy

## Results
There is a clear trend of housing prices to start escaping income.
![Output Image](plots/juil/affordability_vs_price.png)

## How to Use

Clone the repository and navigate to the project directory:
```bash
git clone https://github.com/ft-p1team05/canhomeowner.git
cd fintech-project01
```

Run Jupyter Notebook to access the full analysis:
```bash
jupyter notebook
```

## Data Resources

Utilized data from CREA, Bank of Canada, Statistics Canada, CMHC, and Ontario's public data.
* [CREA - The Canadian Real Estate Association](https://stats.crea.ca/en-CA/)
  * [Seasonally Adjusted Home Price Index and Benchmark](Resources/Seasonally_Adjusted.xlsx)
* [Bank of Canada](https://www.bankofcanada.ca/rates/)
  * [Interest Rates](https://www.bankofcanada.ca/rates/interest-rates/canadian-interest-rates/)
  * [Inflation](https://www.bankofcanada.ca/rates/indicators/capacity-and-inflation-pressures/inflation/)
* [Statistics Canada](https://www.statcan.gc.ca/en/start)
  * [Immigration](https://www12.statcan.gc.ca/census-recensement/2021/as-sa/fogs-spg/page.cfm?topic=9&lang=E&dguid=2021A000011124)
* [CMHC - Canada Mortgage and Housing Corporation](https://www.cmhc-schl.gc.ca/en/professionals/housing-markets-data-and-research)
  * [Rental Market Data](https://www.cmhc-schl.gc.ca/en/professionals/housing-markets-data-and-research/housing-data/data-tables/rental-market)
  * [Mortgage Data](https://www.cmhc-schl.gc.ca/en/professionals/housing-markets-data-and-research/housing-data/residential-mortgage-industry-data-dashboard)
* [data.ontario.ca](https://data.ontario.ca/) 
  * [Ontario Public School Enrollment](https://data.ontario.ca/dataset/ontario-public-schools-enrolment)

## Challenges

Overcame challenges in data acquisition, team collaboration, and complex data visualization to provide actionable insights.

## Contributions

As a collaborative project, contributions ranged from data collection, analysis, machine learning model implementation to visualization and report generation.

## Project Presentation

Explore our detailed findings and visualizations here: [Presentation Slides](https://docs.google.com/presentation/d/e/2PACX-1vQpqhoqND5ZDTo_8uhrVo5SECL_wze3Q7KL7XBq3krg9yFWrBj1Em7eT8ax1O9k5Radiz0f1VdGi9rI/pub?start=false&loop=false&delayms=3000)

## Repository Link

[GitHub Repository](https://github.com/mohjaiswal/canhomeowner))

### Plots and Graphs
![Heatmap](plots/kei/heatmap.png)

![GeoPlot](plots/kei/home_price-geoplot.png)

![Line Graph](plots/moh/mortgage_vs_rent.png)

Average Mortgage Monthly Payments (pct_change) and  Gross Rent (pct_change)

![Percentage Change](plots/moh/mortgage_vs_rent-percentchange.png)

![Interest Rates](plots/romain/interest_rates.png)

The calculator estimates your living expenses.

![Mortgage Calculator](plots/romain/calculator.png)

![Home Prices vs Affordability based on Income](plots/juil/affordability_vs_price.png)
