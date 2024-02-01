# Video Game Sales Analysis:

**Video Games Python Code**

This repository contains Python code for analyzing video game sales data. The dataset, obtained from Kaggle, includes information about various video games, such as sales rank, name, platform, year of release, genre, publisher, and sales data for different regions (North America, Europe, Japan, and others).

**Data Import and Cleaning:**
- Utilizes Pandas to import and clean the video game sales dataset.
- Drops missing values and checks for duplicates.
  
**Exploratory Data Analysis (EDA):**
- Provides a summary of the data, including statistics and data types.
- Visualizes sales distribution using histograms, boxplots, and quantile plots.
- Examines the correlation matrix to identify relationships between sales in different regions.

**Top 5 Analysis:**
- Identifies the top 5 best-selling games, genres, platforms, and publishers based on global sales.

**Sales Distribution:**
- Presents a bar chart showing the distribution of sales across different regions.

**Yearly Trends:**
- Displays a line plot illustrating the global sales trend from 1997 to 2016.
          
**Genre-Platform Combinations:**
- Utilizes a heatmap to visualize the global sales of different genre-platform combinations.

**Statistical Analysis:**
- Conducts hypothesis testing for platform impact, genre impact, and publisher impact on global sales.
- Builds a linear regression model to predict global sales based on genre, publisher, and platform.
- Assesses multicollinearity, heteroskedasticity, and robustness of coefficient estimates.
- Uses cross-validation to evaluate model performance
  
(P.S. Adding more code, will update folder accordingly)

**Take-Two Interactive Sales Tableau Dashboard**

Welcome to the Take-Two Interactive Sales Dashboard, a comprehensive visualization of sales data spanning from 1997 to 2016. This Tableau dashboard provides valuable insights into the gaming industry giant's performance, with a particular focus on the renowned Grand Theft Auto V (GTA V). Here's what you'll find in this dynamic and informative dashboard:

**1) GTA V Sales Metrics:** Dive into key sales metrics for GTA V, one of Take-Two Interactive's flagship games. Explore its global sales, European sales, North American sales, and Japan sales individually, gaining a nuanced understanding of its success across different regions.
   
**2) Global Sales Over Time:** Witness the evolution of Take-Two Interactive's global sales over the years through an intuitive line graph. Track the company's financial performance and identify trends that shaped its journey from 1997 to 2016.
   
**3) Top 10 Best Selling Games:** Get a glimpse of Take-Two Interactive's gaming portfolio by exploring the top 10 best-selling games. Uncover the titles that left a lasting impact on the gaming community and contributed significantly to the company's success.
   
**4) Top 4 Genres:** Discover the predominant genres within Take-Two Interactive's gaming catalog. With action taking the lead as the number 1 genre, gain insights into the diverse gaming experiences offered by the company.
   
**5) Sales Platform Distribution:** Explore the distribution of sales across different gaming platforms. Identify the primary platforms driving Take-Two Interactive's success, with PS2 claiming the top spot.
   
Whether you're a gaming enthusiast, industry analyst, or simply curious about Take-Two Interactive's sales performance, this dashboard provides a visually engaging and informative exploration of the company's journey through the gaming landscape. Download, explore, and uncover the story behind Take-Two Interactive's success in the world of gaming.

(P.S. PowerPoint attached incase Tableau not accessible to get idea of what the dashboard might look like, but open Tableau to see interactive features)

# Econometrics Project: What Variables Impact Attendance

- **Descriptive Analysis:** Perform a univariate analysis
    - histograms, quantile plots, correlation plots, etc.
    - exploratory analysis using Pandas Profiling
    - Estimate density distributions (e.g., Cullen & Frey)
    - Transformations on any non-linearities within variables
    - Comment on any outliers
    - Impute N/A Values

- **Variable Selection:**
    - Use Boruta Algorithm to identify top 2 predictors
    - Use Mallows Cp to identify top 2 predictors 

- **Model Building:** Explore several competing OLS models
    - Evaluate transformations of variables
    - Look at Cook’s distance Plot, Residuals Plot
    - Evaluate the robustness of coefficient estimates by bootstrapping model
    - Use cross-validation to evaluate model’s performance
 
# Fashion Forward E-Commerce Clothing Classifier

**Project Overview**

Welcome to the Fashion Forward E-Commerce Clothing Classifier project! In this endeavor, we aim to revolutionize the fashion and retail industry by developing an innovative garment classification system. Our goal is to create a smarter, more efficient, and user-friendly shopping experience, leveraging cutting-edge AI and machine learning techniques.

**Objective**

