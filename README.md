# EFL Championship Player Analysis (25/26)
Applied PCA to Championship Players football statistics to reduce and combine player performance metrics, transforming them into a smaller set of PCs and create useful business insights through data analysis.

![Loading Heatmap & Biplots](Loading_Heatmap%20%26%20Biplots.jpg)
<p align="center">
  <img src="Correlation%20Matrix.jpg" alt="Correlation Matrix">
</p>

## Summary of Insights
- PC1 is strongly associated with attacking variables such as Goals, Shots, Shots on Target and Dribbles, while passing-related variables such as Long Balls and Average Passes load negatively. This suggests that PC1 represents an attacking intensity dimension, differentiating direct attacking output with playmaking ability.
  
- PC2 is primarily driven by defensive variables including Tackles, Tackles Won and Interceptions, indicating that this component reflects defensive contribution.
  
- PC3 is associated with variables such as Crosses, Long Balls, Assists and Key Passes, suggesting that it captures playmaking ability, particularly related to passing and chance creation.


## Business Implications
The PCA results suggest three player archetypes. Players scoring highly on PC1 tend to exhibit strong attacking output, those scoring highly on PC2 demonstrate stronger defensive contributions and players with high scores on PC3 show strong playmaking ability.

### Business Application 1: Player Recruitment
A club could use this analysis to identify potential replacements for players who have left the team. For example, when Adam Armstrong departed Southampton F.C his PCA values were used to find players with similar performance metrics. A dataframe was created containing each player’s PCA values for Attacking, Playmaking and Defending. Armstrong’s values were compared to other strikers by calculating the absolute differences and sorting based on PC1, which is most associated with attacking output.





### Business Application 2: Linking Player Performance to Team Outcomes
