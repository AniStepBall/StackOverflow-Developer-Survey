# StackOverflow developer survey analysis
## Project Overview
This project analyzes a developer survey dataset from StackOverflow to understand the strategies used between developers, see current trends of technology, analyse the different way problem solving stategies by developers finally, what influences certain career decisions.

## Motivation
To understand the scope of 2020 by answering these questions:
1. How did the transition to remote work in 2020 influence devlopers' work-life balance, (e.g., workweek hours and overtime frequency)?
2. What were the trends in adopting new technologies in 2020 across different experience levels?
3. How did developers’ problem-solving strategies change in 2020 due to global events?
4. How do company size and work policies impact developer career satisfaction?
5. How did educational background influence job opportunities and career growth in 2020?

## Libraries Used
* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn

## Repository Structure
* tech-overview.ipynb: Comprehensive Jupyter Notebook
* requirements.txt: Python environment dependencies
* stack-overflow-developer-survey-2020: A zip file that contains the dataset used
* survey_results_public.csv: A 2020 developer survey from StackOverflow
* scenario_prediction.csv: A csv file that contains a list of scenario to predicit thier job satification

## Key Findings
1. How did the transition to remote work in 2020 influence devlopers' work-life balance, (e.g., workweek hours and overtime frequency)?
- The violin plot shows that there were more developers working longer non-remotely compared to developer who did work remotly.
- The is an overall increase of non-remote developers working overtime compared developers working remotely

2. What were the trends in adopting new technologies in 2020 across different experience levels?
- The most used programming languaged used by developers was Bash/Shell/PowerShell.
- In addtion, there are more intermediate developers [i.e., experience in a language less than 15 years] compa to other experience levels.

3. How did developers’ problem-solving strategies change in 2020 due to global events?
- Overall developers visits Stack Overflow that most when they encounter a problem.
- There is around an equal number of those who either panic, meditate or play games.

4. How do company size and work policies impact developer career satisfaction?
- Companies size does have an effects the developers satisfaction towards their career
- There is a correlation between work hours and company-sizes

5. How did educational background influence job opportunities and career growth in 2020?
- Developers with a Computer science major, has the highest number of thoesin each cateogries

## Acknowledgments
* Developer survey data provided by StackOverflow
* Project given by Udacity
