# How do the number and timing of shots and fouls vary across different European leagues (Italy, England, France), and what patterns emerge when comparing these leagues?
We looked into 3 different European countries (Italy, England, France) and look into the relationship between fouls and shots attempted. After looking into the 3 different countries, we looked for a relationship within the countries and also compared the 3 countries between each other. (Final Findings at the bottom)

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
### Relationship between Late Game Fouls/Shots vs Team
<img width="1024" alt="image" src="https://github.com/user-attachments/assets/dde95472-8bf8-472b-af39-793589cd6cb3">
The left graph illustrates the foul and shot densities per team during the late game. The right graph compares shot density to foul density for each team in the same period, with a threshold set at 0.33. In both graphs, fouls and shots are mostly distributed evenly around the threshold.

### Relationship between Late Game Foul/Shot density w/ Match
<img width="1038" alt="image" src="https://github.com/user-attachments/assets/eb1eada7-50aa-4c69-b9d2-aa603dd21696">
The left graph displays foul and shot densities per match during the late game. The right graph compares shot density to foul density per match in the same period, with a threshold of 0.33. In both graphs, the foul and shot densities exceed the threshold.

### Relationship between Early Game Fouls/Shots vs Team
<img width="1038" alt="image" src="https://github.com/user-attachments/assets/d3657dde-0691-4494-b86a-3bdc4c158d48">
The left graph shows foul and shot densities per team during the early game, while the right graph compares shot density to foul density for each team in the same period. The threshold is set at 0.66, with most fouls and shots distributed above this threshold in both graphs.

### Relationship between Early Game Foul/Shot density w/ Match
<img width="1038" alt="image" src="https://github.com/user-attachments/assets/0ab4e598-8ea6-46d7-b07b-a2b1aeeb2be3">
The left graph illustrates foul and shot densities per team during the early game, while the right graph compares shot density to foul density for each team in the same period. The threshold is set at 0.66, with most fouls and shots falling below this threshold in both graphs.

### Shots/Fouls by the Minute
<img width="1038" alt="image" src="https://github.com/user-attachments/assets/eb60472f-36d5-4742-97a6-e4a0e53cadce">
The left graph displays the number of shots over the minutes of the game, while the right graph shows the number of fouls over the same period. Both graphs indicate that the peak for shots and fouls occurred between the 40-45 minute mark.

### Average Late Game Foul/Shot density by Team
<img width="1038" alt="image" src="https://github.com/user-attachments/assets/707b9732-3bfd-486d-8e2a-150a6ba566cc">
These graphs are converted from scatter plots to bar graphs to help identify additional patterns or relationships between shots and fouls. As observed, the shot and foul densities follow similar patterns in both graphs, though the relationship between them remains weak.

### Average Early Game Foul/Shot Density by Team
<img width="1027" alt="image" src="https://github.com/user-attachments/assets/6cd1bf64-da68-4318-80cf-8a0973512351">
The shot and foul graphs reveal that shot density follows a similar trend to foul density in the early game. However, the relationship between the two remains weak.

### France Conclusions
Our analysis of shots and fouls during games revealed a correlation between the two. When comparing early and late game densities, we found that in the early stages, both shots and fouls were less frequent, more evenly distributed, and often below the threshold. In contrast, the late game showed a higher density of shots and fouls, with many data points exceeding the threshold, indicating a possible relationship between shot attempts and fouls by team. Notably, there was a spike in both fouls and shots during the 40-45th minute, further supporting this correlation. Overall, the findings suggest a connection between shot attempts and fouls in a game.

## England 🏴󠁧󠁢󠁥󠁮󠁧󠁿
### Distribution of Events Over Time
<img width="1035" alt="image" src="https://github.com/user-attachments/assets/04f77bad-484a-4d05-906d-993347c47314">
Events (shots and fouls) are most common around the end of the first half and beginning of the second (40-50 min). We see a slow buildup in events up until that mark and then a slow decline up until a quick rise in events towards the end of the game (80-90 min). We can also clearly see that teams take more chances in the second half compared to the first. The graphs between the shots and fouls in games are very similar and would likely have a high correlation to each other. 

