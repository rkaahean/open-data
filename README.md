
# Analyzing football data provided by statsbomb.

# Understanding the structure of data.

 - Under competitions, pick a one by opening the json and checking the season and the league. 
 - Get the league id. For the spanish league, it is 11.
 - Under the matches folder, open the folder representing the competition. In this case, it is 11.
 - Each file represents the matches played in various competitions in various seasons.
 - For example, in ```4.json```, it represents data from the 2018/19 La Liga season.
 - It has a list of match id's.
 - Under the events folder, you can find the ```{match_id}.json```, representing all the events in the match.