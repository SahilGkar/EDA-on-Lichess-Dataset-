# EDA-on-Lichess-Dataset-
I have done EDA on a chess dataset containing 20,000 chess games from the website Lichess. It is very basic as i did this project at the end of my first semester.


The objective of this project is to explore, clean, and analyse a dataset of online chess games to understand patterns related to player rating, game outcomes, time controls, popular openings, and game length.
The analysis aims to answer the following questions:
•	Which time controls and openings are most played?
•	How do player ratings influence the result?
•	What factors correlate with longer or shorter games?
•	How do openings affect winning percentages?


Problem Statement:
	To perform an exploratory data analysis (EDA) on a dataset of ~20,000 online chess games in order to understand how player ratings, time controls, and opening choices influence game outcomes and game length.


Dataset name: Chess Games Dataset
Source: Open-source dataset 
https://mavenanalytics.io/data-playground/online-chess-games


•	Rows: ~20,058 game records
•	Columns: 16 features



•	Numerical:
o	white_rating, black_rating, turns, opening_moves
•	Categorical:
o	winner, victory_status, opening_shortname, opening_fullname, time_increment
•	Text:
o	Opening names, response variations
•	Derived Features Added:
o	rating_diff, avg_rating, time_control_type, result_binary
