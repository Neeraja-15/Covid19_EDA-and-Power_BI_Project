# COVID-19 EDA and Power BI Visualization
Welcome to the COVID-19 EDA and Power BI Visualization project! This repository contains an exploratory data analysis (EDA) conducted in Jupyter Notebook and an interactive dashboard built in Power BI, based on COVID-19 data from the Ministry of Health. The project cleans, analyzes, and visualizes the data to uncover trends and insights about the pandemic’s spread and impact.
## Project Overview
### Goal
To process and analyze COVID-19 data, delivering statistical insights and an interactive dashboard for tracking cases, deaths, and geographic patterns.
### Technologies
- **Jupyter Notebook**: Python-based EDA using `pandas`, `seaborn`, and `matplotlib`.
- **Power BI**: Interactive dashboard for data visualization.
### Dataset
- **Source**: Ministry of Health
- **Fields**:
  - `Date_reported`: Date of record
  - `Country_Code`: ISO country code (e.g., "US")
  - `Country`: Country name
  - `WHO_region`: WHO region (e.g., "AMRO")
  - `New_cases`: Daily new cases (18,729 missing initially)
  - `Cumulative_cases`: Total cases to date
  - `New_deaths`: Daily new deaths (30,306 missing initially)
  - `Cumulative_deaths`: Total deaths to date
- **Files**:
  - `covid_data.csv`: Raw input data
  - `cleaned_covid_data.csv`: Processed data for Power BI
## Getting Started
### Prerequisites
- **Python 3.x**: Install from [Python.org](https://www.python.org/) or Anaconda.
- **Jupyter Notebook**: Install via `pip install notebook` or Anaconda Navigator.
- **Power BI Desktop**: Download from [Microsoft](https://powerbi.microsoft.com/en-us/desktop/).
- **Python Libraries**: `pandas`, `seaborn`, `matplotlib`.
### Installation
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/[YourUsername]/COVID-19-EDA-PowerBI.git
   cd COVID-19-EDA-PowerBI
