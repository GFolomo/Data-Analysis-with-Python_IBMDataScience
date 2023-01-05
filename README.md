PROJECT SCENARIO
*****************
In this assignment, you are a Data Analyst working at a Real Estate Investment Trust. The Trust would like to start investing in Residential real estate. You are tasked with determining the market price of a house given a set of features. You will analyze and predict housing prices using attributes or features such as square footage, number of bedrooms, number of floors, and so on. A template notebook is provided in the lab; your job is to complete the ten questions. Some hints to the questions are given in the template notebook.

The dataset contains house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015. 

The dataset was taken from: 
https://www.kaggle.com/datasets/harlfoxem/housesalesprediction?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-wwwcourseraorg-SkillsNetworkCoursesIBMDeveloperSkillsNetworkDA0101ENSkillsNetwork20235326-2022-01-01 and modified for the purpose of the project and course.

THE FOLLOWING QUESTIONS WERE ANSWERED
**************************************
Question 1) Display the data types of each column using the attribute dtypes, then take a screenshot and submit it, include your code in the image.

Question 2) Drop the columns "id" and "Unnamed: 0" from axis 1 using the method drop(), then use the method describe() to obtain a statistical summary of the data. Take a screenshot and submit it, make sure the inplace parameter is set to True. Your output should look like this:

Question 3) use the method value_counts to count the number of houses with unique floor values, use the method .to_frame() to convert it to a dataframe. Your output should look like this :

Question 4) use the function boxplot in the seaborn library to produce a plot that can be used to determine whether houses with a waterfront view or without a waterfront view have more price outliers. Your output should look like this with the code that produced it (the colors may be different ) :

Question 5) Use the function regplot in the seaborn library to determine if the feature sqft_above is negatively or positively correlated with price. Take a screenshot of the plot and the code used to generate it.

Question 6) Fit a linear regression model to predict the price using the feature 'sqft_living' then calculate the R^2. Take a screenshot of your code and the value of the R^2. 

Question 7) Fit a linear regression model to predict the 'price' using the list of features:
"floors" "waterfront" "lat" "bedrooms" "sqft_basement" "view" "bathrooms" "sqft_living15" "sqft_above" "grade" "sqft_living"
The calculate the R^2. Take a screenshot of your code and the value of the R^2. 

See uploaded answers as well as the notebook with codes.

