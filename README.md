# Project to find out whether 3 or 5 sets are better in grand slam matches in tennis:
1) Scrape match data from wikipedia for grand slams from 1970-2020: https://en.wikipedia.org/wiki/Wikipedia:WikiProject_Tennis/Grand_Slam_Project
2) Read all of the slam CSV files into one dataframe (15000+ matches)
3) Manipulate data to evaluate fairness increase and injuries from best of 0 to 1 to 3 to 5 sets of grand slam tennis matches.
4) Visualize results
5) Build ML classifier to see if I can predict if a match will be 3 sets or longer (i.e. 4 or 5 sets).

# For a detailed discussion about the results, see my blog post https://rigbym.blogspot.com/2020/10/the-eternal-3-set-vs-5-set-debate-in.html

# To run:

1) Run tennis_scrape. This saves each grand slam data to its own .csv file in Slam_Data.

2) Run tennis_analysis. This analyzes and produces plots comparing best of 3 and best of 5 set matches.

3) Run tennis_ml_classifier. This uses machine learning algorithms to predict whether a best of 5 set match will end in 3 sets or more (i.e. 4 or 5 sets).