### Event Densities Late Game vs Early Game per Match
<img width="1035" alt="image" src="https://github.com/user-attachments/assets/647cf946-f0b9-488f-9986-f5922cd927a4">
Teams tend to favor late game shots than early game shots. This could be because teams focus on reading the defense and working on build-up play during the beginning of games and during late games they try to go out there and win it. We can also slightly see teams tend foul later in the games and play more conservatively during early game. We see outliers in all four of the graphs which could have interesting stories behind them.

### Event Densities Late Game vs Early Game per Team
<img width="1035" alt="image" src="https://github.com/user-attachments/assets/2d2994f9-6adf-46e5-b4b8-fa6bc42029fe">
From these graphs we can see which teams favor which playstyle. Some teams favor early game play which others favor late game play. These numbers can also show us what circumstances these teams are in during early and late games. Like for example teams that take more shots or foul more late game (Burnley) are usually losing and need to take risks to get points back in the game.

### Relationship between Early Game Fouls/Shots per Team
<img width="1041" alt="image" src="https://github.com/user-attachments/assets/a6cfb483-83be-43ec-af73-ac3a28881d04">
The left graph compares the density of early game shots (red dots) and fouls (blue dots) for different EPL teams. For most teams, fouls (blue) tend to have a higher density than shots (red). This suggests that teams are more likely to commit fouls than take shots in the early stages of the game. Some teams, like Brighton & Hove Albion and Watford, are on the upper end, where both shot and foul densities are the highest. There is some variability among teams, with clubs like Bournemouth and Arsenal showing a smaller gap between fouls and shots. The scatter plot on the right shows how early game shot density correlates with foul density for different EPL teams. Brighton & Hove Albion has the highest density of both shots and fouls, indicated by the top-right positioning on the graph. Bournemouth and Burnley have relatively lower values for both shot and foul densities, as shown in the bottom-left corner. There is no clear direct correlation between shot and foul density for the teams; however, teams with higher foul densities, like Albion and Watford, tend to also have higher shot densities.

### Early Game Event Densities Shots vs Fouls
<img width="1041" alt="image" src="https://github.com/user-attachments/assets/9a3d4029-1680-4bdc-9d97-66bc6c740cbe">
The left graph shows early game densities for fouls (red dots) and shots (blue dots) across various EPL matches. The most common range for both shots and fouls in early game densities appears to be between 0.2 and 0.4, suggesting that a majority of games see similar activity levels in the early stages. The scatter plot on the right shows a correlation between early game shot and foul densities for various matches. We can see that very few games reach very high foul densities early game, with the maximum being around 0.65. The majority of matches have early game shot and foul densities between 0.2 and 0.4, reinforcing that this is a common range for early game action across the board.

### Relationship between Late Game Fouls/Shots per Team
<img width="1041" alt="image" src="https://github.com/user-attachments/assets/cad636dc-96e6-4847-8df2-a683c836870d">
The left graph shows the comparison of late game shot density (blue dots) and foul density (red dots) across various EPL teams. For most teams, foul density and shot density are fairly close, with no major gaps between the two for most teams. Liverpool, Everton, and Burnley have relatively higher foul densities compared to their shot densities. Albion and Bournemouth are notable for having relatively lower densities for both fouls and shots. The highest late game activity in terms of fouls and shots is observed in Burnley, while Albion shows the lowest activity in both categories. The scatter plot on the right represents the correlation between late game shot density and foul density for different teams. Teams like Burnley and Watford are positioned on the far right, indicating high late game densities for both fouls and shots. Brighton & Hove Albion shows the lowest values for both metrics, placed in the bottom-left corner. Similar to the early game graphs, there does not appear to be a strong correlation between shot and foul densities, as teams with high foul densities (e.g., Burnley) do not necessarily have proportionally high shot densities. There is a general clustering around a moderate range (0.36 to 0.40) for both shots and fouls, meaning most teams have somewhat similar late game activity levels.

### Late Game Event Densities Shots vs Fouls
<img width="1041" alt="image" src="https://github.com/user-attachments/assets/3ee871f5-bb3a-40f7-b3e5-106b612ce638">
The graph on the left shows late game densities for fouls (red dots) and shots (blue dots) across various EPL matches. The most common range for both shots and fouls in early game densities appears to be between 0.3 and 0.5, which is higher when compared to the early game event density graph. The scatter plot on the right shows a correlation between late game shot and foul densities for various matches. We can see that two games which are outliers reaching very high foul densities late game, with the maximum being around 0.77.

