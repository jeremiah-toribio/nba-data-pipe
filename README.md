# NBA Data Pipeline

---
## Project Description
### Creating a data pipeline & dashbaord to retrieve NBA statistics and key data driving insights. Our primary objective is not so much in the predictions aspect but rather provide another feature for analysis based on model results. Analysis will be key.
+++++++++++++++++\
\
**Overview:**\
The purpose of this project is primarily to test skills such as containerization, web scraping, data architecting, ETL, analytics and more. Of course the outcome is equally important. Hoping to see concurrent data regarding NBA games and player individual stats from separate tables. \
**Method**\
Containerization, API, Data Pipelining, Data Architecting, ETL, Sports Analysis, PostgreSQL, Classification
**Takeaways**\
TBD.\
**Skills:**\
Docker, Python, Cron, JSON, Dataframes, Pandas, Extract Transform Load, Tensorflow, Classification, Decision Tree, Random Forest, Dashboard

## Project Goals
---
1. Correct utilization of Docker containers
2. Extract, Transform and Load data from NBA-API
3. Automatic updates to front end side
4. Indepth NBA player analysis and insights

## Initial Thoughts
--- 
- Finding key drivers that lead to wins would be beneficial when attempting to model for to predict game wins
- Creating an accurate data set could prove useful for other community members that could deliver insights

## Planning
--- 
1. Acquire data NBA-API
2. Format for analysis
3. Explore and analyze data for key insights that lead to victories\
    a. Determine our baseline prediction (this could be a prediction from book keepers)\
    b. Are we beating the auction house's estimates?\
    c. Does logarithmically transforming player stats translate to better model analysis?
4. Build dashboard that has custom analytics tailored per front-end user
7. Publish dashboard to front-end website

## Data Dictionary
### players (table)
--- 
| Feature        | Definition                                   |
| ---            | ---                                          |
| id | a unique identifier |
| season | the season that the data entry is relative to |
| player | player first & last name |
| team | associated team |
|  |  |
|  |  |
|  |  |

### game (table)
| Feature | Definition |
| gameid | a unique identifier |
| team1 |  |
| team2 |  |
| location |  |
| winner |  |
| mvp |  |

## Reproducability Requirements
---
These will be detailed in both the Dockerfile and docker-compose.yaml
