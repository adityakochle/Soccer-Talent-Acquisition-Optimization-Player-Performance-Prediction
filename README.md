**Executive Summary-Soccer Squad Optimizer**

Problem Statement: 
To create an optimized soccer squad while adhering to a strict budget constraint, considering player ratings and the maximum number of players.

Model Overview:

Part-1
This Excel-based model provides a solution to the challenge of selecting the most optimal soccer squad while minimizing budget. 
It incorporates a user-friendly interface that allows for flexible input of desired squad size and player rating parameters. 
The model then leverages a robust optimization algorithm to identify the best combination of players that maximizes overall team rating while keeping at minimum the budget.

Key Features and Benefits:
 Efficiency: Automates the player selection process, saving significant time and effort.
 Cost-Effectiveness: Ensures optimal resource allocation by minimizing the total cost of the squad.
 Performance Optimization: Prioritizes players with higher ratings to maximize team performance.
 Flexibility: Can be easily adapted to different squad sizes, budget constraints, and player rating criteria.


Part-2 Player KPI Tool Overview
Once the output from Part 1 is derived, it's crucial to evaluate whether the chosen player has the potential to improve and perform consistently year over year. 
This is where the Player KPI (Key Performance Indicator) tool comes into play. 
The tool performs a detailed evaluation of players based on various parameters, including positive metrics and discipline-related factors.

Key Metrics for Evaluation
1. Positive Metrics:
 Goals Scored per 90 minutes: This metric helps assess the player's scoring ability.
 Assists Made per 90 minutes: This metric evaluates the player's ability to support teammates in scoring.

2. Discipline and Temperament:
 Suspensions or Warnings per 90 Minutes: This metric measures the player's disciplinary record, which is crucial for maintaining team stability.
 Cards Accrued Over Time: Tracking the number of yellow and red cards received can indicate changes in a player's behaviour and discipline as they age.

Importance of Discipline Metrics
A player with high ratings but poor discipline can be detrimental to the squad due to frequent suspensions. 
By measuring the number of suspensions or warnings per 90 minutes or over a season, the tool helps identify players who may pose a risk to team stability. 
It's noted that players often become more composed as they age, leading to fewer disciplinary issues.

Calculation Period
The values are calculated over a 90-minute period to capture performance trends that may change due to various factors such as injuries or disciplinary issues. 
The industry standard for measuring player performance is per 90 minutes.

Tool Usage
The Player KPI tool can be used multiple times, and the outputs are consistent provided the inputs remain the same.
This ensures reliability in the evaluation process.

Inputs Required
1. Player Index: Derived from the optimized squad selection in Part 1.
2. Expected Goals per 90 Minutes: Typically ranges between 0 and 1. For players rated 80-85, the mean value is 0.3-0.5, with outliers like Lionel Messi ranging from 0.8 to 1.1.
3. Expected Assists per 90 Minutes: Also ranges between 0 and 1. For players like Luka Modric, this could be between 0.5-0.7.

Simulation Process
Once the inputs are provided, the tool runs 1000 simulations for goals/90, assists/90, yellow cards/90, and red cards/90. 
From these simulations, the following values are derived: 
1. Mean, Standard Deviation, Min, Max Values: These statistics provide a comprehensive view of the player's expected performance.
2. Count of Number of Trials: Indicates the number of simulations run.
3. 5th and 95th Percentile Values: These percentiles help understand the range within which the player's performance is expected to fall.
4. Visualization of Expected Performance: Graphical representation of the player's performance metrics.

By incorporating these inputs and running simulations, the Player KPI tool provides a comprehensive evaluation of each player's potential to improve and perform consistently, ensuring a well-rounded and disciplined squad.

Conclusion:
The Soccer Squad Optimizer and Player KPI Tool provide a comprehensive and efficient solution for optimizing soccer squad composition and evaluating player performance. 
The Excel-based model automates the player selection process, ensuring cost-effectiveness and performance optimization within budget constraints. 
The Player KPI Tool further enhances decision-making by evaluating players' potential for improvement and consistent performance, considering both positive metrics and discipline-related factors. 
Together, these tools offer a robust framework for making informed decisions, ultimately leading to a more effective and cohesive team.