As a data scientist, the primary objective is to implement a garment classifier that automates the categorization of clothing items for Fashion Forward, a new AI-based e-commerce clothing retailer. The classifier will assist in automatically categorizing new product listings, making it easier for customers to find their desired items and facilitating efficient inventory management.

Technical Details To achieve this, we will define a Convolutional Neural Network (CNN) classifier with specific layers, including convolutional layers, RectiLinear unit activation layers, max pooling layers, and fully connected layers. The model will be trained on the FashionMNIST dataset, a collection of grayscale images representing various clothing types.

**Implementation Steps**

1) Define the CNN classifier with the specified layers.
2) Train the CNN on the provided train_data using a suitable optimizer.
3) Limit the training loop to 1 or 2 epochs to optimize run time.
4) Test the CNN on the provided test_data and store predictions in a list called predictions.
5) Calculate accuracy, per-class precision, and recall for the trained classifier on the test data.
6) Store the results in variables accuracy, precision, and recall respectively, using lists of appropriate length for precision and recall.

# DataCamp: Exploring London's Travel Network

**Project Description**

**Overview**
How do Londoners get around? This project dives into the vast public transport network provided by Transport for London (TfL). With over 1.5 million journeys per day, TfL plays a crucial role in facilitating efficient travel across the UK's capital. This introductory project uses SQL to analyze a database containing information about TfL journeys spanning 12 years, from 2010 to 2022.

**Objectives**
- Most Popular Transport Types: Write SQL queries to identify the most popular transport methods based on the total number of journeys. The output should include columns for Journey Type (JOURNEY_TYPE) and Total Journeys in millions (TOTAL_JOURNEYS_MILLIONS), sorted in descending order. Save the query as most_popular_transport_types.
- Emirates Airline Popularity: Determine the top five months and years for the Emirates Airline cable car. The output should include columns for Month (MONTH), Year (YEAR), and Journeys in millions rounded to two decimal places (ROUNDED_JOURNEYS_MILLIONS). Save the result as emirates_airline_popularity.
- Least Popular Years for Underground & DLR Journeys: Find the five years with the lowest volume of Underground & DLR journeys. The output should include columns for Year (YEAR), Journey Type (JOURNEY_TYPE), and Total Journeys in millions (TOTAL_JOURNEYS_MILLIONS). Save the result as least_popular_years_tube.

**Guided Project (Snowflake)**
- For those using Snowflake, the project offers a guided approach with specific tasks and real-time automated code checks to ensure a smooth workflow.

**Instructions**
- Utilize the provided SQL cells in the Workspace.
- Access the Snowflake database using the syntax FROM TFL.JOURNEYS (ensure uppercase).
- Keep the names of the DataFrames consistent with the provided ones to avoid renaming issues.
- Follow the specified output format for each query.
- Let's embark on this journey through London's travel network data!

# Quant Finance: Trading Strategy

- **Trading Strategy**
      - Build a strategy based off technical indicators

- **Portfolio Optimisation**
      - Build a Minimum Variance Portfolio

- **AI Bots**
      - Set up AI Bots that will Buy for you

# DataCamp: NYC Airbnb Data Analysis

In the Exploring the NYC Airbnb Market project, I will apply data importing and cleaning skills to analyze the Airbnb market in New York. I will ingest and combine the data from multiple file types, and clean strings and format dates to extract accurate information.  

I accessed this Data Analytical project from Data Camp. The focus of this project is to import and clean data.

# Tableau: Car Crash Data

Overview: In pursuit of contributing to automotive safety, I undertook a comprehensive analysis of NHSTA data on car crashes, specifically focusing on substance involvement. The resulting project is a dynamic Tableau dashboard designed to provide valuable insights into the impact of substances on car safety.

**Key Features:**

  **1) Substance Metrics Comparison:**
       - Parameter-driven switch between alcohol and drug metrics, enabling a detailed comparative analysis.

  **2) Weekly Crash Frequency:**
       - Visual representation of crash frequency throughout the week, offering insights into substance-related patterns.

  **3) Injury Impact Visualization:**
       - Graphic display of the impact of substance-related crashes on the severity of injuries sustained.

  **3) Crash Characteristics Analysis:**
       - Examination of crash characteristics and their correlation with hospitalization or fatality, categorized by alcohol or drug involvement.

This project serves as a testament to my commitment to leveraging data for informed decision-making in the realm of automotive safety. It is not only a showcase of technical skills but a demonstration of strategic thinking and analytical prowess.

(P.S. PowerPoint attached incase Tableau not accessible to get idea of what the dashboard might look like, but open Tableau to see interactive features)
