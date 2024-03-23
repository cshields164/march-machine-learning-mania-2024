# March Machine Learning Mania 2024

Every year, the NCAA host a college basketball tournament called March Madness for the Men's and Women's division. Each team are seeded from 1-16 through different Regions to compete to determine who will come out on top. There is also a challenge for the viewers and sports fans who can create the perfect bracket to determine the winner. As data scientists, we want to find out whether or not we can use historical data of past tournaments to run an in-depth analysis to determine if we can use an analysis model to predict the perfect bracket.

# Observations

The first part of my EDA was to determine which datasets I wanted to go in-depth with. I decided to ingest the Teams, Seasons, Tournament Seeds, Regular Season Results, and Tournament Results. My initial process was to take in this data to determine what particular statistics can determine a teams chances of winning over the other. I also wanted to drop particular columns that were unnecessary to the analysis.

So after ingesting datasets and dropping unecessary columns, I decided to concatenate some dataframes to have a main dataset to run an analysis and EDA on. After finalizing the formation of the dataset, I ran a few EDA lines of code to determine how the distribution of columns and other variables will look.

With most of the statistics in the regular season and tournament, they were normally distributed when plotted with a histogram. We also see that majority of wins and scoring come from home teams which is obvious as the sports world call it home-field advantage. The Neutral game location has the same amount of scoring as Away teams, which was expected as well as the teams would perform in a different arena as opposed to their home location.

The teams that participate in the tournament and have a higher seed would have similar statistics in the tournament compared to the regular season statistics. This is the case because they generally play more games than the lower seeded due to them playing more games and not being elimnated as quickly. The lower seeded teams would have a lower average statistics in the tournmanent compared to the regular season statistics due to them being elimnated quicker than the higher seeded teams.