# LyonFlix: Urban Data-Driven Movie Recommendations
"*What if Lyon's mood could decide what you watch tonight ? 🍿*"

- 🌧️ Rainy day? 🚇 Metro strike? 🎉 Too many events downtown ?
- Don't worry, LyonFlix is here to find out whether Lyon is having its main-character moment… or just needs a movie night. 🎭

## What's the idea ?
LyonFlix is a data engineering project that connects the dots between city life and cinema.

We combine urban data local events, weather conditions, public transport disruptions with movie information to estimate Lyon's current mood and explore which films match it best.

Because let's be honest: a sunny day in Parc de la Tête d'Or and a rainy day with transport disruptions don't exactly give the same vibes. ☀️🌧️

# Objectives 
- Collect and integrate data from multiple sources.
- Analyze local events, weather conditions, and public transport disruptions.
- I dentify urban factors that may influence the estimated mood of Lyon.
- Design a structured database for analytical queries.
- Explore movie recommendations based on the estimated city mood.
- Evaluate the impact of data availability and quality on the results.

# Business Questions 
1. What is the overall mood of Lyon at a given time ?
2. What are the most influential urban factors for estimating Lyon's mood ?
3. Which movies best reflect Lyon's current mood ?
4. Which movies do not match Lyon's current mood ?
5. How does the availability of urban data affect mood estimation and movie recommendations ?

# Meet the Data 
Local events : Festivals, cultural activities, and what's happening around town.
Weather : Sunshine, rain, clouds, and the occasional mood killer.
Public transport : Service alerts and disruptions that can change the daily vibe.
Movie Data : Ratings, genres, descriptions, and potential movie-night candidates.

# 🏗️ Behind the Scenes 

No magic here. Just data engineering. 🪄

Our planned star schema organizes the data into a central fact table and several dimension tables:
FACT_CITY_MOOD — trying to make sense of the city's vibe.
DIM_DATE — because timing matters.
DIM_WEATHER — sunny-side-up or rainy-day energy?
DIM_EVENT — what's happening in Lyon?
DIM_MOVIE — the movie universe.
DIM_TRANSPORT — smooth commute or plot twist?

## 🛠️ Our Tech Stack
- 🐍 **Python** collecting and preparing the data.
- 🐼 **Pandas** making messy datasets behave.
- 🍃 **MongoDB** storing flexible, semi-structured urban data.
- 🐘 **PostgreSQL** organizing our data into a structured star schema.
- 🧮 **SQL & MongoDB Query Language (MQL)** asking the important questions in two different ways.
- 🐳 **Docker** because *"it works on my machine"* isn't a deployment strategy.
- 📓 **Jupyter Notebook** experimenting before things get serious.
- 🐙 **Git & GitHub** keeping track of our progress and our mistakes.
  
# The Plot 
1. Collect the data.
2. Clean up the mess.
3. Connect the different sources.
4. Build the database and star schema.
5. Run SQL queries and investigate the results.
6. Estimate Lyon's mood using available indicators.
7. Explore mood-based movie recommendations.
8. Evaluate what works, what doesn't, and what the data refuses to tell us.

# The Expected Finale 
By the end of the project, we aim to have:
- A collection of integrated urban and movie datasets.
- A structured PostgreSQL database.
- SQL queries answering our five business questions.
- An analysis of the factors associated with Lyon's estimated mood.
- A movie recommendation approach based on urban context.
- An honest assessment of data quality and missing information.


# Team 
Two Students :
Salma Kattabi and Gao Quanleyi
