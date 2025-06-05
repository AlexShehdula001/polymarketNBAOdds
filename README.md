Goal:
Use historical time series data to perform real time predictions on live NBA game betting odds on Polymarket. Identify possible points of overreaction by fans to profit from back and forth scoring behaviour. Also acts as a way to practice time series data manipulation, API calls, visualizations and forecasting. 


Process:
API Connection:
Establishes a connection to the Clob and Gamma Polymarket APIs to retrieve historical and real-time time series data using the requests library.

Data Preprocessing:
Filters for NBA games, cleans erroneous values, and creates additional columns required for downstream analysis.

Data Storage and Visualization:
Extracts and stores cleaned data for specific teams or games in history objects. This data can then be visualized to observe trends over time.

Statistical Analysis:
Calculates median values for betting odds intersection points per team and league per game. Plots the distribution to check for normality.

Behavioral Insight:
Combines statistical results with other indicators—such as signs of close or lopsided games—to identify moments when viewers likely overreact to scoring runs or sudden point swings.

Future steps:
Refactor code to be cleaner functions.
Recomment the code for other developers to better understand.
Build one or two mock examples/use cases along with a report.
Create a main loop that can be used through a UI.
Expand to other types of markets (other professional sports would be most likely to have similar trends)
Account for outside of match factors (player injuries, momentum in series, coaching staff changes etc.) 

