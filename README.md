# Arınç Eskicioğlu DSA 210 Project
arinc.eskicioglu34320dsa210project

# Project Proposal
The UEFA Champions League (UCL) is the most prestigious club competition in world football. While pundits often analyze a team's success based on luck or individual player quality, a deeper understanding requires a data-driven, historical perspective. To truly define the drivers of success and failure in the UCL, this project will analyze the statistical patterns, results, and trends that have emerged over decades.

My motivation for this topic stems from a desire to challenge common narratives. This project moves beyond a simple "who won" analysis to investigate the 'how' and 'why' behind historical outcomes. It operates on the hypothesis that success in elite sports is not purely a matter of coincidence, nor is it solely dictated by financial power, as is often assumed. Rather, this project seeks to demonstrate that UCL success is the measurable result of effective tactics, consistent on-pitch performance, and superior statistical profiles.

By exploring the patterns of teams that successfully navigate the tournament versus those that fail, this project will attempt to identify the tangible, data-backed markers of a championship-caliber team.


# Data to be used
Generally, I am using data from 
- https://fbref.com/en/comps/8/history/Champions-League-Seasons
- https://www.transfermarkt.com/uefa-champions-league/teilnehmer/pokalwettbewerb/CL
- https://www.uefa.com/uefachampionsleague/


- Countries of the teams and teams qualified for round of 16
- The amount of wins and losses of the winner team in the group stage
- total goal each team scored and total goal scored against them
- the points each team collected in group stage
- expected goals and expected goals allowed by each team, also expected goal difference per 90 mins for each team
- market value of every team in each seasons
- in which step the teams elimined and the amount of goal difference causing them eliminated
- in which step the eliminating them eliminated


# Problems
- A potential bias arises when a strong team (Team A) is eliminated early, for instance in the Round of 16, simply because they faced the tournament winner. Although the champion is theoretically the strongest opponent, our current scoring system penalizes Team A for this early exit. Consequently, Team A is underrated; their true performance quality may be much higher than their final ranking suggests. Isolved that problem thorugh giving a weighted sum to the elimination step. The success in knockout phase is calculated as (5 * Eliminated phase + 2 * the elimintaion sted of the team eliminitanig them - score difference). This seems to be fair to me.
- Also there is a problem in conducting t-test and linear regreesion. The teams that get eliminated in group stages has no success in knockout phase. However it does not mean they were bad at those stages since they did not have the chance. It affected the linear all the parts in my study directly. I found out how to solve that in different ways. I'll come to that when I mention them.



# Questions
- How many teams do each country have in champions league and how many of them were able to? which country is the most successful?
- Is there a significant difference between a team eliminated in round of 16 and a finalist team in group stages? or in other words - What makes the difference between the champion and a just good team?
- Was the winner team always the best in group stage?
- What statistics make a team best in the group stage or in two leg system?
- How much valueable is a team need to be and does it always work?

