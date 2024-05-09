# applied-data-science-capstone-project-spacex-ibm
This project is part of IBM Data Science certificate. https://www.coursera.org/professional-certificates/ibm-data-science
SpaceX Falcon 9 First Stage Landing Prediction
In this project, we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch. In this lab, you will collect and make sure the data is in the correct format from an API. The following is an example of a successful and launch. This supervised classification project was carried out as part of the IBM Data Science Professional certificate.

Presentation of the project
The presentation covers all steps described in Jupyter Notebooks in following sections. 
From Data Collection to Analysis to prediction of launch succeess (succesful first stage landing) with classification algorithms. 

SpaceX Data Collection included:
Request to the SpaceX API.
Clean the requested data.
SpaceX Data Collection - Jupyter Notebook

Data Wrangling
In this lab, we will perform some Exploratory Data Analysis (EDA) to find some patterns in the data and determine what would be the label for training supervised models.
SpaceX Data Wrangling - Jupyter Notebook

Web scraping Falcon 9 and Falcon Heavy Launches Records from Wikipedia
Web scraping to collect Falcon 9 historical launch records from a Wikipedia page titled List of Falcon 9 and Falcon Heavy launches. Beautiful soup.
Falcon9 webscraping - Jupyter Notebook

EDA - Undertanding Dataset. SQL Queries.
Understand the Spacex DataSet
Load the dataset into the corresponding table.
Execute SQL queries to answer assignment questions
EDA - Undertanding Dataset - Jupyter Notebook

EDA Data visualization
EDA Data visualization. Exploring and Preparing Data.
Perform exploratory Data Analysis and Feature Engineering using Pandas and Matplotlib Exploratory Data Analysis.
Preparing Data Feature Engineering
In this assignment, we will predict if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is due to the fact that SpaceX can reuse the first stage.

EDA - Data Visualization - Jupyter Notebook
SpaceX Launch Records Dashboard
Dashboard Application with Plotly Dash about SpaceX launch sites, sucess rate and payload. In the previous exploratory data analysis labs, you have visualized the SpaceX launch dataset using matplotlib and seaborn and discovered some preliminary correlations between the launch site and success rates.

Launch Site Drop-down Input Component
Callback function to render success-pie-chart based on selected site dropdown
Range Slider to Select Payload
Callback function to render the success-payload-scatter-chart scatter plot.
Note: the interactive Notebook doesnot work on Github. Must be downloaded and executed locally. Or on Google Colab.

Dashboard - Jupyter Notebook
Launch Sites Locations Analysis with Folium
Interactive The launch success rate may depend on many factors such as payload mass, orbit type, and so on. It may also depend on the location and proximities of a launch site, i.e., the initial position of rocket trajectories. Finding an optimal location for building a launch site certainly involves many factors and hopefully we could discover some of the factors by analyzing the existing launch site locations.
In this lab, you will be performing more interactive visual analytics using Folium.
Note: The interactive Notebook does not work on Github. It must be downloaded and run locally, with an Anaconda distribution for example. Or on Google Colab.

Launch sites - Interactive Notebook with Folium
SpaceX Launch Success. Machine Learning classification
Machine Learning Prediction using Classification Algorithms: KNN, Decision Tree, SVM, Logistic Regression.
Optimization of hyperparameters.

Machine Learning - Jupyter Notebook
