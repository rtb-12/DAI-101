# Exploratory Data Analysis (EDA) on Japan vs. China Technology Dataset

## Dataset
The Kaggle Dataset reffered for this project : [China Vs Japan EDA](https://www.kaggle.com/code/waqi786/china-vs-japan-eda/notebook)

## Overview

This project performs an Exploratory Data Analysis (EDA) on a dataset comparing the technological metrics of Japan and China. The dataset includes various key metrics such as:

- **R&D Investment (in USD)**
- **Venture Capital Funding (in USD)**
- **Tech Exports (in USD)**
- **Internet Penetration (%)**
- **5G Network Coverage (%)**
- **Number of Startups**
- **Market Share (%)**

## Objectives

The goal of this EDA is to:

1. **Univariate Analysis**: Analyze each variable individually to understand its distribution and key characteristics for each country.
2. **Multivariate Analysis**: Investigate relationships between multiple variables to understand trends, correlations, and patterns that highlight the technological advancements and investments in Japan and China.

## Analysis Performed

### 1. Univariate Analysis

- **Box Plots** were created to compare key metrics between Japan and China:

  - **R&D Investment**
  - **Internet Penetration**
  - **5G Network Coverage**

  **Findings**:

  - China tends to have higher R&D investment and greater 5G network coverage, while Japan shows more consistent internet penetration across years.

### 2. Multivariate Analysis

- **Correlation Matrix**: A correlation heatmap was generated to explore the relationships between key numerical variables such as R&D investment, number of patents filed, and global innovation ranking.

  **Findings**:

  - Strong positive correlation between **R&D Investment** and **Number of Patents Filed**.
  - Venture capital funding is moderately related to the number of startups.

- **Scatter Plots**:

  - **Market Share (%) vs. R&D Investment**: This scatter plot shows the relationship between market share in the tech sector and the amount of R&D investment for each country.
  - **Internet Penetration (%) vs. 5G Network Coverage (%)**: This visualizes how internet penetration aligns with 5G coverage.

  **Findings**:

  - Countries with higher market share tend to have greater R&D investment.
  - China exhibits higher 5G coverage compared to Japan, but internet penetration shows less variance across both countries.

- **Bar Plot**:
  - **Venture Capital Funding (in USD) by Country and Year**: This shows the trend of venture capital investment over the years in both countries.
  **Findings**:
  - China has seen a sharper increase in venture capital funding in recent years, compared to a more stable trend in Japan.

## Conclusion

The EDA reveals several key trends in the technological sector of Japan and China:

- China is making significant strides in technological infrastructure, with greater investment in 5G and R&D.
- Japan remains consistent in areas like internet penetration, but China is outpacing Japan in terms of funding and market share growth.
- There is a strong relationship between R&D investment and innovation, as seen by the correlation with the number of patents filed.

Overall, the analysis highlights the competitive technological landscape between the two countries, with China showing a more aggressive growth trajectory in recent years.

## Dependencies

The following libraries are required to run the analysis:

- `pandas`
- `seaborn`
- `matplotlib`
- `numpy`
