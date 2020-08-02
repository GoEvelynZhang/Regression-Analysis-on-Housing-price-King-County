# Regression-Analysis-on-Housing-price-King-County-Spring-2018-econometrics-
Econometrics project &amp; presentation
### refer to pdf for compelete report and presentation for logistic demonstration

### Introduction
In real estate business, house pricing constitutes an essential part and stirs the dynamics among buyers, sellers and brokers. Key attributes such as square footage of the living space, year when the house was built, the overall house condition are widely acknowledged by the market. However, how house price per square foot adjusts in sync with the increase in square footage across groups with different income levels remains a puzzle to us.

This paper uses data from “House Sales in King County, USA” and endeavors to investigate the question of our interest. Commonly applied Hedonic regression is incorporated as the theoretical foundation of preliminary model specification. The pricing model is constructed by house characteristics of 1) sqft_living15 2) bedrooms 3) bathrooms 4) sqft_lot15 5) floors 6) waterfront 7) sqft_above 8) sqft_renoliving 9) time_sold 10) time_renovated 11) up 12) middle 13) up_sqft_living 14) mid_sqft_living 15) grade.

Methodology of this research paper covers data processing, model specification and diagnostics, multivariable regression, hypothesis testing.

### Research Question
Linking people’s different income levels to the per unit housing price, it’s natural to presume that people from higher classes are more willing to pay for bigger houses.

Based on this presumption, our research question narrows down to the point of answering: when the square footage of total house living space increases by unit, does the unit price of house per square foot change more in upper class regions than that in middle and lower class regions?

By delving into this question, we hope to shed light on the demand and supply relationship of houses for people from different income classes. The point being, we would like to seek for certain logics behind the market dynamic for regular homebuyers to reference. Real estate market involves various dynamics and is oftentimes found to be information asymmetric for outsider buyers. Albeit they may bargain with sellers or brokers, regular buyers tend to be put in a passive situation and end up price-takers. Meanwhile, for real estate developers, this question may also contribute to understand the profit margin from square footage of houses. In this sense, they can align different sizes of houses with their target clients from specific income class.

### Research logistics
1. Variables selection and Basic Descriptive Statistics
2. Inferential analysis

* Model Specification (prelimitary model with omitted variable test)
* Model Specification (prelimitary model with Ramsey Test to explore quadratic form)
* Model Specification (discussion on transformation of functional form)

3. Regression diagnostic
* Check on exogeneity of the model and normal distribution of
residual [MLR4 & MLR6]
* Check on homoscedasticity [MLR5]

4. Regression validation
* Goodness of fit
* Further justification for the efficiency of robust OLS estimators

5. Discussion on the regression Result
* direct inference from the regression result about difference in between the lower and upper lower and middle class
* Interpretation of regression result
Econometric methodology and careful thoughts have been put into the enquiry of our research question. The above discourse centers around the question of our interest and is structured in an efficient manner to approach the answers.

Based on preceding regression result and subsequent hypothesis testing, we therefore conclude our findings are:

1. Living square of the house has more contributions to the per square foot housing price on average in middle and upper class than in lower class. From the buyers’ market, this indicates that there are more demand for larger houses in the middle and upper class. From the constructors’ side, this indicates profitability of building bigger houses in the middle and upper class regions, and smaller houses in the lower class regions.
2. However, the increase in square footage of living space does not result in significantly different increase of per square foot housing price in between the middle and upper class. From the buyers’ perspective, this indicates more or less similar willingness of middle class and upper class in buying comparatively bigger houses. From the constructors’ side, it might be equally profitable to develop big houses in both middle and upper class.
3. General difference (the coefficient of variables up & middle, which measures the difference in per square foot housing price when living square is zero) in housing price per square foot suggests that for upper class, they are more willing to pay higher (31.50239) for unit price than lower class. However, the middle class are less willing to pay for unit price than lower class by 15.62638.

* Insights into real estate market - real world implications

While the scope of this empirical study is relatively confined within King County level, we do hope to cast light upon some real world implications from this research and better understand the real estate market mechanism.

Based on our regression results, custructors should follow the rule to build more large houses catered for upper class and middle class while build smaller houses for lower class. This decision will influence the layout of houses and communities along with other factors before construction. When evaluating construction plans, real estate developers should take all these elements into consideration to maximize the profit from a given land.

