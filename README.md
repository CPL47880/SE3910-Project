# SE3910-Project
Repository for the Commerce Bank Project in SE-3910

PROJECT DESCRIPTION
-------------------
UCM Spring 2023 Project
Personal Budget Web App
Description
Making responsible financial decisions requires awareness of your own circumstances and defining
concrete savings goals for themselves can help a person internalize their spending habits. This project is
to develop a web application with which a user can define savings goals, track their spending, and
estimate their capacity to take out a personal loan with Commerce Bank.

Requirements
• The application must use Java and the Spring framework. It should also use a React front end
and a MySQL database.
• Users should be pre-established and authenticated with a simple login page. Credentials can be
stored in a database, but no encryption of the password is required for this project.

Balance Adjustment View
• A user’s initial balance should be zero, and they should be prompted to input an initial
unplanned balance adjustment to indicate their starting balance.
• The user should be able to input planned expenses and incomes.
• The user should be able to input unplanned expenses and incomes.
• The user should be able to delete any existing balance adjustments.

Monthly Calendar View
• The user should be able to see a monthly calendar view displaying expenses and incomes, as
well as if those expenses and incomes are planned or unplanned.
• The user should be able define monthly savings goals – the amount by which they would like
their account to increase over the course of each month.
• The user’s monthly view should display a target balance for the current day. This should be
calculated based on the day of the month, monthly savings goals, and starting budget for the
month.
  o Example: If the starting budget is $500 and the savings goal is $300, the target balance
  for the last day of the month is $800. The target balance for the 10th day of a 30 day
  month would then be (10/30)*300 + 500, or $600.
• The user’s monthly view should indicate the extent to which the user is currently over or under
budget by comparing the day’s target balance to the day’s actual budget.

Personal Loan Estimator View
• The user should be able to access a Personal Loan Estimator with inputs for a Loan Amount,
Loan Term (in months), and Interest Rate.
• The Personal Loan Estimator should calculate a monthly payment based on the input values.
• The Personal Loan Estimator should offer advice to the user, informing them when a specific
loan would cause their monthly savings to drop below their savings goal or worse, below zero.

Stretch Goals
• Users inputting expenses and incomes should have options to make them recurring monthly,
weekly, and/or with more complex methods for recurring dates such as “the first Friday of every
month” or “the 12th and 24th of every month.”
• From the Personal Loan Estimator, users should be able to add the calculated recurring monthly
payments to their calendar.
