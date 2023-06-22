# Applied Data Science Capstone
<p align="center">
  <img src="https://images.pexels.com/photos/2166/flight-sky-earth-space.jpg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" width="1200">
</p>

## 📄 Summary
This capstone project will ultimately **predict if the Space X Falcon 9 first stage will land successfully**. 

The full report can be found [here](https://github.com/Giflin/IBM-data-science-professional-certificate/blob/master/10.Applied%20Data%20Science%20Capstone/CAPSTONE%20PROJECT%20SpaceX.pdf).

### Context and Business Understanding
- SpaceX launches Falcon 9 rockets at a cost of around $62m. This is considerably cheaper than other providers (which usually cost upwards of $165m), and much of the savings are because SpaceX can land, and then re-use the first stage of the rocket. 

- If we can make predictions on whether the first stage will land, we can determine the cost of a launch, and use this information to assess whether or not an alternate company should bid against SpaceX for a rocket launch.

## 📑 Main Topics 
This project follows these steps:
1. [Data Collection](https://github.com/Giflin/IBM-data-science-professional-certificate/blob/master/10.Applied%20Data%20Science%20Capstone/data%20collection%20with%20web%20scraping%20(1).ipynb)
    - Making GET requests to the SpaceX REST API
    - Web Scraping
2. [Data Wrangling ](https://github.com/Giflin/IBM-data-science-professional-certificate/blob/master/10.Applied%20Data%20Science%20Capstone/data%20wrangling%20(2).ipynb)
    - Using the `.fillna()` method to remove NaN values
    - Using the `.value_counts()` method to determine the following:
        - Number of launches on each site
        - Number and occurrence of each orbit
        - Number and occurrence of mission outcome per orbit type
    - Creating a landing outcome label that shows the following:
        - 0 when the booster did not land successfully
        - 1 when the booster did land successfully
3. [Exploratory Data Analysis](https://github.com/Giflin/IBM-data-science-professional-certificate/blob/master/10.Applied%20Data%20Science%20Capstone/EDA%20WITH%20SQL%20(4).ipynb)
    - Using SQL queries to manipulate and evaluate the SpaceX dataset
    - Using Pandas and Matplotlib to visualize relationships between variables, and determine patterns
4. [Interactive Visual Analytics](https://github.com/Giflin/IBM-data-science-professional-certificate/blob/master/10.Applied%20Data%20Science%20Capstone/interactive%20visualiusation%20(1).ipynb)
    - Geospatial analytics using Folium
    - Creating an interactive dashboard using Plotly Dash
5. [Predictive Analysis (Classification)](https://github.com/Giflin/IBM-data-science-professional-certificate/blob/master/10.Applied%20Data%20Science%20Capstone/machine%20learning%20prediction%20(1).ipynb))
    - Using Scikit-Learn to:
        - Pre-process (standardize) the data
        - Split the data into training and testing data using train_test_split
        - Train different classification models
        - Find hyperparameters using GridSearchCV
    - Plotting confusion matrices for each classification model
    - Assessing the accuracy of each classification model






## 🔑 Key Skills Learned/Used 
- Using data science methodologies to define and formulate a real-world business problem
- Using data analysis and data visualisation to load a dataset, clean it, and find out interesting insights from it
- Interactive dashboard development with Plotly Dash
- Interactive map development using Folium
- Using machine learning to build a predictive model to help a business function more efficiently
- Structuring and building a data-findings report

## 🏆 Certificates 
To verify the certificates, click the images to follow the links.

<p align="middle">
  <a href="https://coursera.org/verify/8DTER4DBQU7A"><img src="https://github.com/Giflin/IBM-data-science-professional-certificate/blob/master/10.Applied%20Data%20Science%20Capstone/Coursera%208DTER4DBQU7A%20APPLIED%20DATA%20SCIENCE-1.png" height="420"></a>
  <a href="https://www.credly.com/earner/earned/badge/62332e50-7b68-4041-9c3e-36bcc96c582d"><img src="https://user-images.githubusercontent.com/84391594/161431807-63db38f1-2203-4383-aa6e-ad8b6e42ee55.png" height="420"></a>
</p>
