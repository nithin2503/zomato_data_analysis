**Zomato Data Analysis**

This project performs an exploratory data analysis (EDA) on Zomato restaurant data. It includes data preprocessing, visualization, and insights extraction using Python.

**Dataset**

The dataset contains information about restaurants, including ratings, votes, online order availability, restaurant types, and approximate costs for two people.

**Columns in the dataset:**

name: Name of the restaurant

rate: Restaurant rating

votes: Number of votes received

online_order: Whether online orders are available (Yes/No)

listed_in(type): Type of restaurant

approx_cost(for two people): Estimated cost for two people

**Code Overview:**

Data Loading: Reads the dataset using Pandas.

Data Cleaning: Converts rating values into numerical format.

**Visualizations:**

Count plots for listed_in(type) and online_order

Histogram of restaurant ratings

Boxplot of ratings vs. online order availability

Heatmap of restaurant type vs. online orders

Line plot showing total votes per restaurant type

**Insights:**

Do a greater number of restaurants provide online delivery as opposed to offline services?

Which types of restaurants are the most favored by the general public?

What price range is preferred by couples for their dinner at restaurants?

Identifies the restaurant with the highest votes.

