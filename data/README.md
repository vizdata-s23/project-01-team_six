# data dictionary

## polls.csv 

|variable         |class | description| 
|:----------------|:-----------|:-----------|
|company        |character | Company Name |
|industry        |character | 		Industry group |
|2022_rank        |integer | 2022 Rank (1 is better than 100) |
|2022_rq        |double | 2022 RQ score. An RQ score is calculated by: [ (Sum of ratings of each of the 9 attributes)/(the total number of attributes answered x 7) ] x 100. Score ranges: 80 & above: Excellent; 75-79: Very Good ; 70-74: Good ; 65-69: Fair ; 55-64: Poor ; 50-54: Very Poor ; Below 50: Critical |
|change        |integer | 	Change in rank from 2021 |
|year        |integer | 	Year for that rank/RQ |
|rank        |integer | 	Rank corresponding to the year |
|rq        |double | RQ score corresponding to the year |


## reputation.csv

|variable         |class | description|
|:----------------|:-----------|:-----------|
|company        |character | Company Name |
|industry      | character |Industry Group |
|name        | character | Name of reputation category (P&S = Product and Service) |
|score        | double | Score for reputation category |
|rank        | integer | Rank for reputation category |

		