# EBX-Dashboard_Cricket
To make improvement decisions from ESPN Cricinfo: https://www.espncricinfo.com/records/tournament/batting-most-runs-career/icc-champions-trophy-2024-25-16814

To create a TIBCO EBX project that incorporates batting statistics from the ICC Champions Trophy 2024/25, follow these steps:

Define the Data Model:
Entity: PlayerStatistics
Attributes:
PlayerName (String)
Team (String)
MatchesPlayed (Integer)
InningsBatted (Integer)
NotOuts (Integer)
RunsScored (Integer)
HighestScore (String)
BattingAverage (Float)
BallsFaced (Integer)
StrikeRate (Float)
Centuries (Integer)
HalfCenturies (Integer)
Ducks (Integer)
FoursHit (Integer)
SixesHit (Integer)
Create the Data Set:
Populate the PlayerStatistics data set with the batting records from the ICC Champions Trophy 2024/25. For example:
PlayerName: Ben Duckett
Team: England
MatchesPlayed: 3
InningsBatted: 3
NotOuts: 0
RunsScored: 227
HighestScore: 165
BattingAverage: 75.66
BallsFaced: 209
StrikeRate: 108.61
Centuries: 1
HalfCenturies: 0
Ducks: 0
FoursHit: 25
SixesHit: 3
PlayerName: Joe Root
Team: England
MatchesPlayed: 3
InningsBatted: 3
NotOuts: 0
RunsScored: 225
HighestScore: 120
BattingAverage: 75.00
BallsFaced: 233
StrikeRate: 96.56
Centuries: 1
HalfCenturies: 1
Ducks: 0
FoursHit: 19
SixesHit: 2
PlayerName: Virat Kohli
Team: India
MatchesPlayed: 4
InningsBatted: 4
NotOuts: 1
RunsScored: 217
HighestScore: 100*
BattingAverage: 72.33
BallsFaced: 261
StrikeRate: 83.14
Centuries: 1
HalfCenturies: 1
Ducks: 0
FoursHit: 15
SixesHit: 0
(Continue adding records for other players as needed.)
Data Entry:
Input the data into the PlayerStatistics data set within TIBCO EBX, ensuring accuracy and consistency with the source information.
Utilize the Data:
With the data set established, you can now leverage TIBCO EBX's features to manage, analyze, and visualize the batting statistics as required.
