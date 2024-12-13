# Iowa-Food-Insecurity

**Introduction**

In this project my group and I used food insecurity data to predict where Iowans were experiencing the most food insecurity. We used CPS data to gather food insecurity indicators and build multiple models, then used ACS data to predict which PUMAs in Iowa were the most food insecure.

**Goals**
- Predict the most food insecure PUMAs in Iowa
- Discover key factors in determining food insecurity
- Visualize our findings on a map to highlight food insecurity across the state

**Data**

We used two data sources for this project. 

- CPS - Individual data aggregated onto the household level containing food insecurity indicators as well as demographic data.
- ACS - Demographic data aggregated onto the PUMA level, allowing us the geographically visualize our findings.
- Iowa Senior data - Secondary Data on the location of senior citizens (60+) in Iowa. Used to predict food insecurity among seniors.

**Methods**
1. Data Prep

- Clean both main datasets and aggregate to the household level.

2. Modeling
- Clustering: We chose to cluster 3 food insecurity varaibles. We chose to cluster these Y variables to provide better insights to multiple dimensions of food insecurity. When deciding which food insecurity variables to chose, we had to take into account how much data was missing from other potential Y variables. We ended up chosing the variables we had the most data on.
- Lasso regression: Used to predict food insecurity based on demographics and household data.

3.Visualizations
Used the PUMA data to visualize our models on a map and locate the regions we predicted to be the most food insecure.

**Results**
We found key factors in predicting food insecurity on the household level were education, marital status, age. We predict the Des Moines, Coucil Bluffs, and Dubuque PUMAs to be the most food insecure in Iowa.

  







