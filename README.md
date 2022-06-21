Database & SQL Questions
INSTRUCTIONS
    1. Install mysql (Optional)
    2. Upload tables (Optional)
    3. Submit the SQL Query along with the Result for each question below

Data is present in the below Spreadsheet:
https://docs.google.com/spreadsheets/d/14RH6NUFRjY2QRp9FPEU4wxPlq5jsMIyX1mRFjuK3t7k/edit?usp=sharing

TABLES USED
    1. TeamGame
    2. FantasyDefenseGame
    3. PlayerGameMaster
    4. PlayerGameFeatures
QUESTIONS
    1. What is the total number of Teams for season 2008 who played on Artificial surface (Table = TeamGame) 

    2. Display top 3 team which has the Maximum Opponent Score in a home game (Table = TeamGame)

    3. Create a table below from FantasyDefenseGame. Total is the sum of each value across the entire data set. (Table = FantasyDefenseGame)

Value                    Total
- - - - - - - - - - - - - - - - - - - 
PointsAllowed	    117015
SoloTackles	    224485
Sacks	                11877




    4. For Season 2014 and Team ARI:
        a. Create a temp table Player from PlayerGameMaster with Season, Team, Name, Position
        b. Create a temp table Scores from PlayerGameFeatures with Season, Team, Name, Position, PassingAttempts
        c. Join the two temp tables capturing all fields from Player and only Passing Attempts from Scores and show rows where Passing Attempts > 1 (Primary Key = Season, Team, Name, Position)

    5. What is Primary Key and Foreign Key?

    6. What is a Self-Join? How is it different from Cross Join?

    7. What is an ER Diagram?
