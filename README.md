# Communicate Data Findings

## Dataset
* This dataset is about loans and the status of the loans as well as the borrowers.

## Prosper Loan Data
113,937 observations with 81 features. I.e. 113,937 rows by 81 columns.

Main features are: CreditGrade, BorrowerAPR, BorrowerRate, EstimatedLoss, EstimatedReturn, ProsperScore, ListingCategory, BorrowerState, EmploymentStatus, IsBorrowerHomeowner, CreditScoreRangeLower, CreditScoreRangeUpper, CurrentCreditLines, OpenCreditLines, InquiriesLast6Months, TotalInquiries, CurrentDelinquencies, DelinquenciesLast7Years, IncomeRange, IncomeVerifiable, and StatedMonthlyIncome.


Features that I think will help support my investigation into my features of interest: CreditGrade, BorrowerAPR, BorrowerRate, EstimatedLoss, EstimatedReturn, ProsperScore, ListingCategory, BorrowerState, EmploymentStatus, IsBorrowerHomeowner, CreditScoreRangeLower, CreditScoreRangeUpper, CurrentCreditLines, OpenCreditLines, InquiriesLast6Months, TotalInquiries, CurrentDelinquencies, DelinquenciesLast7Years, IncomeRange, IncomeVerifiable, and StatedMonthlyIncome.

* Surprisingly almost has a normal distribution with a couple peaks and a really large peak between 0.3 and 0.4 in Borrower APR Distribution.

* The estimated loss is definitely right skewed with a few peaks.

* Estimated Return is actually almost normally distributed.

* Probably the closest we have to a normal distribution.

* In Category (numeric) Distribution was interesting in the sense to see other observations besides only Debt Consolidation.

* Unsurprisingly, in Borrower State Counts, most of the borrowers are from California. What is suprising is that Texas is next on the list.

* As being ordered by counts per state borrowing, it is very interesting to see that the states with less counts of borrowing have higher APR. Not huge increases but a slow trend. Except for a couple outliers such as IA and ME.

* Why would it be that part-time has the lowest APR? It seems rather unethical to prey on not employed by charging more APR under the pretense of higher risk.

* We have already discussed not employed so we will skip that part. Also, it seems self-explanatory that employed status would have the lowest estimated loss. Interesting though that retired would have second highest estimated loss when retired people can not get fired/let-go.

* It would make sense that as the estimated loss raises so does the APR, not dependent on employment status. Speaking on that, however, where someone is employed (self-employed, employed, full-time) there is much more variance, most likely because lenders are more lenient sense they can trust the borrower more.

* For the most part, being a homeowner does not directly impact your APR. However, in some states, if you are a homeowner, it is possible to get a lower APR; in other states, if you are NOT a homeowner then you can get a lower APR.

## Author
* [David Capella](http://davidcapella.com)