## Italy 󠁧󠁢󠁥󠁮󠁧🇮🇹
<img width="1052" alt="image" src="https://github.com/user-attachments/assets/d467a263-d895-4e61-900f-78ef0a6ee5bb">

<img width="1052" alt="image" src="https://github.com/user-attachments/assets/2114d119-2a86-43a8-971c-4307fcb2507b">

### Italy Conclusions
- By team: nearly half Serie A teams exhibited extra aggressiveness by late game 
  - Around 40% fouls committed and 36% shots attempted committed in the last 33% of the game

- By Match: as a League, Serie A shows great aggression 
  - Matches consistently show a greater spread of around 37% -50% of all shots and fouls within the last 33% of the game 
  - See Fig. i.7

- Shot vs. Density correlation: there seems to be a weak but present correlation to the fouls committed to the shots committed 
  - Late game fouls and early game fouls cluster above the lines of normalcy 
  - See Fig i.8

# Findings/Conclusion
Football/soccer is a very diverse sport with many different styles of play. There are various factors that go into this from coaching tactics to changing playstyles based on opponents. We can see distinct approaches to the beautiful game from teams just 10 km from each other let alone different nations. Through an in-depth analysis of fouls and shots across three major European leagues (Italy’s Serie A, England’s Premier League, and France’s Ligue 1), we identified several key findings. 

### Trends Between All Three Leagues
- Across all three leagues, shots and fouls tended to increase as games progressed, particularly in the final third (post-60 minutes). This is likely due to teams taking more risks, seeking to score, or prevent goals as time runs out. The late game intensity reflects a heightened sense of urgency, especially for teams that are trailing in the scoreline.
- All three leagues showed a notable peak in both fouls and shots just before halftime (40-50 min range). This suggests that players push harder towards the end of the first half, likely driven by the desire to score before the break.
- There is a slight correlation between fouls and shots. Teams that commit more fouls late in the game tend to also take more shots, indicating a more aggressive style of play as the match nears its conclusion.

### Country-Specific Patterns
France: Teams were relatively balanced in their distribution of fouls and shots across both the early and late stages of the game, with a slight increase in late-game activity. However, the overall densities were quite evenly spread, with no significant outliers. Ligue 1 teams also tend to play conservatively in the early stages, focusing on maintaining control before ramping up aggression later in the game.

England: The Premier League exhibited a clear pattern of teams favoring late-game shots, with a tendency to play more conservatively in the early stages. Some teams, were more likely to foul and take risks in the late game, possibly due to being in losing positions. A slow buildup of events was observed in the first half, followed by a burst of activity around the 40-50 minute mark and a final surge towards the end of the game (80-90 minutes). This reflects the intense nature of EPL matches, where teams frequently alter strategies as the game unfolds.

Italy: Serie A demonstrated a particularly aggressive style, with almost half of the teams showing significantly higher densities of fouls and shots late in the game. Nearly 40% of fouls and 36% of shots occurred in the last third of the game. Italian teams are known for their tactical focus, and this aggression likely reflects a shift towards counterattacks and defensive intensity as matches approach their climax. Teams adapt dynamically based on the game situation, emphasizing the need for precision in late-game management.

### Implications
This study offers practical insights for teams, coaches, and analysts to improve strategies based on how fouls and shots vary throughout a game. Teams can adjust tactics, knowing when players are more aggressive or take more risks, and coaches can fine-tune training. The data can also be used for better match predictions, scouting, and even in fantasy football (soccer) for player selection. This data can also be useful for referees as they could use these trends to anticipate high-foul moments and make more informed decisions during games.

### Further Improvements & Questions
This study focused on three countries, allowing us to compare and contrast the soccer games in terms of fouls and shots. To enhance the project, we would expand the analysis to include more countries and possibly different leagues, providing a broader basis for comparing fouls and shots. Additionally, incorporating more metrics—such as goals scored, types of fouls (red/yellow cards), foul locations, and more—would lead to stronger, data-driven conclusions. One key question for further exploration is whether there is a relationship between fouls committed by winning or losing teams, and how this could impact predictions of the game's outcome.

### Thank you!
- Andres Gutierrez, Twesha Ghosh, Karthik Valluri





