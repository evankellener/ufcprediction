# ufcprediction
Using XGbossted trees and logistic regression to predict ufc fights given fighter stats.
I am using the "UFC/MMA Biggest Dataset With Differentials" dataset from Kaggle: 'https://www.kaggle.com/datasets/danmcinerney/mma-differentials-and-elo/code'. I used the author of the databases' code(Dan McInerney) to get features with the highest correlation to fight outcomes but used my own build of logistic regression. The highest score I got using scaled values was 0.6524, which is pretty much the same as the author's results using the tree-based approach. I have detailed some of the steps I took throughout and how I got better and better results. 

Using the SVM architecture, using the following features: 
['age', 'reach', 'precomp_avg_age_differential_vs_opp', 'precomp_change_avg_ground_strikes_attempts_per_min_differential_peak_vs_opp', 'precomp_head_strikes_def_vs_opp', 'precomp_avg_head_strikes_landed_per_min_differential_vs_opp', 'precomp_change_avg_elo_differential_vs_peak', 'precomp_change_elo_differential_vs_valley']

I got an accuracy score of 0.789 which is essentially 79% accurate. 
