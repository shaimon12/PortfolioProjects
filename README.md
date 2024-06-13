# UEFA Champions League 2021-2022 Player Analysis

## Project Overview

This project provides an extensive analysis of player performance data from the UEFA Champions League 2021-2022 season. Utilizing various datasets, this analysis focuses on predicting player goal-scoring potential, categorizing player performances, and identifying key players using different machine learning models including Linear Regression, Logistic Regression, and K-Nearest Neighbors (KNN).

![MV5BNTViYjI5M2MtNDYzZS00MDZkLTkzOWItMzkyM2FmMDhhZjc4XkEyXkFqcGdeQXVyNDg4MjkzNDk@ _V1_](https://github.com/shaimon12/PortfolioProjects/assets/160793918/86067a58-37e6-4143-938d-601592a72a1a)

## Dataset Description

The analysis is based on multiple datasets from Kaggle (https://www.kaggle.com/datasets/azminetoushikwasi/ucl-202122-uefa-champions-league/data), with a primary focus on the `key_stats.csv` file, which includes the following columns:
- **player_name**: Name of the player
- **club**: Club of the player
- **position**: Playing position (e.g., Forward, Midfielder)
- **minutes_played**: Total minutes played by the player
- **match_played**: Number of matches played
- **goals**: Total goals scored
- **assists**: Total assists made
- **distance_covered**: Total distance covered by the player in kilometers

## Analysis Objectives

1. **Data Preparation**: Load and clean the data, handling missing values and incorrect data types.
2. **Exploratory Data Analysis**: Investigate the distribution of data, and relationships between variables, and perform outlier detection.
3. **Model Development**:
   - **Linear Regression**: Predict the number of goals based on other performance metrics.
   - **Logistic Regression**: Classify players based on whether they score above or below the median number of goals.
   - **K-Nearest Neighbors**: Classify players into performance categories and optimize the model using hyperparameter tuning.

## How to Run

### Step 1: Clone the repository:
   ```bash
   git clone https://github.com/shaimon12/PortfolioProjects
cd PortfolioProjects
```
### Step 2: Install Anaconda

Download and install Anaconda from the [official Anaconda website](https://www.anaconda.com/products/individual), following the installation instructions for your operating system.

### Step 2: Launch Anaconda Navigator

Open Anaconda Navigator, which comes installed with the Anaconda suite.

### Step 3: Launch Jupyter Notebook

Within Anaconda Navigator:
1. Locate the Jupyter Notebook app and click "Launch".
2. Jupyter Notebook will open in your web browser.
3. Navigate to the directory where your project files are located.

### Step 4: Run the Notebook

1. Open the `uefa_champions_league_analysis.ipynb` file in Jupyter Notebook to access and run the project analysis.

## Notes on Packages

Anaconda includes a comprehensive suite of scientific packages sufficient for most data analysis tasks. If you need additional packages:
1. Open a terminal from Anaconda Navigator.
2. Install the packages using Conda, e.g., `conda install package-name`.

## Results

The project successfully developed two predictive models:
1. **Linear Regression** Model demonstrated strong predictive power with an R-squared of 82.89%.
2. **Logistic Regression** Model showed robust performance with over 92% accuracy in classifying players' goal-scoring above or below the median.
3. **KNN** Model effectively categorized players with an optimized K-value showing peak accuracy, confirming the model's generalizability and effectiveness.

## Contributing

Contributions are welcome! Please fork the repository, create a feature branch, make changes, and submit a pull request.

## License

This project is released under the MIT License. See the [LICENSE](LICENSE.md) file for details.

## Contact

For any queries, please reach out to shaimon.rahman.au@gmail.com.

## Acknowledgments

- Thanks to all contributors and data providers involved in this project.


