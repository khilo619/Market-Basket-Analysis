# Market Basket Analysis with Shiny

## Project Overview
This project is a Shiny application for performing Market Basket Analysis using transaction data. It provides various visualizations and analytical tools to help understand customer purchasing patterns. The application is built using R and utilizes libraries such as `shiny`, `dplyr`, `ggplot2`, and `arules`.

## Features
- **Age vs. Total Spending**: A line plot comparing different age groups and their total spending.
- **Payment Method Analysis**: A pie chart showing the comparison between cash and credit transactions.
- **City-wise Spending**: A bar chart comparing total spending across different cities.
- **Spending Distribution**: A box plot representing the distribution of total spending.
- **Dashboard**: A combination of the above visualizations for a comprehensive overview.
- **K-Means Clustering**: Grouping customers based on spending patterns.
- **Association Rule Mining**: Discovering relationships between purchased items using the Apriori algorithm.

## Installation
To run this project, ensure that you have R and the following libraries installed:
```r
install.packages("shiny")
install.packages("dplyr")
install.packages("ggplot2")
install.packages("arules")
```

## Usage
1. Run the Shiny app by executing:
   ```r
   library(shiny)
   runApp("path_to_project")
   ```
2. Enter the file path for your transaction dataset (CSV format).
3. Adjust clustering and association rule mining parameters using sliders.
4. Navigate through different tabs to explore visualizations and analysis results.

## File Structure
- **ui**: Defines the user interface layout and appearance.
- **server**: Contains the logic for data processing and visualization.
- **plots**: Functions for generating different plots.
- **clean_data_KOL**: Function to clean and preprocess transaction data.

## Team 36
- Abdelrahmaen Ahmed Abdelmonem
- Ahmed Mohamed Abdullatif
- Adham Ibrahim Farouk
- Khaled Nabil Fathy
- Manar Mohamed Abdelkarim
- Lamia Araby AboZaid Ahmed

## Acknowledgments
Special thanks to all contributors and supporters of Team 36. "Impossible is not the title of Team 36’s story!" 🚀

