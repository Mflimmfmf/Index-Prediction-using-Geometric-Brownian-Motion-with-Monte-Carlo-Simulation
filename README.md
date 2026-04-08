Project Manual

1. Manually download the four historical data from Investing.com

2. Read the data through Quant_Lab.Rmd

3. Model development , model evaluation and hyperparameter tuning is conducted through such Rmd files

4. Obtain the optimal fit of the four historical indices:

    - To obtain optimal fit
         - Apply (drift and volatility tuninng):
            - MLE
            - Rolling Window (60 days)

         - Apply (only drift):
             - simple return

         - Apply (only volatility):
            - Exponential Weighted Moving Average (EWMA)

     - Manual extensive comparison is conducted to obtain the optimal fit 
    
5. The optimal fit result should refer to Tuning.xlsx
