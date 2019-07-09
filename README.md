# noahgift-nba-example
Code and Data for the Pragmatic AI Book



## Steps

1. Create the requirements file
1. Create the makefile
1. Run: `make setup` and then `make install` if it does not work, then run on command line
1. Go to: https://www.basketball-reference.com/leagues/NBA_2017_advanced.html to get the NBA data
1. Start Jupyter Notebook in the command line: `jupyter notebook`
1. Run the following code:
```
import pandas as pd
nba=pd.read_csv("data/nba-per-game-2017.csv")
nba.describe()
```
1. ... depending on time on Tuesday, or maybe an assignment to follow the instructions from the book
