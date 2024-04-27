# House-Sales-in-King-County-Analysis
---
### Authors: Minh Le, Hoa Nguyen, Yen Nguyen
## 1. Introduction

King County is the most populous county in Washington, known for its innovation and rich culture. It is a key component of the Seattle-Tacoma-Bellevue metropolitan area, a hub of both economic activity and cultural diversity. In this project, we will use the data set that shape the landscape of "house sale prices" in King County between May 2014 and May 2015 from Kaggle to understand how various factors impose impacts on property values in King County. Through statistical analyses and data visualization, we seek to gain insights that inform both the past and future of real estate in this county. 

## 2. Ethical Consideration

When working with this dataset, it is essential to prioritize privacy and confidentiality. Since it contains various details about homes, anonymizing data that could reveal individual identities is essential to protect privacy rights. Furthermore, it is crucial to ensure that data collection adheres to informed consent principles and legal regulations, respecting individuals' rights. To ensure fairness and objectivity, address biases in pricing and practices, and prioritize transparency through thorough documentation, all of which enhance ethical standards and contribute to the accuracy and significance of house price analysis.

## 3. Data Exploration

The data set includes homes sold between May 2014 and May 2015 in King County. The original dataset has 21 features of houses; however, we only use the following features about housing in this project:

- `price`: Price of each home sold

- `bedrooms`, `bathrooms`, `floors`: Number of bedrooms, bathrooms, floors, respectively.

- `sqft_living`, `sqft_lot`, `sqft_above`, `sqft_basement`: Square footage of interior living space, land space, floors, interior housing space that is above and below ground level, respectively.

- `waterfront`: A variable for whether the apartment was overlooking the waterfront or not.

- `view`: An index from 0 to 4 of how good the view of the property was.

- `condition`: An index from 1 to 5 on the condition of the apartment.

- `grade`: An index from 1 to 13 on the quality of construction and design.

- `zipcode`: Zip code area of the house.

## 4. Inference & Regression
For this part, we conduct hypothesis test and confidence interval between variables to see the correlation as well as the statistical significance of difference between different features of the house. We then conduct a regression model (Simple & Multiple Linear Regression and Logistic Regression) as well as Random Forest model to predict the price of the house based on the chosen features using stepwise selection methods. More results can be found [here](https://github.com/lqminhhh/House-Sales-in-King-County-Analysis/blob/main/Project%20Report.pdf).

## 5. Limitations & Conclusions

One notable limitation of this study is the reliance on a single dataset from King County within a specific time frame. While this dataset provides valuable insights into housing prices within the region, it may not capture the full spectrum of housing market dynamics in other geographical areas or over different time periods. Local factors, economic conditions, and market trends unique to King County may limit the generalizability of our findings to broader contexts. Therefore, caution should be exercised when applying the conclusions drawn from this study to other real estate markets with distinct characteristics. Future research could benefit from incorporating multiple datasets or extending the analysis to diverse geographic regions for a more comprehensive understanding of housing price determinants.

In conclusion, our analysis and test statistics of housing data in King County have yielded valuable insights into the determinants of house prices. Location, specifically zip codes, plays a pivotal role, with the 98039 area commanding the highest average housing price, followed closely by areas 98004, 98040, and 98112. Besides that, the presence of a waterfront view as well as the number of functioning rooms also impact prices. Moreover, our investigation revealed a positive correlation between house prices and interior living space, grade, and above-ground living area. These findings contribute to a nuanced understanding of the factors influencing housing prices in King County, providing valuable insights for both buyers and sellers in the markets of King County.

## 6. Reference
Harlfoxem. “House Sales in King County, USA.” Kaggle, August 25, 2016. https://www.kaggle.com/datasets/harlfoxem/housesalesprediction/data.  
