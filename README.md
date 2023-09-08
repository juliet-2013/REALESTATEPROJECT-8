# REALESTATEPROJECT-8
ENHANCING AMG REALTORS
DECISION- MAKING ON HOME
OWNERSHIP

Authors
 JULIET WANJA THUKU
 KELVIN MUIA
 SYLVESTER MAGUNDA
 STEPHEN KIMITI
Overview
This project uses multiple linear regression modeling to analyze house sales in a northwestern
county and generate insights for AMG REALTORS, a real estate agency that helps homeowners
buy and/or sell homes. Based on the King County House Sales dataset, recommendations are
made on what AMG REALTORS should consider when buying or selling houses. Generally, the
findings show that grade, square footage, bedrooms, bathrooms, and floors are the best predictors
of the prices of houses in King County.

Business and Data Understanding
In this project, we seek to transfigure how our stakeholder, AMG REALTORS, a real estate agency,
operates. This is by making it more agile, efficient, and customer-centered than ever before. The real
estate industry is no stranger to challenges. Market volatility, data overload, fierce competition, and
ever-evolving customer expectations are just a few of the hurdles agencies face. But every
challenge presents an opportunity, and that&#39;s precisely what we are here to capitalize on. The vision
is simple yet powerful. The vision is to empower AMG Realtors to excel in a digital age. We want to
equip them with the tools, strategies, and expertise needed to thrive in today&#39;s dynamic market. By
doing so, we aim to enhance the agency&#39;s ability to help homeowners buy and sell homes
seamlessly. This will be done through a holistic approach. We will dive into the core issues that the
agency faces. From market research, data security, and market expansion. This project will address
these challenges comprehensively. We are not just offering quick fixes but laying the foundation for
sustained success. The benefits are twofold. AMG Realtors will become a more competitive player in
the real estate industry, and more importantly, homeowners will experience a smoother, more
transparent, and more rewarding journey when trading homes. The approach to this is data-driven,
technology-enabled, and people-centralized. This team&#39;s commitment is to craft a holistic solution
that empowers AMG Realtors to offer impeccable service to its clients. This endeavor involves
refining business strategies and building a culture of continuous improvement among its dedicated
team of agents. In an industry that&#39;s ripe for innovation, this project represents an opportunity to not
only enhance the agency&#39;s bottom line but also make a significant positive impact on the lives of

homeowners. It&#39;s an opportunity to set new standards of excellence in the real estate market. We
can turn challenges into opportunities and dreams into reality. We are confident that by the end of
this project, AMG Realtors will emerge as a shining example of what is possible when vision,
strategy, and technology converge to create success.
This project is based on the King County House Sales dataset to understand the best way
for AMG REALTORS to advise homeowners when buying or selling houses. The data
used represent information on different movies using columns such as grade, square
footage, bedrooms, bathrooms, and floors, which are all critical in making informed decisions
on home ownership.
Modelling
This project uses multiple linear regression with both numerical variables and non-numerical
variables. Dummy variables are created using one-hot encoding to make the most productive
model which shows that grade, square footage, bedrooms, bathrooms, and floors are the best
predictors of the prices of houses in King County.
Regression Results
Model 3 with the combination of sqft_living, bedrooms, bathrooms, floors, yr_built, and grade_int as
independent variables has the highest R-squared and adjusted R-squared values, indicating that it
best fits the data among the three models. Model 2 is the second-best, and Model 1 is the least
effective in explaining the variance in the price.
Conclusions
We encourage our stakeholder, AMG Realtors to consider these factors when listing or purchasing
homes
1 Size and layout First from our analysis the importance of square footage and the number of
bathrooms have been highly focused on. Clearly, larger living spaces and more bathrooms tend to
increase house prices. We also encourage homeowners to consider renovations or upgrades that
can increase the square footage or improve the number of bathrooms in their properties. These
improvements can potentially lead to higher resale values.
2 Age of property. Older properties tend to have lower prices. When marketing older homes, we
strongly advice our client to focus on the properties unique characteristics, history, and any
renovations that have been done to enhance their value.
3 Combined, grade, square footage, bedrooms, and bathrooms are best predictors of the prices of
the houses in King County. The grade_int feature was a categorical variable feature engineered to fit
our model. The feature significantly improved the predictive power of our model for the house prices
at this county
