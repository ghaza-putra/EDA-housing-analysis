# EDA-housing-analysis
## Background Problem
A property company aims to analyze the factors that influence house sale prices. The dataset includes categorical variables such as Utilities, HouseStyle, and ExterQual, as well as numerical variables like SalePrice, GrLivArea, and PoolArea. This project seeks to understand the relationships between these variables and the house prices through Exploratory Data Analysis (EDA), involving data type separation, data cleaning, and 1D and 2D visualizations.

## Version Libraries
- Pandas version: 2.2.2
- Numpy version: 2.0.2
- Seaborn version: 0.13.2
- Matplotlib version: 3.10.0

## Insight
**1D Visualization Insights**
1. Utilities: Most houses have full access to public utilities (AllPub).
2. HouseStyle: The most dominant house type is 1Story, indicating a market preference for single-story homes.
3. ExterQual: The exterior quality is generally Typical/Average (TA) and Good (Gd).
4. SalePrice: House prices are right-skewed, with most homes priced below $200,000.
5. GrLivArea: The living area is generally between 1,000–2,000 sqft, with some homes being very large.
6. GarageArea: The distribution of garage area is nearly normal, with most homes having garages between 400–600 sqft.
7. Log-10 Transformation: Successfully normalized the distribution of the variables SalePrice, GrLivArea, and GarageArea.

**2D Visualization Insights**
1. GrLivArea vs SalePrice: Strong positive relationship; larger homes tend to be more expensive.
2. GarageArea vs SalePrice: Positive relationship, although more scattered and not as strong as GrLivArea.

## Advice
Based on the EDA analysis, for the house price prediction model, it is recommended to focus on GrLivArea as the main feature because it shows the strongest correlation with house prices (SalePrice). While GarageArea also has a positive correlation with price, its impact is weaker, making it less effective than GrLivArea in predictive modeling. Additionally, considering exterior quality (ExterQual) and house style (HouseStyle) could improve the model's accuracy. Applying log-10 transformation to skewed variables like SalePrice and GrLivArea can help address distribution issues and enhance model performance by normalizing data with extreme values. To achieve better results, consider using regression or decision tree models that account for interactions between these variables.

#EDA #Python #HousingPriceAnalysis #DataScience Feel free to connect with me if you'd like to discuss anything,
ghazaputra99@gmail.com
