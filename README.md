# Springboard

Coursework, assignments, and case studies from the Springboard Data Science Career Track program.

## Repository Structure
Assignments/
Notebooks/
api_data_wrangling.ipynb Pulls historical weather data from the Open-Meteo API,
cleans it with pandas, and explores temperature/humidity/
precipitation trends for New York and LA.
meteorites.ipynb Automated exploratory data analysis on NASA's Meteorite
Landings dataset using ydata-profiling.

Case studies/
country club case study.ipynb SQL case study (Country Club database): querying member
and facility data, revenue analysis, and usage stats
with SQLite.
London Housing Case Study.ipynb Guided (filled-in) version of the London Housing case
study, analyzing which London boroughs saw the greatest
rise in housing prices over the last two decades.
London Housing Tier 3.ipynb Tier 3 (unguided) version of the same London Housing
challenge, worked independently from a blank skeleton.

Data/
country_club.sql Source data for the country club case study.
new_york_weather.csv Weather data used in api_data_wrangling.ipynb.
los_angeles_weather.csv Weather data used in api_data_wrangling.ipynb.


## Tech Stack

Python, pandas, NumPy, SQLite/SQL, requests, matplotlib, ydata-profiling, Jupyter Notebook

## Running the Notebooks

```bash
pip install pandas numpy requests matplotlib ydata-profiling jupyter
jupyter lab
```

The SQL case study connects to `Data/country_club.sql` via SQLite; the other notebooks pull data directly from their source APIs/files.
