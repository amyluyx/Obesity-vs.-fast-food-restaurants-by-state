# Obesity-vs.-fast-food-restaurants-by-state

## Executive Summary
The Github readme file should contain a 1/2-1 page summary of your work.
It should: 
- contain one figure that you have computed and created from data
- tell who is the target audience of your story

  According to the CDC, nearly 42% of the adult population is classified as obese and around a third of Americans are said to be consuming fast food on any given day. Due to such statistics, it is imperative to understand the context, significance, and potential implications of these statistics in order to better examine potential connections and contributing factors. This led to the development of this project’s objective, targeting the population who consume fast foods in the United States.
  
  This project aims to interpret the findings regarding the correlation between state obesity rates and the density of fast food restaurants throughout the United States, which is represented in the “Number of Fast Food Restaurants vs. Obesity Rate” scatter plot. The data put into the graph was produced from two different .csv files: “Obesity Rate by State 2023” (Wisevoter.com) and “Fast Food Restaurants Across US' (Kaggle.comI)'. The two files were merged into ‘joint’. This final merged dataset included many relevant variables: ‘State’, ‘Obesity by State’, ‘...1’, ‘city’, ‘country’, ‘latitude’, ‘longitude’, ‘name’, ‘north’, ‘south’, ‘#’, ‘obesity’, ‘average weight’, and ‘diabetes percentage’. In order to create the ‘north’ and ‘south’ categories, a few extra calculations were made utilizing the ‘latitude’ variable and ifelse statements. If located north of the middle latitude, north would come out as TRUE; if not, then FALSE. Another variable added was Obesity by State, which tells the user the average weight of every state. As a result of the merged data, there is a definitive upward trendline, indicating that as the number of restaurants increase, the obesity rate also increases. Through analyzing the graph, it is safe to interpret that fast food restaurants are, in fact, a leading factor to state-level obesity in the United States. 


