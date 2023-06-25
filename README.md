# Movie Analysis on Box Office Data

**Authors**: 
## Overview

This project aims to analyze the box office data retrieved from various different databases. The ultimate goal of this project is to provide 3 actionable recommendations to our company's new movie studio on the type of future films to create.

## Business Situation

Evaluating the box office data on various movies is very important for the new movie studio to start planning for the first movie to film. Different factors such as most popular genre of the movie, production budget, and release date can greatly influence how well a film does in the market, and how much profit it makes. Therefore, analyzing the box office data prior to filming and releasing a new movie can help the new movie studio maximize revenue and plan for the future film. 

## Data Information

We retrieved box office data from two databases: [IMDB](https://www.imdb.com/) for basic information, and [The Numbers](https://www.the-numbers.com/) for the production budget and revenue. Please note that the IMDB database file needs to be **unzipped** prior running the jupyter notebook.

## Methods

Collectively, we want to apply some filters to focus on a subset of the dataset gathered for the purpose of this project. First, we decide to analyze from the movies that were **released between 2010 and 2018**, because there were only 3 months of the production budget data for 2019. The main categories of data that are relevant for our analyses are the **main genre**, **production budget**, **worldwide gross**, and **release date**. We additionally compute the overall **profit** and the **Return On Investment (ROI)** for each movie. For the main genre, we assign one genre per movie, and analyze across all genres. However, it is important to note that movies can be separated into multiple genres. Another limintation to our dataset is that movies released during last 4 years are not included.

To propose recommendation to our company's new movie studio, we complete the following exploratory data analyses (EDA):

1. Median profit, production budget, and ROI values per genre

2. Profit of top 4 popular genres across release months
[label](blob:vscode-webview%3A//06kjknb04qu853nb0qv5u4g5k7oit03akm7umt6oj0f1dqe0ekph/53e6bd35-1f56-43f7-bd48-11e6ef7507c6)

 Simple linear regression model is used to explore the relationship between the production budget and profit.

 [label](blob:vscode-webview%3A//06kjknb04qu853nb0qv5u4g5k7oit03akm7umt6oj0f1dqe0ekph/416fad80-9221-4217-ba3d-e6f84ec2fc20)

 ## Conclusions

 This project ultimately aims to provide recommendations to our company's new movie studio to consider when developing business strategies for future films.

 -**Animation, Adventure, and Action for a high budget film**, as they generate the most profit per movie. While these genres have the highest production budgets, they have the highest ROI as well.

 -**Comeday for a low budget film**, as comedy is the 4th in the ROI metric with lower median budget.

 -**Avoid summer releases.** As our movie studio is just getting started in the movie industry, we recommend avoiding the competition from the big movie studios in the summer.

 ## Appendix

 The appendix includes average metrics, simple linear regression models for each genre, and Analysis of Variance (ANOVA) for genre and profit.

 ## For More Information

 Please refer to the[Jupyter notebook](./Movie_Analysis.ipynb) contains more in-depth analyses, and the [presentation](./RSM-Productions_Launch.pdf).

 If you have any questions, please contact our team:

 Rajesh Reddy: [rredd002@gmail.com](mailto:rredd002@gmail.com)

 Sangyun (Yun) Thom: [sangyun.thom@gmail.com](mailto:sangyun.thom@gmail.com)

 Morgan Goode: [morgan.h.goode@gmail.com](mailto:morgan.h.goode@gmail.com)

 ## Repository Structure

├── .gitignore

├── zippedData

├── Movie Analysis.ipynb

├── RSM-Productions_Launch.pdf

├── README.md