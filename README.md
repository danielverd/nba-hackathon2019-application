# nba-hackathon2019-application

Unfinished application question for the 2019 NBA Hackathon. Elements are recycled from the 2018 question, but the data structures are updated to reflect the new question. The prompt requires that you iterate through play by play data and keep a running tab of Offensive Rating and Defensive Rating, which is the measure of pointsScored/100Possessions and pointsAllowed/100Possessions when a player is on the court.

The program currently is stuck on a data-ordering error. Due to the format of the data, there is (at least) one instance of a player being subbed out of the game while already on the bench. The program crashes in this case. This is likely caused by the program's current method of ordering, reordering, and breaking ties in ordering. 

The possession counter is not correct yet, but without solving the subbing out a benched player issue, the program can't produce an output. Debugging the possession counter would be impractical until outputs can be seen and judged as reasonable or not.
