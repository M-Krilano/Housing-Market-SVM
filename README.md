# Housing-Market-SVM
Using the Quandl module I extracted Housing Price Index(HPI) data from all 50 states (1975 to present), manipulated the data to find the HPI percentage change since 1975 for all US states.

Dependencies:
- python
- pandas
- plotly
- matplotlib
- pickle
- sklearn
- quandl

Part 1("new_mexico_analysis.ipynb"): I wanted to see if it was a good time to buy a house in New Mexico. I compared New Mexico HPI to US avg HPI by determining their correlation and deduced that the best times to buy were in 1987,1991, 1998, and 2007. This is because their correlation values dipped to the lowest from -0.5 to -0.9. As of now, the correlation doesn't seem to be diverging which means it's not a good time to buy but a good time to sell.

Part 2("housing_prediction.ipynb"): I used a support vector machine to classify if the Housing Price Index will Increase or Decrease based on % change of HPI of every US state, GDP, SP500, 30 year mortgage rate, and unemployment rate.


# Please Note
I used plotly but github performs a static render of the notebooks and it doesn't include the embedded HTML/JavaScript that makes up a plotly graph. If you'd like to see the dynamic graphs paste the link of any GitHub notebooks into http://nbviewer.jupyter.org/, which will present a rich view of the notebook.

Notebook Links:
1) New Mexico Analysis
https://github.com/M-Krilano/HousingMarket/blob/master/new_mexico_analysis.ipynb
2) Housing Market Prediction
