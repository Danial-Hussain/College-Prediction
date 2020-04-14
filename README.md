# College-Prediction Project- Overview
Many have tried, many have failed. Few trailblazers are ambitious enought to chase acceptance into the top 15 universites of the United States. Known for their grueling admissions process and heartbreaking decisions, the top 15 are at the pinnacle of every student's dream. 
In this project, we will be attempting to predict college acceptance for undergraduate students into top 15 national universities. The universities covered in this project will be strictly colleges from the United States.

**Top 15 universites**

In order to determine the top 15 universities in the United States, we will use the 2020 rankings published by U.S News.
1. Princeton University----------------------------6. Stanford University-------------------------11. Johns Hopkins University
2. Harvard University------------------------------7. University of Chicago-----------------12. California Institute of Technology
3. Columbia University-----------------------------8. University of Pennsylvania------------------13. Dartmouth College 
4. Massachusetts Institute of Technology-----------9. Northwestern University---------------------14. Brown University 
5. Yale University---------------------------------10. Duke University----------------------------15. University of Notre Dame

## Project Outline
1. [Web Scraper](web_scraper.py)-Programmed web scraper to gather data. Used python along with the beautifulsoup and requests modules
2. [Machine Learning](College_Prediction_Model.ipynb)- Created a jupyter notebook where I performed data cleaning, feature engineering, and machine learning to create a classifier model that predicts college acceptance. Utilized pandas, numpy, sklearn and xgboost.
3. [Deployment](app.py)- Created a web application, with the classifier model, using flask. Created a graphical user interface using CSS and HTML. 

## Running the Project
1. Prerequisites: You must have the following libraries installed- pandas, numpy, sklearn, seaborn, re, xgboost, and flask.
2. Navigate to the project home directory and run the following command: `python app.py`
3. Flask will run on port 5000 and the http link will appear in the terminal.
![Image of Screen](https://github.com/Danial-Hussain/College-Prediction/blob/master/Images/Capture.PNG)
