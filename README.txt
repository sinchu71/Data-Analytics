Project Title: Loyalty Points Calculation - Analytics Case Study

Files Submitted:
1. loyalty_points_analysis.ipynb - Google Colab notebook with full solution
2. User_Loyalty_Points_Report.xlsx - Final output report with Loyalty Points per user

Approach Summary:
- Cleaned and preprocessed Gameplay, Deposit, and Withdrawal datasets.
- Aggregated data per user.
- Applied the formula as provided:
   Loyalty Points = 0.01 * Deposit Amount
                  + 0.2 * Games Played
                  - 0.005 * Withdrawal Amount
                  + 0.001 * max(#Deposits - #Withdrawals, 0)

- Sorted users based on Loyalty Points.
- Saved the result to Excel using pandas.

Tools Used: Python, pandas, Google Colab

Prepared by: Sinchana C
