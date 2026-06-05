#### SeriousDlqin2yrs 
    -> did the person default within 2 years
   - Delinquency :> means the failure to pay the money back -> less serious
   - default -> means the failure to pay the money back  -> more serious


#### RevolvingUtilizationOfUnsecuredLines 
    -> How much of their credit card limit are they using?

what is credit card?
    For a data-science or credit-risk interview, I'd say:

A credit card provides a revolving credit limit that a customer can borrow against repeatedly. The customer repays the borrowed amount later, and interest is charged only if the balance is not paid in full by the due date.

That's the essence of it:

Credit limit = maximum you can borrow.
Balance = amount currently borrowed.
Utilization = balance ÷ credit limit.
Interest = charged if the balance isn't fully repaid on time.


#### age
age of the person

#### NumberOfTime30-59DaysPastDueNotWorse
Times they were 30-59 days late on a payment

#### DebtRatio
what % of their income goes to paying debt


#### MonthlyIncome
Salary of the person in dollars

#### NumberOfOpenCreditLinesAndLoans
how many active loans/credit cards they have

#### NumberOfTimes90DaysLate
times they were 90 days late 

#### NumberRealEstateLoansOrLines
how many mortgages or home loans they have

#### NumberOfTime60-89DaysPastDueNotWorse
times they were 60-89 days late

#### number of dependencies
how many people depend on them



Phase 1: SQL          → Load data into SQLite, explore with queries
Phase 2: Python EDA   → Clean data, find patterns, visualize
Phase 3: ML Model     → Build & evaluate prediction model
Phase 4: Storytelling → README + charts that tell the business story


Here are the questions we want to answer visually:

How many people actually defaulted? — Are defaults rare or common in our data?
Does age affect default risk? — Your hypothesis earlier
Does being late on payments affect default? — Your instinct was right, let's prove it visually
Does income affect default? — Richer people default less?
Does debt ratio matter? — High debt = high risk?


Phase 1: SQL          → ⏳ coming
Phase 2: Python EDA   → 🔄 in progress (just started viz)
Phase 3: ML Model     → ⏳ coming
Phase 4: Storytelling → ⏳ coming