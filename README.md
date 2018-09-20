# ML-of-Legends-
A project to use Riot's APIs to perform statistical analysis, to aid in character selection and item choices.   
  
✊   

Main Goals:  
-Suggest what runes/items to buy on a certain champion (taking enemy champions into account)  
-Suggest what champions to play against enemy team comps  
-Track data of winrate based on different factors (time of day, games played in 1 session, whether you're playing with friends, etc)    
-Track enemy team's total gold in real time (based on their farm + time in game)  
-Do it all with a good looking UI  
-Profit 💵  
  
  
  
First task:   
1) Setup a pipeline to use YOLO9000 + OBS (or some other video recording software) to detect gamestate in real time     
2) Use the gamestate detection found in the previous step to calculate enemy gold/summoner spell cooldowns/ultimate cooldowns/ward timers in an overlay on top of the game (maybe investigate the platform overwolf is built on)   
3) Use YOLO9000 (or some real time API) to automatically detect bans/your team picks/enemy team picks, and suggest best champion (in your position) to counter enemy picks      
