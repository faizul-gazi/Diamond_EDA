# Diamond Price Analysis Project

## Overview
This project explores a classic dataset containing information about nearly 54,000 diamonds, including their prices and various attributes. The analysis aims to understand the factors that influence diamond prices and uncover patterns in the diamond market.

## Dataset Description
The dataset includes the following attributes for each diamond:
- **price**: Price in US dollars ($326-$18,823)
- **carat**: Weight of the diamond (0.2-5.01)
- **cut**: Quality of the cut (Fair, Good, Very Good, Premium, Ideal)
- **color**: Diamond color, from J (worst) to D (best)
- **clarity**: A measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))
- **x**: Length in mm (0-10.74)
- **y**: Width in mm (0-58.9)
- **z**: Depth in mm (0-31.8)
- **depth**: Total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43-79)
- **table**: Width of top of diamond relative to widest point (43-95)

## Project Structure
- `Diamond-EDA.ipynb`: Main Jupyter notebook containing the analysis
- `README.md`: Project documentation
- `.gitignore`: Git ignore file

## Analysis Sections
1. **Variable Identification**: Understanding data types and structure
2. **Univariate Analysis**: 
   - Distribution analysis of continuous variables
   - Frequency analysis of categorical variables
3. **Bivariate Analysis**: Exploring relationships between variables
4. **Missing Value Analysis**: Checking data completeness
5. **Outlier Analysis**: Identifying and analyzing outliers
6. **Class Imbalance Analysis**: Examining distribution of categorical variables

## Key Findings
- Most diamonds in the dataset are of Ideal cut (21.5K)
- G color is the most common, while J is the least common
- SI1 and VS2 are the most frequent clarity grades
- Price distribution shows strong right skew
- No missing values in the dataset

## Technologies Used
- Python
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
 
  ![Screenshot_4](https://github.com/user-attachments/assets/25abec1c-6dbf-4161-87eb-d8ea9d6b0f99)

## Setup and Installation
1. Clone the repository
2. Install required packages: 
