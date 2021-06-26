# NBA-Data-Science
This repo contains a A  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) project made by **Yarden Ankonina** and **Alon Sapozhnikov** in a data science class in Holon Institute of Technology, analyzing NBA player's stats and specifically PER (player efficiency rating - by  John Hollinger's ) By using pandas and machine learning in python. <br/>
Extra addition to our project - just for fun [PER calculator](https://yarden-ankonina.github.io/NBA-Data-Science/)<br/>

## Main Purpose
The NBA has a lot of interesting statistics but there is a statistic that combines them all, under the name PER.<br/>
We will use it to estimate the success of the players in their season.<br/>

Our process is defining a research question ->  Web Crawling - >  Data Cleaning - > Visualisation - >  Machine Learning<br/>


Can we predict a player’s PER using machine learning based on his stats?<br/>
Can we predict a player’s PER in his next year using machine learning based on his stats?<br/>
Can we predict the 2021-2022 MVP of the year based on PER?<br/>


## Web Crawling
We got our data from : <br/>
[basketball-reference](https://www.basketball-reference.com/leagues/NBA_2021_totals.html)<br/>
[basketball-reference](https://www.basketball-reference.com/awards/mvp.html)<br/>
[wiki](https://en.wikipedia.org/wiki/Player_efficiency_rating)<br/>
Using beautiful soup Library


## Data Cleaning
Remove missing data.<br/>
Fill missing values.<br/>
Handle outliers<br/>
Format columns<br/>



## Visualisation

We visualize our data and then analyze it to try to learn more about it.<br/>
We will use seaborn, matplotlib visual libraries<br/>

## Machine Learning
Using sklearn with linear regression algorithm  to try to : <br/>
Predict a player’s PER based on his stats<br/>
Predict a player’s PER in his upcoming year based on his stats (Future PER)<br/>



