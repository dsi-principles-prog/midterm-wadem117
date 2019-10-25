# Principles of Programming Midterm project

### Data source

This dataset is exported from www.naturalstattrick.com and includes data from every NHL game in the 2018-2019 season. Many of the columns have to do with different categories of shot attempts and scoring chances produced by each team on a per-game basis. A complete list of the variables is included at the end of this document. 

### Motivating question

To what degree do different performance metrics affect goals for and against in an NHL game? 

### Descriptions of variables 

game: lists date and final score of game 

team: team whose stats are listed in row 

toi: total five-on-five ice time for game (time on ice) 

cf: shot attempts for 

ca: shot attempts allowed 

ff: unblocked shot attempts for

fa: unblocked shot attempts allowed 

sf: shots on goal for

sa: shots on goal allowed

gf: goals for

ga: goals allowed

xgf: expected goals for

xga: expected goals allowed 

scf: scoring chances for 

sca: scoring chances allowed 

hdcf: high-danger scoring chances for 

hdca: high-danger scoring chances allowed 

hdsf: high-danger shots on goal for

hdsa: high-danger shots on goal allowed 

hdgf: high-danger goals for 

hdga: high-danger goals allowed

hdsh_percent: high-danger shooting percentage

hdsv_percent: high-danger save percentage 

**repeat “high-danger” columns for mid- and low-danger**

pdo: total save percentage + total shooting percentage

attendance: number of fans attending game 

## Project

Using the data and code you developed for your last assignment, fill out this repo repository so that it:

1. Outlines the problem you have identified and states data source data (in README2.md)
2. Describes the data (in an import notebook)
3. Contains the necessary notebooks to load, test and clean the data, build features, and prep the data for modeling (three notebooks in total, no need to include the EDA notebook).
