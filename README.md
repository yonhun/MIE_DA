# MIE_DA(Data Analysis Project)
University of Seoul 2024/1 Data_Analysis Final Project

This repository contains the final project files for a data analysis course. The project explores two main datasets:

1. **Car Fuel Efficiency Analysis (MPG dataset)**
2. **NBA Player Statistics Clustering (2023/2024 Season)**

## Project Structure

- **mpg.csv**: Contains the car fuel efficiency data (MPG dataset).
- **2324.csv**: Contains the NBA player statistics for the 2023/2024 season.
- **Part1.ipynb**: Data analysis on the car fuel efficiency dataset.
- **Part2.ipynb**: Clustering analysis on the NBA player statistics.
- **DA_기말과제_2019430003_고영훈.pdf**: The final project report summarizing the analyses performed.

## Analysis 1: Car Fuel Efficiency (MPG Dataset)

The first part of the project uses the `mpg` dataset to explore how different car attributes (like engine displacement, number of cylinders, and drivetrain) influence city and highway fuel efficiency.

### Steps Included:
1. Data cleaning and preprocessing
2. Exploratory Data Analysis (EDA)
    - Categorical data frequency analysis
    - Distribution of numerical variables
    - Correlation analysis using scatterplots and heatmaps
3. Regression analysis to determine key factors affecting fuel efficiency

### Key Results:
- Engine displacement and the number of cylinders are negatively correlated with fuel efficiency.
- Cars with front-wheel drive generally have better fuel efficiency than all-wheel-drive cars.

## Analysis 2: NBA Player Statistics Clustering (2023/2024 Season)

The second part focuses on NBA player statistics for the 2023/2024 season. The analysis aims to classify players based on their performance metrics (e.g., points, rebounds, assists, etc.) using k-means clustering.

### Steps Included:
1. Data cleaning and normalization
2. Exploratory analysis of player stats (e.g., average points, rebounds, and shooting percentages)
3. K-means clustering to group players into performance-based clusters
4. Comparison of cluster results to player positions (PG, SG, SF, PF, C)

### Key Results:
- Players tend to cluster based on playing time rather than position, indicating that playing time is a dominant factor in stat accumulation.
- Attempts to cluster based on shooting success (e.g., field goal percentage) revealed meaningful groups after data normalization.

## How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/yourrepository.git

2. Install the required Python packages:

   ```bash
   pip install -r requirements.txt

3. Run the Jupyter notebooks:

   Open the `.ipynb` files in your Jupyter environment to explore the analysis and results.

## Project Files

| File Name                          | Description                                  |
| ---------------------------------- | -------------------------------------------- |
| `mpg.csv`                          | Car fuel efficiency data                     |
| `2324.csv`                         | NBA player stats for 2023/2024               |
| `Part1.ipynb`                      | Analysis of car fuel efficiency              |
| `Part2.ipynb`                      | Clustering analysis of NBA player stats      |
| `DA_기말과제_2019430003_고영훈.pdf` | Final project report                         |

## Conclusion

This project applies data analysis techniques, including exploratory data analysis (EDA), regression, and clustering, to uncover insights from real-world datasets. The results help identify key factors affecting fuel efficiency and group NBA players based on performance.
