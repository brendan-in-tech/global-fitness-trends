# FitScope  
**Analyzing global demand for digital fitness experiences (2018–2023)**  

This project explores how interest in workouts, gyms, and home-based fitness has evolved using Google Trends data. The analysis normalizes and visualizes worldwide search interest to uncover patterns in consumer behavior and the long-term shift toward digital fitness.  

## Goals  
- Measure global and regional trends for fitness-related keywords  
- Compare in-person vs. digital fitness interest over time  
- Identify which countries show the strongest growth in home-workout demand  

## Data  
All data comes from Google Trends and is included in the `data/` folder:  
- `workout.csv` — global interest in “workout”  
- `three_keywords.csv` — global interest in “home workout,” “gym workout,” and “home gym”  
- `workout_geo.csv` — five-year average by country  
- `three_keywords_geo.csv` — five-year averages for the same three keywords by country  

## Method  
- Loaded and cleaned data using pandas  
- Normalized by year to compare relative interest  
- Visualized keyword trends with matplotlib  

## Example Insights  
- Home-workout searches peaked during 2020 and remained above pre-COVID levels  
- Interest in “gym workout” recovered slower but stabilized post-2022  
- Southeast Asia shows the fastest growth in home-based fitness demand  

## Tech Stack  
- Python 3  
- pandas  
- matplotlib  
