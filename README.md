# Box Office Analysis

## Overview

This project focuses on analyzing box office performance based on several variables such as the number of tickets sold, the number of screens, and daily box office revenue. Using Excel, scatter plots and correlation analysis are employed to discover the relationships between these variables.

## Project Objectives

- Analyze the daily box office data and its relationship with key variables like ticket price and the number of screens.
- Use scatter plots to visualize potential trends and patterns in the data.
- Perform correlation analysis to quantify the relationship between box office revenue and other variables.

## Key Features

- **Scatter Plot Visualization**: Visualize relationships between variables such as tickets sold, screens, and daily box office revenue.
- **Correlation Analysis**: Calculate correlation coefficients to measure the strength and direction of relationships between variables.
- **Data-Driven Insights**: Use visualizations and correlation coefficients to drive decisions and predictions for future box office trends.

## Tools Used

- **Microsoft Excel**: Primary tool for data analysis, visualization, and correlation analysis.
- **Excel Functions**:
  - `CORREL()`: Used for calculating correlation coefficients between key variables.
  - `INSERT CHART`: Used to create scatter plot visualizations of the data.

## Data Overview

The dataset contains information on daily box office performance for a movie, including:

- **movieID**: Unique identifier for the movie.
- **date**: Date of the box office record.
- **box_office**: Box office revenue (in millions).
- **ticket**: Average ticket price (in USD).
- **screens**: Number of screens showing the movie on that day.

## Methodology

### 1. Data Cleaning
- The data was first inspected for any missing or incorrect values, which were removed or imputed.
- Standardized date formats were applied where necessary to ensure consistency.

### 2. Scatter Plot Analysis
- Scatter plots were created to explore relationships between the following key variables:
  - **Tickets vs. Box Office Revenue**
  - **Screens vs. Box Office Revenue**
  - **Ticket Price vs. Box Office Revenue**

### 3. Correlation Analysis
- Used the `CORREL()` function in Excel to calculate correlation coefficients between:
  - Number of screens and box office revenue.
  - Ticket price and box office revenue.
- The correlation coefficient provides insight into the strength of these relationships.

## Key Insights

- **Screens vs. Box Office Revenue**: 
  - Strong positive correlation suggests that more screens generally lead to higher box office revenue.
- **Ticket Price vs. Box Office Revenue**: 
  - Moderate correlation between ticket price and revenue indicates that while ticket prices affect revenue, the impact is less significant compared to the number of screens.

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/box-office-analysis.git
2. Open the Excel file located in the 'data/' folder.
3. Explore the scatter plots and correlation analysis in the relevant tabs to gain insights.

#Future Enhancements
- Time Series Analysis: Analyze how box office performance changes over time.
- Predictive Modeling: Build a predictive model using multiple variables to estimate future box office performance.

# Contributing
Contributions are welcome! Follow these steps to contribute:
1. Fork the repository.
2. Create your feature branch (git checkout -b feature/AmazingFeature).
3. Commit your changes (git commit -m 'Add some AmazingFeature').
4. Push to the branch (git push origin feature/AmazingFeature).
5. Open a pull request.

# Contact
- Chetan Kumar Suppala - https://www.linkedin.com/in/chetankumarsuppala/
- Projecct Repository - https://github.com/ChetanKumar421/BoxOfficeAnalysis/
