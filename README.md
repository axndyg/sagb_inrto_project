# How do the number and timing of shots and fouls vary across different European leagues (Italy, England, France), and what patterns emerge when comparing these leagues?
We looked into 3 different European countries (Italy, England, France) and look into the relationship between fouls and shots attempted. After looking into the 3 different countries, we looked for a relationship within the countries and also compared the 3 countries between each other. 

#### metrics & formalities
- late game considered t > 60, where t was measured in minutes
  - Interval looking at 33% of game time
- early game considered t <= 60, t also measured in minutes
  - Internal looking at 66% of game time 
- an event recorded (foul / shot) by minute x would be slotted into the appropriate interval 
- Density recorded by 
                              n / T 
                              Where
                   n = count of events in interval 
                 T = total number of events recorded
## France 🇫🇷
## Relationship between Late Game Fouls/Shots vs Team
<img width="1024" alt="image" src="https://github.com/user-attachments/assets/dde95472-8bf8-472b-af39-793589cd6cb3">
The left graph illustrates the foul and shot densities per team during the late game. The right graph compares shot density to foul density for each team in the same period, with a threshold set at 0.33. In both graphs, fouls and shots are mostly distributed evenly around the threshold.

## Relationship between Late Game Foul/Shot density w/ Match
<img width="1038" alt="image" src="https://github.com/user-attachments/assets/eb1eada7-50aa-4c69-b9d2-aa603dd21696">
The left graph displays foul and shot densities per match during the late game. The right graph compares shot density to foul density per match in the same period, with a threshold of 0.33. In both graphs, the foul and shot densities exceed the threshold.

## Relationship between Early Game Fouls/Shots vs Team
<img width="1038" alt="image" src="https://github.com/user-attachments/assets/d3657dde-0691-4494-b86a-3bdc4c158d48">
The left graph shows foul and shot densities per team during the early game, while the right graph compares shot density to foul density for each team in the same period. The threshold is set at 0.66, with most fouls and shots distributed above this threshold in both graphs.

## Relationship between Early Game Foul/Shot density w/ Match
<img width="1038" alt="image" src="https://github.com/user-attachments/assets/0ab4e598-8ea6-46d7-b07b-a2b1aeeb2be3">
The left graph illustrates foul and shot densities per team during the early game, while the right graph compares shot density to foul density for each team in the same period. The threshold is set at 0.66, with most fouls and shots falling below this threshold in both graphs.

## Shots/Fouls by the Minute
<img width="1038" alt="image" src="https://github.com/user-attachments/assets/eb60472f-36d5-4742-97a6-e4a0e53cadce">
The left graph displays the number of shots over the minutes of the game, while the right graph shows the number of fouls over the same period. Both graphs indicate that the peak for shots and fouls occurred between the 40-45 minute mark.

## Average Late Game Foul/Shot density by Team
<img width="1038" alt="image" src="https://github.com/user-attachments/assets/707b9732-3bfd-486d-8e2a-150a6ba566cc">
These graphs are converted from scatter plots to bar graphs to help identify additional patterns or relationships between shots and fouls. As observed, the shot and foul densities follow similar patterns in both graphs, though the relationship between them remains weak.

## Average Early Game Foul/Shot Density by Team
<img width="1027" alt="image" src="https://github.com/user-attachments/assets/6cd1bf64-da68-4318-80cf-8a0973512351">
The shot and foul graphs reveal that shot density follows a similar trend to foul density in the early game. However, the relationship between the two remains weak.

Our analysis of shots and fouls during games revealed a correlation between the two. When comparing early and late game densities, we found that in the early stages, both shots and fouls were less frequent, more evenly distributed, and often below the threshold. In contrast, the late game showed a higher density of shots and fouls, with many data points exceeding the threshold, indicating a possible relationship between shot attempts and fouls by team. Notably, there was a spike in both fouls and shots during the 40-45th minute, further supporting this correlation. Overall, the findings suggest a connection between shot attempts and fouls in a game.
