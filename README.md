# IPL_Players_Data_Analysis
The main objective of this project is to analyse the players data, match summary data, batting summary data and bowling  summary data of the T20 world cup championship to select 11 best players for an IPL team. The players of each category (Openers, middle order, lower order, all rounders and fast bowlers) must satisfy certain criteria to be considered for the final 11. The criteria are provided by stakeholders and attached in the pdf file named “Selection criteria”.

# Dataset
The dataset contains 4 tables as follows <br>
#### A.	T20_WC_batting_summary <br>
    Contains batting details with columns as follows.

1.	Match                 :  Specifies the teams competing in the match (team1 versus team2).<br>
2.	TeamInnings           :  Indicates batting team.<br>
3.	BattingPos            :  Denotes the order in which the batsman comes to bat (e.g., 1st, 2nd, etc.).<br>
4.	BatsmanName           :  The name of the player who is batting.<br>
5.	Dismissal             :  The name of the bowler who took the wicket.<br>
6.	Runs                  :  The total number of runs scored by the batsman.<br>
7.	Balls                 : The number of balls the batsman faced during their innings.<br>
8.	 4s                   :  The total number of boundaries (4s) hit by the batsman.<br>
9.	 6s                   :  The total number of sixes (6s) hit by the batsman.<br>
10.	 SR (strike rate)     :  The batsman's batting strike rate, calculated as the number of runs scored per 100 balls <br>
                             faced.<br>

#### B.	T20_WC_bowling_summary<br>
    Contains bowling details with columns as follows.

1.	Match                 : The teams involved in the match (e.g., Team1 vs Team2).<br>
2.	BowlingTeam           : The team that is bowling during the specific period.<br>
3.	Bowler Name           : The name of the bowler who is bowling.<br>
4.	Overs                 : The total number of overs bowled by the bowler in the match.<br>
5.	Maiden                : The number of overs bowled by the bowler without conceding any runs.<br>
6.	Runs                  : The total number of runs conceded by the bowler.<br>
7.	Wickets               : The total number of wickets taken by the bowler.<br>
8.	Economy               : The bowler's economy rate, calculated as runs conceded per over.<br>
9.	0s                    : The number of balls bowled where no runs were scored by the batsman.<br>
10.	4s                    : The total number of boundaries (4s) hit off the bowler's deliveries.<br>
11.	6s                    : The total number of sixes (6s) hit off the bowler's deliveries.<br>
12.	Wides                 : The number of deliveries bowled that were wide and not counted as legitimate balls.<br>
13.	No Balls              : The number of no balls bowled by the bowler during the match.<br>

#### C.	T20_WC_player_info<br>
    Contains all the information of the players participating in the T20 world cup 
    championship. Contains columns as follows.

1.	Name                  : The name of the player participating in the T20 World Cup.<br>
2.	Team                  : The team the player represents in the T20 World Cup.<br>
3.	Batting Style         : The player's preferred batting style, such as right-hand or left-hand, and any specific <br>
                            techniques (e.g., right-handed batsman).<br>
4.	Bowling Style         : The player's preferred bowling style (e.g., fast bowler, off-spin, left-arm  orthodox).<br>
5.	Playing Role          : The role the player performs in the team (e.g., batsman, bowler, all-rounder, wicketkeeper). <br>
6.	Description           : A brief overview of the player's skills, achievements, and playing characteristics.<br>

#### D.	T20_WC_match_results<br>
    Contains information about the match results and have columns as follows.

1.	Team1                 : The first team participating in the match.<br>
2.	Team2                 : The second team participating in the match.<br>
3.	Winner                : The team that won the match.<br>
4.	Margin                : The winning margin, indicating by how many runs or wickets the winner triumphed.<br>
5.	Ground                : The venue or stadium where the match was played.<br>
6.	Match Date            : The date on which the match took place.<br>
7.	Scorecard             : A detailed summary of the match, showing the performances of both teams, including runs, <br>
                            wickets, and individual player statistics.<br>


# Project Steps:
1.	Four .json files (t20_wc_batting_summary, t20_wc_bowling_summary, t20_wc_player_info, t20_wc_match_results)<br>
    loaded in jupyter_notebook.<br>
2.	Basic cleaning and transformation performed in the 4 tables.<br>
3.	The four tables converted to csv files.<br>
4.	The 4 csv files loaded in Power BI.<br>
5.	Data analysis, data visualization and final 11 selection in Power BI.<br>

