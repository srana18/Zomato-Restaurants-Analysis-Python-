# Zomato-Restaurants-Analysis-Python-


->Dataset:

•	Source (Kaggle): Zomato Restaurants Dataset(link: https://www.kaggle.com/datasets/abhijitdahatonde/zomato-restaurants-dataset/data)
•	Records Analyzed: 7,105 restaurants

->Tech Stack:

Language: Python

Libraries: Pandas, NumPy, Seaborn, Matplotlib, Plotly Express

->Objective:

To analyze restaurant data to uncover insights on popularity, service gaps, and cost trends.

->Key Performance Indicators (KPIs):

1. Popularity
   
•	Restaurants:

  Average Rating (out of 5)
  
  Number of Ratings
  
  Popularity Score (custom KPI combining rating & number of ratings)

•	Cuisines:

  Count of cuisines among top 1% restaurants
  
  Count of cuisines in the overall dataset
  
•	Restaurant Types:

  Count of types among top 1% restaurants
  
  Count of types in the overall dataset
  
•	Areas:

  Count of occurrences among top 1% restaurants
  
  Count of occurrences in the overall dataset
  
2. Service Gaps
   
  % of restaurants offering Online Ordering

  % of restaurants offering Table Booking

3. Cost Trends
   
  Average cost of Luxury Restaurants
  
  Average cost of Affordable Restaurants

->Approach:

  1. Data Preprocessing:
     
     Formatted column names & values
     
     Handled nulls (median imputation for skewed data) and duplicates

     Outliers kept (genuine business cases)

   3. Exploratory Data Analysis (EDA)
      
      Univariate Analysis:
      
      Histograms & boxplots for distributions/outliers

      Identified top restaurants, cuisines, types, and areas

      Bivariate Analysis:
      
      Cuisines & restaurant types among top 1%

      Service gaps in top 1%

      Popularity vs cost (scatter plots)
      
->Visualization Tools Used:

Seaborn → Histograms, boxplots

Plotly Express → Interactive plots like histogram, pie charts, bar plots

->Result/Impact:

1. Top 5 Restaurants identified based on popularity score.
   
2. Top Restaurants Differ in Restaurant Types
   
   IMPACT:
   
   Suggest that high-performing restaurants often occupy niche or less common segments. Also, reveals gaps between
   popularity and availability.
   
   New entrants should lean towards niche/unique formats so that its easier to break through.
   Existing mainstream players should stay mainstream (volume-driven) but innovate by borrowing niche elements to avoid         being “just another option.”

3. Cuisine Diversity is a Differentiator
   
   IMPACT:
   This suggests that variety and niche offerings help top restaurants stand out, while the majority of restaurants stick        to standard popular cuisines.

4. High density restaurant areas common to both affordable and luxury restaurants:

   IMPACT:
   Indicates that location plays a key role in restaurant presence and potential visibility, but high performance depends on     other factors like cuisine, type, and service.

5. Service Gaps Identified
   Top 1%: ~50% offer Online Ordering, ~60% offer Table Booking
   Overall: ~52.5% Online Ordering, only ~10.5% Table Booking

   IMPACT:
   Big opportunity in Table Booking services for customer convenience.

6. Cost Trends
   Split restaurants into Affordable (<₹2000) & Luxury (≥₹2000).
   Top 1% mostly in the affordable range.
   
   IMPACT:
   Popularity is not limited to High Price. Success comes from a combination of other factors(service, cuisine, restaurant      type and location).

   

->This analysis provides actionable insights into how restaurants can stand out in a competitive market by focusing on service innovation, diverse cuisines, and affordability.


   



   

   
