# Vodafone-Stock-price-prediction-in-R

Background:

The dataset lse looks at the closing share prices for Vodafone and 27 other companies in the FTSE (Financial
Times Stock Exchange) 100 Index. The FTSE 100 Index lists the share prices of the 100 companies with the
highest market capitalisation that are part of the London Stock Exchange. That is, the companies with the
highest market value, worked out by multiplying the company’s share price with the number of shares. [1]
The data were taken from Yahoo Finance and the response variable, which predictions will be made on, is
labelled VOD. The dataset includes daily data from January 2016 to January 2019. The other 27 company
variables have been standardised with mean 0 and variance 1. The share price for Vodafone is one day ahead
and so a regression model can be fit to predict the closing share prices at the end of day (i+1) using those of
the 27 companies at the end of day (i)
