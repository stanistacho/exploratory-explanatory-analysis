# Prosper Loan Data - exploratory and explanatory analysis
## by Stanislava Stachova


## Dataset

The dataset consists of detailed information about Loans provided by Prosper. Dataset consists of nearly 114 thousand observations and 81 features providing specific Loan info. The definitions of each feature is listed in separate file, Prosper Loan Data - Variable definition.


## Summary of Findings

> Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.

In order to acquaint myself with the dataset I decided to focus on two main parts, as follows:
 __Lender area__ (Term conditions, Loan status, Lender Yield, Rating/Score, Loan original amount, Listing categories);
 __Borrower area__ (Borrower Rate/APR, Borrower State, Employment status, Employment status duration, Income Range, Debt to Income Ratio, Recommendations).


__RELATIONSHIP BETWEEN 2 VARIABLES:__

__Relationship between Loan Amount and Borrower rate:__ According to expectation, the correlation between these two variables is negative.

__Relationship between Loan Amount and Term conditions:__ There is weak correlation relationship. Loans for short term period seem to have lower amount( up to 10 thousand). Some points show higher amounts (20 and 25 thousand) - possibly outliers. The periods of 36 and 60 seem to be comparable. Higher loan amounts are dedicated to longer period.
    
__Relationship between Loan Amount and Income Range:__ The plot seems reasonable, the mean increases in line with increase in income. I noticed that peaks in distributions probably refer to standard loan amounts (5,000; 10,000; 15,000, 25,000). 

__Relationship between Income Range and Term conditions:__  Based on the heatmap, we may conclude that, the most number of loans were borrowed for 36 months period to borrowers from income range USD 25,000-49,999 followed by income range USD 50,000-74,999. The smallest number of loans were borrowed for 12 months period to borrowers from income range USD 1-24,999.

__Relationship between Loan Amount and Listing Category:__ The lowest median value is seen in Student use, Personal Loan and Vacation assuming that only small value loans are popular. This assumption is supported by distribution on the graph, which is quite high around median (lower than USD 5,000). The highest median value is seen in Debt Consolidation (higher disttribution around standard Loan amounts as of USD 5,000; USD 10,000 and USD 15,000) and Wedding Loans.



__RELATIONSHIP BETWEEN 3 OR MORE VARIABLES__

__Relationship between Loan Amount, Borrower Rate/APR and Lender Yield:__ Based on the heatmap, we see negative correlation between Borrower rate/APR and Loan Amount, supporting the general knowleadge, that high amount of the loan is connected to lower interest rate. We may see strong positive correlation between Borrower rate and Borrower APR as these are comparable variables. Both variables then correlate to Yield, as it is actually borrower interest rate but without service fee. 

__Relationship between Loan amount, Listing category, Borrower Rate:__ There is negative correlation between Loan Amount (within each listing category) and Borrower Rate. The highest median value is seen in Debt Consolidation (higher distribution around standard Loan amounts as of USD 5,000; USD 10,000 and USD 15,000) and Wedding Loans.The lowest median value is seen in Student use, Personal Loan and Vacation assuming that only small value loans are popular. This assumption is supported by distribution on the graph, which is quite high around median value (lower than USD 5,000)


__Relationship between Income range, Listing Category and Loan amount__: I have selected three biggest categories within Listing Category (Debt Consolidation, Other and Home Improvement). The highest loan amount is borrowed by borrowers from income range USD 100,000 within a listing category Other.


## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.

I have decided to present relationships between 2 variables. Therefore I plotted only univariate plots to present basics about selected variables within Dataset and bivariate plots to demonstrate relationships between variables. Only relationship between Loan amount, Borrower rate/APR and Lender Yield remain as it is expressed via correlation matrix, easily to understand.

The reason behind is that it would be quite difficult to vizualy analyse plots with more than 2 variables during the presentation. Even though, the graphs are a bit complicated or perhaps unknown for audience.


Due to this reasons I adjusted the goal and set assumptions for my investigation as follows:

The goal of the investigation is to analyse following relationships and prove or disprove the assumptions:

* Relationship between Loan Amount, Borrower Rate/APR and Lender Yield   
* Relationship between Loan amount and Listing category  
* Relationship between Income range and Loan amount
* Relationship between Income range and Term conditions
 
Assumptions:
* _Assumption: I expect that Borrower rate/APR/Lender Yield will have negative correlation with Loan amount._
* _Assumption: I expect that high Income range clients obtain higher Loan Amount._
* _Assumption: I expect that the reason for loan borrowing, determine how large Loan Amount will be._
* _Assumptions: I expect that lower loan amounts are agreed for shorter period and higher Loan amounts are agreed for longer period of time._


