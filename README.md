create database if not exists IPL_Data;

use IPL_Data;

create Table Ball2Ball
(
match_id int,
season varchar(255),
start_date date,
venue int,
innings int,
ball int,
batting_team varchar(255),
bowling_team varchar(255),
striker varchar(255),
non_striker varchar(255),
bowler varchar(255),
runs_off_bat int,
extras int,
wides int,
noballs int,
byes int,
legbyes int,
penalty int,
wicket_type varchar(255),
player_dismissed varchar(255),
other_wicket_type varchar(255),
other_player_dismissed varchar(255)
);


select * 
from Ball2Ball






