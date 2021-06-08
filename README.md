# Thesis2021

New Repo for Spring 2021 Honors Thesis

## Overview

For the University of Minnesota-Twin Cities honors program. I needed to write a thesis of my choosing. Naturally, I chose something sports
related. I decided to use the SportVu NBA player tracking data from the 2015-2016 season to make an Expected Points Added model to 
better evaluate offensive performance than traditional points/assists. 

This model was implemented with an XGBoost framework in python to obtain the probability a team will score zero, one, two, or three points
at any given moment. The inputs for the model were: the x and y locations, speed, and angle of movement of every player and the ball, plus the
current height of the ball. 

One of the striking conclusions that was found was the very high scores of EPA/game for point guards (especially pass-first guards) compared to other positions. This 
could have various reasons behind it but some that are most likely the driving forces are that there could be some inherent bias in the model
that favors these guards and also that passing may be a more variable skill from player to player in the NBA than scoring. 

## Relevant Files

* [ThesisFinalDraft.pdf](https://github.com/JCHampton/Thesis2021/blob/main/ThesisFinalDraft.pdf): Submitted draft of my thesis
* [finalThesisPoster.PNG](https://github.com/JCHampton/Thesis2021/blob/main/finalThesisPoster.PNG): Poster used for the department of mathematics poster session
* [MakeXGBoostModel.ipynb](https://github.com/JCHampton/Thesis2021/blob/main/MakeXGBoostModel.ipynb): Jupyter Notebook where I made and implemented the XGBoost model
* [getEPA.ipynb](https://github.com/JCHampton/Thesis2021/blob/main/getEPA.ipynb): Jupyter Notebook where I used the XGBoost model to get the EPA for each player/team
* [AllEPA.ipynb](https://github.com/JCHampton/Thesis2021/blob/main/AllEPA.ipynb): Jupyter Notebook where I looked at the results of EPA/game on a player/team level

Note: You will notice two other repositories in here. One is by linouk23 that I used to show the player locations. The other is by sealneaward and that is where I actually
obtained all of the data - I couldn't have done this project without his great and helpful repo!

## Advisors

* Main advisor: Mike Wiemerskirch
* Paper readers: Daniel Boley and Andy Hardt

## Questions/Comments/Suggestions?

* Email me at hampt146@umn.edu
* DM me on Twitter [@JHamptAnalytics](https://twitter.com/JHamptAnalytics)

