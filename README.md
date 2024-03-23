# March Machine Learning Mania 2024

Every year, the NCAA host a college basketball tournament called March Madness for the Men's and Women's division. Each team are seeded from 1-16 through different Regions to compete to determine who will come out on top. There is also a challenge for the viewers and sports fans who can create the perfect bracket to determine the winner. As data scientists, we want to find out whether or not we can use historical data of past tournaments to run an in-depth analysis to determine if we can use an analysis model to predict the perfect bracket.

# Observations

The first part of my EDA was to determine which datasets I wanted to go in-depth with. I decided to ingest the Teams, Seasons, Tournament Seeds, Regular Season Results, and Tournament Results. My initial process was to take in this data to determine what particular statistics can determine a teams chances of winning over the other. I also wanted to drop particular columns that were unnecessary to the analysis.

So after ingesting datasets and dropping unecessary columns, I decided to concatenate some dataframes to have a main dataset to run an analysis and EDA on.