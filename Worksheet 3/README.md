
#COMP110: Worksheet 3
##Database Design
#####Player Table:

player_id | player_name 
--- | --- | ---
 | 
 
 Player_id is the primary key. The data about the player is stored in this table.
 
##### Level Table:

level_id | level_name 
--- | --- | ---
 | 
 
 Level_id is the primary key. This table contains data about the levels.
 
#####Score Table:
score_id | player_id | level_id | score
--- | --- | --- | --- |--- |
 | 
 
 Score_id is the primary key. This table contains the scores with differenet players in different levels.


##Entity-relationship Diagrams
![ERD 2](https://github.com/MaddieK19/comp110-worksheets/blob/master/Worksheet%203/COMP110%20ERD%20-%20Standard.png?raw=true)  
One player can have many scores and have many scores for each level.

##Client-Server Communication Pseudocode 
Client Side | Server Side
--- | --- | --- |
REQUEST access to database | ALLOW access
SEND username, level and score | RECEIVE  username, level and score
 |IF the user doesn't exist add them to database
  | IF user has a prexisting score for that level update it to the highest score
 | SEND updated high score table
DISPLAY highscore table | END connection






 
 
