# NBA Shot Predictor

This report will detail the usage of statistical
learning methods to predict whether a basketball shot is made
or missed in the 2014-2015 NBA season. We will attempt to
predict the result based on information about the game scenario
at the time of the shot.

## Introduction
The usage of data analysis to influence decisions in basket-
ball analytics has increased in popularity exponentially over
the past few years. This trend is due to two main reasons.
First being the increased hardware process in handling big
data tasks. The second is the advent of advanced play-by-
play detection technology facilitated by a camera system
hung from the rafters collects data on the movements of
each player. Now that teams are able to gather a plethora
of detailed and descriptive data, they are shifting to relying
more on statistical and quantitative measures to influence
game time decisions.

Obviously, the objective of basketball is to score more
points than your opponent. The point of this analysis is to
determine whether we can build a model that can predict
whether a shot will fall or not based on advanced data
gathered by the SportsVU camera system mentioned above.
A model that can do this provides invaluable information to
the coaching staff of a team about how the conditions of the
game at the time of the shot influences the outcome of the
shot.

## Data Source
The data we will be looking at shot log data gathered from
the SportsVU camera systems for every game spanning a
majority of the 2014-2015 NBA season, from Oct 2014-Mar
2015. The data was taken from https://www.kaggle.
com/dansbecker/nba-shot-logs/home,
which
compiled this dataset by using the NBA API. The reason
we are looking at data from the 2014-2015 season is that
the NBA API stopped providing this data permanently after
the 2015 season due to cost concerns.

