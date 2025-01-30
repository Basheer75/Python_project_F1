Overview:

The main goal of this project is to provide insights into the historical performance of drivers and constructors in the Formula 1 World Championship. The project includes data visualizations, statistical analysis, and exploration of trends in race results, pit stops, qualifying performances, and more.

Data Sources
The data used in this project is sourced from Kaggle’s Formula 1 dataset, which includes the following key files:

circuits.csv: Information about race circuits.

cons_result.csv: Constructor results in each race.

constructors.csv: Constructor information.

cons_standing.csv: Constructor standings for each season.

drivers.csv: Information about drivers.

driver_std.csv: Driver standings in each season.

lap_times.csv: Lap times for each race.

pit_stop.csv: Pit stop data.

qualifying.csv: Qualifying session results.

races.csv: Race details such as date, location, and race results.

results.csv: Race results for each driver.

seasons.csv: Data on the F1 seasons.

status.csv: Status of drivers in each race (e.g., finished, retired).

Key Features

Data Preprocessing:

Cleaning and merging data from various CSV files.
Handling missing values and optimizing memory usage.

Data Exploration:

Insights into the top drivers and constructors based on wins and points.
Analysis of race dominance by drivers and constructors.
Visualizations of key race data including pit stop times, qualifying performance, and driver/constructor performance.

Visualizations:

Interactive bar charts and scatter plots for drivers and constructors.
Heatmaps for correlations between pit stop times and race wins.
Scatter plots showing the relationship between average pit stop time and race wins.
Top 10 drivers by wins and points, with clickable driver profiles.

Pit Stop Analysis:

Comparing average pit stop times for different constructors.
Analyzing the impact of pit stop times on race results.

Installation

Clone the repository:

git clone (https://github.com/Basheer75/Python_project_F1)
cd formula-1-analysis
Install the required dependencies:

pip install -r requirements.txt
If you need to access the Kaggle dataset, make sure you have a Kaggle account and have set up Kaggle API credentials. You can then use the following to download the dataset:

kaggle.api.dataset_download_files('rohanrao/formula-1-world-championship-1950-2020', path='data/', unzip=True)
Run the Jupyter notebook (formula_1_analysis.ipynb) to start exploring the data and visualizations.

How to Use
The Jupyter notebook contains various sections where you can see the analysis of:

Driver Performance: Top drivers based on wins and points.
Constructor Performance: Top constructors based on total points and wins.
Pit Stop Analysis: Comparison of pit stop times and their relationship with wins.
Race Data Exploration: In-depth analysis of race results, including pit stops, driver positions, and race outcomes.
You can modify the existing code to analyze specific data points or create new visualizations.

Example Visualizations
Top 10 Drivers by Wins:

Interactive bar chart showing the top 10 drivers with the most wins.
Top 10 Constructors by Points:

Interactive bar chart displaying the top 10 constructors by total points.
Pit Stop Analysis:

Bar chart comparing the average pit stop times for constructors.
Scatter plot showing the correlation between pit stop time and wins.
