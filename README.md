# analysis-of-business-indicators
Product - the entertainment application Procrastinate Pro+.

In recent months, the application has been operating at a loss, despite significant advertising budgets.

The goal is to identify the causes and help the company turn a profit.

Tasks:

- Determine where users come from and what devices they use,
- Determine the cost of attracting users from different advertising channels;
- Determine how much money each customer brings in,
Determine when customer acquisition costs are recovered,
Identify factors that hinder customer acquisition.
There is data available on users attracted from May 1 to October 27, 2019:

Server logs with information about their site visits,
Download of their purchases for this period,
Advertising expenses.
Data description:
There are three datasets available. The file visits_info_short.csv contains the server log with information about site visits, orders_info_short.csv contains information about orders, and costs_info_short.csv contains information about advertising expenses.

Structure of visits_info_short.csv:

User Id - a unique user identifier,
Region - user's country,
Device - user's device type,
Channel - identifier of the traffic source,
Session Start - date and time the session began,
Session End - date and time the session ended.
Structure of orders_info_short.csv:

User Id - a unique user identifier,
Event Dt - date and time of purchase,
Revenue - purchase amount.
Structure of costs_info_short.csv:

dt - date of the advertising campaign,
Channel - identifier of the advertising source,
Costs - expenses for this campaign.
