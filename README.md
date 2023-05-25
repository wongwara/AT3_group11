## Introduction
As bank data scientists, we employ machine learning to analyse the huge amount of data available in banking. This data includes transaction history, client information, and meaningful financial information. 

We can swiftly process and evaluate this massive amount of data by leveraging machine learning algorithms' capabilities, detecting anomalies, and making accurate forecasts.

## Project Objective
There are 4 main objectives for our project:
1. `Case A`: **Better decision making**- Client financial management: Assist customers in organising their spending plans by forecasting their monthly expenses. This will increase overall happiness and financial security.
2. `Case B`: **Prevention of fraud** - Aid the compliance staff in identifying and eliminating fraudulent activity. This will safeguard our financial stability and maintain the trust of our clients.
3. `Case C`: **Improved customer experience** - Help the sales and marketing teams increase customer engagement and satisfaction for clients who are likely to increase their spending over the following three months. By concentrating our marketing efforts on these potential high-value customers.
4. `Case D`: **Better risk management** - Find out unusual spending patterns: Assist us in proactively contacting consumers to offer specialised advise and aid in resolving any possible issues or financial troubles they may be facing.

## Project Structure
```
├── README.md              <- read me
├── data_prep.ipyny        <- file to merge all the data
├── eda.ipyny              <- file for sample of eda
├── Experient A - Client Financial management.ipynb <- Jupyter notebooks for experiment A
├── anamoly detection (1.0).ipynb <- Jupyter notebooks for experiment D
├── summary.docx           <- summary of the code for experiment D
```
## Data understanding 
In our dataset, two files are combined: the first file contains transaction history data, which can be used to analyse patterns of spending, spot trends, and perform predictive analysis to predict future spending behaviour using the same account number and credit card number; the second file contains client information, including addresses and personal information, which can increase prediction accuracy and provide tailored financial management advice.

Transaction information for 1000 clients is available from December 2018 through December 2022. The dataset consists of 4,260,904 rows and 23 variables after the union. 

