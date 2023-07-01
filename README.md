# Mortgage-calculator
A mortgage calculator can be very helpful when you’re deciding how to approach the financial side of buying a home. It can give you a ballpark figure of what your monthly mortgage payment may be so you can estimate expenses. It can also help you decide if you might prefer a fixed-rate or an adjustable-rate loan, or a 15- or 30-year loan term.
Building a mortgage calculator with an amortization schedule in Excel can be done by following these simple steps:

Step 1: Set up the basic inputs

Create a new Excel spreadsheet.
Label cell A6 as "Loan Amount."
Label cell A7 as "Interest Rate."
Label cell A8 as "Repayment Period."
In cell B6, B7, and B8, users will input the loan amount, interest rate, and repayment period, respectively.
Step 2: Calculate the monthly interest rate

In cell B4, write the formula "=B7/12" to calculate the monthly interest rate. This formula divides the annual interest rate (cell B7) by 12 to get the monthly rate.
Step 3: Calculate the number of monthly payments

In cell B8, write the formula "=B8*12" to calculate the total number of monthly payments. This formula multiplies the repayment period in years (cell B8) by 12 to get the number of months.
Step 4: Calculate the monthly mortgage payment

In cell B6, write the formula "=PMT(B9, B10, -B4)" to calculate the monthly mortgage payment. This formula uses the PMT function, where the arguments are the monthly interest rate (B9), the total number of monthly payments (B10), and the loan amount as a negative value (-B4).
