# Predicting Ratemyprofessor Ratings Using Regression Techniques

Welcome to my first data science project! 

After learning how to scrape data and build linear regression models, I decided to hone my newly acquired skills by building a predictive model centered around the data that I could scrape from ratemyprofessors.com. The goal of this project was to use linear regression and regularization to tune a model that would accurately predict a professor's average rating on the site. To do this, I used 21 features also scraped from the site. 

Quick takeaways from this project would be that one, my target variable Overall Professor Rating, ended up having a bimodal distribution making it somewhat of a challenge to get the best out of linear regression for this project. Two, regularization didn't improve my LASSO, Ridge, or Elastic Net models much, so I'd recommend running a simple OLS model for best accuracy or LASSO with and alpha = 0.1 for a slight loss in r-squared but dropping over 13 predictor variables. 

Final r-squared values for all models came to be ~0.4808.

Repo Files:

* RMP_Ratings_Presentation.pdf – My presentation of the project
* RMP_Ratings_Writeup.doc – Quick one page summary of my methodology
* Pt1_Selenium_URL_Gathering.ipynb – How I gathered professor URL's from ratemyprofessors
* Pt2_Beautiful_Soup_Parsing.ipynb – How I parsed each URL for my feature set
* Pt3_Regression_Modeling.ipynb – Where I built out and tested all of my models
* data – All of the data I scraped from ratemyprofessors



## Built With

* Python3
* Pandas
* Beautiful Soup
* Selenium – using Firefox webdriver
* Matplotlib & Seaborn
* Sklearn
* Statsmodels



## Author

Edward Leardi

* http://edwardleardi.com/
* https://github.com/edleardi
* https://medium.com/@edleardi_17288



## Acknowledgments

* Metis – Special shout outs to Joe Eddy and Debbie Berebichez
* Ratemyprofessors for not suing me! (I promise I'm not using this data for personal financial gain)

