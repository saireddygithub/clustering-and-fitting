# clustering-and-fitting
# Happiness Analysis 2019

This repository contains a Python-based analysis of the 2019 World Happiness Report dataset. The code explores various aspects of the dataset using visualization, regression analysis, clustering, and correlation heatmap.

## Features

1. **Bar Chart Visualization**:
   - Displays the top 10 happiest countries in 2019 using a bar chart.

2. **Scatter Plot with Regression Line**:
   - Examines the relationship between GDP per capita and happiness scores.
   - Fits a linear regression model and displays the regression line.

3. **K-means Clustering and Elbow Plot**:
   - Uses K-means clustering to analyze patterns in the data.
   - Includes an elbow method plot to determine the optimal number of clusters.

4. **Correlation Heatmap**:
   - Visualizes the correlation between different variables in the dataset using a heatmap.

## Installation

### Prerequisites

- Python 3.7 or above
- Required Python packages:
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn
  - numpy

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/happiness-analysis-2019.git
   cd happiness-analysis-2019
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Place the `2019.csv` dataset in the root directory of the project.

## Usage

Run the script to execute all steps of the analysis:
```bash
python happiness_analysis.py
```

### Code Description

- **Data Preprocessing**:
  Selects relevant columns for analysis, including `Score`, `GDP per capita`, `Social support`, `Healthy life expectancy`, and others.

- **Bar Chart Visualization**:
  ```python
  plot_bar_chart()
  ```
  Displays a bar chart of the top 10 happiest countries.

- **Scatter Plot with Regression Line**:
  ```python
  plot_scatter_with_fit()
  ```
  Plots GDP per capita vs. happiness score with a fitted regression line. Outputs regression coefficients, intercept, and mean squared error.

- **K-means Clustering and Elbow Plot**:
  ```python
  plot_elbow_method(relevant_data)
  ```
  Performs clustering and plots the elbow curve to identify the optimal number of clusters.

- **Correlation Heatmap**:
  ```python
  plot_correlation_heatmap()
  ```
  Displays a heatmap of correlations between variables.

## Dataset

The dataset used in this project is the 2019 World Happiness Report. Ensure the file `2019.csv` is present in the project directory. Columns include:
- `Country or region`
- `Score`
- `GDP per capita`
- `Social support`
- `Healthy life expectancy`
- `Freedom to make life choices`
- `Generosity`
- `Perceptions of corruption`

## Results

1. **Top 10 Happiest Countries**: Visualized as a bar chart.
2. **Regression Analysis**: Highlights the influence of GDP per capita on happiness.
3. **Clustering**: Groups countries based on happiness-related metrics.
4. **Heatmap**: Shows relationships among different variables.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.

---

### Notes
- Replace `your-username` and `your-email@example.com` with your GitHub username and email address, respectively.
- Include the dataset `2019.csv` in the repository for others to replicate your results.

