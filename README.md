# Low-vol-anomaly-Equity Research

This is a research project that I have been working on lately as a research assistant at Singapore Management University. 

The data files for this research have sizes larger than 200 MB, you can find them here: https://drive.google.com/drive/folders/1mOtMwjlIUtDTjmmuqocW6xCo2XxHf4Hi?usp=sharing

For the ultimate version of the code, "new data.csv" is used and the processing is in "Data Processing.ipynb". The calculations are done in the "low_vol portfolio strat.ipynb".

The main reference for this project are: 
Blitz, David and van Vliet, Pim, The Volatility Effect: Lower Risk Without Lower Return (July 4, 2007). Journal of Portfolio Management, pp. 102-113, Fall 2007; ERIM Report Series Reference No. ERS-2007-044-F&A. Available at SSRN: https://ssrn.com/abstract=980865 

Van Vliet P, De Koning J. High Returns from Low Risk: A Remarkable Stock Market Paradox[M]. John Wiley & Sons, 2017.

and other related literature written by Pim van Vilet and David Blitz. The whole reference list can be found at the reference section of the project report.

Multi-factor investor Pim van Vliet created a low-vol related portfolio that has proved to beat high-vol portfolio return in long-term.  
This project is intended to validate (backtesting) the strategy in U.S. stock market and then to explore the rationale behind it. 
Our hypothesis is there are significant ghost effects from the super big guys like MSFT and GE that mislead the empirical results. 
We tested this hypothesis by examining the skewness and kurtosis of the low-vol portfolio, then we will move on to test and optimize the rebalancing frequencies of the portfolio to get higher retuns.  

