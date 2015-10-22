---
title: "Mortgage Calculator"
author: "Sambasiva Andaluri"
date: "October 15, 2015"
output: slidy_presentation
mode: selfcontained
---

## Mortgage Calculator

There are hundreds of mortgage calculators available on the internet. Some of them require Excel and some of them are very difficult to work with and often do not disclose how they calculated the values. 

Presenting a new Mortgage Calculator where anyone shopping for a home or an existing home owner can run what-if scenarios by setting up various parameters. Anyone with basic R knowledge can validate the code behind the calculator and tweak to add additional features

## Input parameters

Mortgage calculator takes the following parameters and presents a what-if calculator where a user can change various parameters and see how it affects their monthly payment and how long it takes to pay off the loan.

- Property value : Value of the property in any currency.
- Downpayment : How much did you pay upfront as down payment for securing loan.
- Interest rate : Rate of interest for the loan.
- Loan term: Number of years overwhich the loan will be paid.
- Prepayment: Monthly additional principal payment.

## Output

The following is a sample of the output generated for an example mortgage scenario with 250,000 as property value, with 25% downpayment, interest rate of 3.625% for 30 year loan with a monthly additional principal payment of 100. For each month my calculator shows monthly mortgage payment with details on both principal and interest. By varying these parameters a home owner or a prospecive buyer can run different scenarios or compare mortgage lenders etc.


| Month| Start Balance| Principal| Prepay| Interest| Total| End Balance|
|-----:|-------------:|---------:|------:|--------:|-----:|-----------:|
|     1|        187500|       389|    100|      566|   955|      187111|
|     2|        187111|       390|    100|      565|   955|      186721|
|     3|        186721|       391|    100|      564|   955|      186330|
|     4|        186330|       392|    100|      563|   955|      185938|
|     5|        185938|       393|    100|      562|   955|      185545|
|     6|        185545|       395|    100|      560|   955|      185150|

## Conclusion

In summary, my mortgage calculator offers a simple approach to calculate monthly payments and run what-if analysis quickly to estimate monthly payments.

References:

Code and formulas were borrowed from the following sites to help develop this calculator:

http://codereview.stackexchange.com/questions/60097/calculation-of-mortgage-repayments

http://www.hughcalc.org/formula.php

