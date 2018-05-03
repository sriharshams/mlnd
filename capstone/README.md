# Machine Learning Engineer Nanodegree
# Capstone
## Project: Lending Club Investor ML

### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [pandas profiling](https://github.com/pandas-profiling/pandas-profiling)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

I recommend install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

### Code

Code is provided in the `lending_club_loan_paid.ipynb` notebook file. Some of the graph code to use the included `visuals.py` Python file and the `LoanStats3a_securev1_2007_2011.csv` dataset file is used for project. Note pandas profiling looks better if you use ipython.

### Run

In a terminal or command window, navigate to the top-level project directory `capstone/` (that contains this README) and run one of the following commands:

```bash
ipython notebook lending_club_loan_paid.ipynb
```  
or
```bash
jupyter notebook lending_club_loan_paid.ipynb
```

This will open the iPython Notebook software and project file in your browser.

### Data

The datasets are provided by LendingClub, we will use lending data from 2007-2011 and be trying to classify and predict whether or not the borrower paid back their loan in full. Data is available to download [here](https://www.lendingclub.com/info/download-data.action).

**Features**
Data fields: Some of the data fields listed below
  LoanStatNew	 Description
- annual_inc:	The self-reported annual income provided by the borrower during registration.
- delinq_2yrs:	The number of 30+ days past-due incidences of delinquency in the borrower's credit file for the past 2 years
- dti:	A ratio calculated using the borrower’s total monthly debt payments on the total debt obligations, excluding mortgage and the requested LC loan, divided by the borrower’s self-reported monthly income.
- emp_length:	Employment length in years. Possible values are between 0 and 10 where 0 means less than one year and 10 means ten or more years.
- fico_range_low:	The lower boundary range the borrower’s FICO at loan origination belongs to.
- home_ownership:	The home ownership status provided by the borrower during registration or obtained from the credit report. Our values are: RENT, OWN, MORTGAGE, OTHER
- inq_last_6mths:	The number of inquiries in past 6 months (excluding auto and mortgage inquiries)
- int_rate:	Interest Rate on the loan
- last_fico_range_low:	The lower boundary range the borrower’s last FICO pulled belongs to.
- loan_amnt:	The listed amount of the loan applied for by the borrower. If at some point in time, the credit department reduces the loan amount, then it will be reflected in this value.
- loan_status:	Current status of the loan
- open_acc:	The number of open credit lines in the borrower's credit file.
purpose	A category provided by the borrower for the loan request.
- revol_bal:	Total credit revolving balance
- revol_util:	Revolving line utilization rate, or the amount of credit the borrower is using relative to all available revolving credit.
term	The number of payments on the loan. Values are in months and can be either 36 or 60.
- total_acc:	The total number of credit lines currently in the borrower's credit file
verification_status:	Indicates if income was verified by LC, not verified, or if the income source was verified

**Target Variable**
- `loan_status`: tatus of the loan
