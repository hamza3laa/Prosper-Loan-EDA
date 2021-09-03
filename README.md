# Prosper Loan Data Exploration

## Dataset

Prosper is a peer-to-peer lending platform. Borrowers can find competitive rates for personal loans with one, three or five-year terms. Behind the scenes, loans are funded by investors, not Prosper itself. Prosper offers loan rates instantly without affecting your credit score. This dataset is a financial dataset of the loans, borrowers, lenders, interest rates of Prosper or Prosper Marketplace Inc. which is a San Francisco, California based . So in this company you are rthier a borrower or an investor

In this dataset, we are using the data from the Posper to analyse it and trying to find pattern and generate valuable insights and obseravation.


## Summary of Findings

>The data set have large numer of variables which was hard to invistage all at once.In the exploration,the variable of interest is  lender yield & EstimatedEffectiveYield
- EstimatedEffectiveYield distribution  tends to be Truncated or Heart-Cut Distribution , the EstimatedEffectiveYield looks normal distribution with the tails cut off and one out lier near  rate = to 30% .
- For the presentation, I focus on factors  the influence of EstimatedEffectiveYield in ehich is the most important factor for an investor to invest.
>I start by introducing the EstimatedEffectiveYield Distribution and plot numircal and catgorical variable that we think it is affect like 

- CurrentDelinquencies : most of the data around 0 means that low level of Delinquencies gives a good sign for an investor 
- AvailableBankcardCredit : Plot was Right skwed with one peak around 2000 which gives neagtive sign so far for an investor
  and then we invistgate catgorical variables 
- ProsperRating : Seems most of the loans have ranking c,b,a and d which considerd quite good for an investor
- EmploymentStatus : afcting as employed borrowers are the hieghst to recive loans while retired , not emplyed and part time employed borrowers are the lowset among borrowers
- IncomeVerifiable : Also income varfied borrowers are more likely to recive loans than those who does not varfiy thier income
- Borrowers homeowener :seems dose not have signifacnt effect
- pepole with income from 50000- 75000 tends to borrow more than 75000-10000+
> Afterwards, I introduce relation between numircal  varibals ,I found that there was a strong relationship
bewteen estmited effective yield and boorower annul rate. The relationship is approximately linear .

Then we looks into realtion between one numirc(EstimatedEffectiveYield) and one catgorical(Rating)
- Data with Rating HR(highest ranknig) most of its data lies between 20 & 30 % with peak on 30% of EstimatedEffectiveYield.
- Date with Rating AA(lowest ranknig) most of its data lies between 0 & 10 % with peak around 5% of EstimatedEffectiveYield
- In General Higher rating led to higher Estamited effective Yeild on loans .
> Finaly we want to look deeply on our investors prefernces and behaviour interms of loan catgories and loan time plan they choseing (Multi varibales plot)
- first thing i notice here that investors tends to invest in short term plan (12 months) except for tow typs of loans (personal use & student use they invest in 36 months plan only )
- Investors prfences top 3 were Green loans ,engamment Ring and baby adoptation
- Despite most borrowers choseing 36 months plan ,Investors were likely in 12 months plan which is normal as invstor wants his orignal invsting amount in shorter period time unlike borrower

## Key Insights for Presentation

In the exploration I found the Distribution of delinquent shows most of the data around 0 which indicates low level of Delinquencies

- In the exploration, I found that there was a strong relationship bewteen estmited effective yield and boorower annul rate. The relationship is approximately linear .
 - I found a somewhat surprising result initially despite most of the loan term plan in 36 months term plan , invertosrs Distribution showes that large numbers tends to invest in 12 month term plan.

Outside of the main variables of interest, I verified that some varibales we think has an effect on borrowers's loan counts  does not show any affect like IsBorrowerHomeowner unlike other variables like EmploymentStatus IncomeVerifiable,IncomeRange

- Also Higher prosper rating led to higher Estamited effective Yeild on loans 
- Most borrowers choseing 36 months plan ,Investors were likely in 12 months plan which is normal as invstor wants his orignal invsting amount in shorter period time unlike borrower



## Refrences 
- https://www.prosper.com/
- 


