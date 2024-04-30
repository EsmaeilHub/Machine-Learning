# March Madness 2024
#### Here is the steps to tackle this dataset:
- WinTeam is considered as team A and LTeam as team B
- The goal is to predict if A beats B
- Value 1 is assigned to the y for actual winners in the dataset
- The related values of the winning team are switched with the losing teams and set to zero for y
- The data related to years from 1985 to 2023 are considered as training and 2024 as testing
- Logistic Regression is used first for feature selection and then for classification
- Teams in different regions are randomly seeded. Then, losers are removed and winners are seeded for the next games until slot R6CH.

### The features defined in this problem are as follows:

- WTeamID: Considered as team A, where y = 1 if it wins
- LTeamID: Considered as team B, where y = 0 if A wins and vice versa
- WNumWins: Number of wins of the last year for team A
- WNumLosses: Number of losses of the last year for team A
- WTeam_grade: Last year relative cumulative sum of the difference between WScore and LScore for team A. Indeed, the score difference is computed first and then the relative cumulative sum is calculated. It is considered relative because some teams may be newer.
- WstdWins: Last year standard deviation (std) of the number of wins over the years for team A. It is measured to differentiate teams that consistently perform well versus those with more erratic performance patterns over time.
- WstdLosses: Last year std of the number of losses over the years for team A.
- LNumWins: Number of wins of the last year for team B
- LNumLosses: Number of losses of the last year for team B
- LTeam_grade: Last year relative cumulative sum of the difference between WScore and LScore for team B.
- LstdWins: Last year std of the number of wins over the years for team B.
- LstdLosses: Last year std of the number of losses over the years for team B.
- 
## Note: For more brackets, adjust the NUMBER_OF_BRACKETS variable to your preferred value.
