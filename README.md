# Markov stock model
Created by Greg Cooper and Matthew Zilligan for presentation in stocastic modeling course. <br/>
Attached Code is general model : <br/>
Paper explaining results also attached : <br/>


## Goals / Focus
(This was to be less a coding exercise, more to understand statistical implications in model)
- Generate an accurate system that models stock data in true or realistic way
- Gain insights into underlying stock movements aside from summary statistics (understand stocks probabilistically)
- Analyize and adjust different distributions to find most accurate model by counting method without forcing fit

## Notable Aspects
- Created Generalized model that supported N-state Markov model for supporting and finding best representation
- Followed previous dynamics by utilizing counting methods scalable by standard deviation as metric for scaling
- Employed Random Sum distribution of Guassian and Poission selection methods to make heavy tailed distributions truer to reality
- Created a model that differentiated stocks in similar trading buckets (delta vs american)
