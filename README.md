<img src="https://media.licdn.com/dms/image/C4E12AQHcwl6rswFXkw/article-cover_image-shrink_600_2000/0/1600461296436?e=2147483647&v=beta&t=rheNneNwqloxmEfmSc2W-3fxS5AOokt0BbRYN0oHr4w" width="500" />

# Predict Federal Election by MRP Model

# Project Overview
This project explores how increased voter turnout might have impacted the 2019 Canadian Federal Election. Using a Multilevel Regression with Poststratification (MRP) model, we predict the election outcome based on factors such as age, sex, education, marital status, and province. The goal is to determine whether higher voter participation would have altered the result, specifically if it could have led to a Conservative Party victory over the Liberal Party. The findings suggest a close race, with the Liberal Party likely maintaining a slight edge. This analysis underscores the significance of demographic factors in electoral outcomes.

# Data
The census_data.csv is used.

## Source Data
The survey data used is from the 2019 online survey of Canadian Election study, and can be loaded with get_ces("ces2019_web").
The census data is from the Canadian general social surveys (GSS) which is provided by CHASS, and it's cleaned using gss_cleaning.R which outputs the census_data.csv used in the markdown.

# Results and evaluation
Provide an overview of the results of your project, including any relevant metrics and graphs. Include explanations of any evaluation methodologies and how they were used to assess the quality of the model. You can also make it appealing by including any pictures of your analysis or visualizations.

# License
For this github repository, the License used is [MIT License](https://opensource.org/license/mit/).
