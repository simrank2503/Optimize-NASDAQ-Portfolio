# Portfolio Optimization using Integer Programming

## Project Overview
This project focuses on constructing an index fund with a limited number of stocks to track the NASDAQ-100 index. The approach involves formulating an integer program for stock selection and a linear program for determining portfolio weights, and also by Mixed Integer Programming and comparing them. The performance of the index fund is then evaluated based on out-of-sample data. The project explores different scenarios by varying the number of stocks included in the portfolio.

## Deliverables
1. **Python Code File:** Python code file containing well-documented code, analysis, and visualizations, utilizing packages like Pandas, Numpy for database, Gurobi for optimization of Linear Programming and Mixed Integer Programming, and Matplotlib, Seaborn for data visualization
3. **PDF Report:** A comprehensive PDF report detailing the problem, solution approach, results, and analysis, including relevant graphs and code snippets.

## Problem Overview
The project starts by selecting a subset of stocks from the NASDAQ-100 index using an integer program based on a similarity matrix. The next step involves solving a linear program to determine the optimal weights for the selected stocks in the portfolio. The portfolio's performance is then evaluated against the NASDAQ-100 index using out-of-sample data.

## Specifics
1. Utilize daily price data from two CSV files for 2019 and 2020, containing the index and component stock prices.
2. Start with m=5 and identify the best 5 stocks for the portfolio with corresponding weights using 2019 data. Evaluate the portfolio's tracking performance in 2020.
3. Repeat the process for m = 10, 20, ..., 100, and analyze the portfolio's performance for each value of m. Investigate potential diminishing returns with increasing stock inclusion.
4. Introduce an alternative approach by formulating the weight selection problem as a Mixed Integer Program (MIP). Compare its performance against the original method for 2020 data, limiting the optimization time for each value of m.
5. Provide recommendations to a hypothetical mutual fund, considering the analyzed data and results. Include visualizations to present key points clearly.


