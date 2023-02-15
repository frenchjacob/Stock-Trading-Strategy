# Stock-Trading-Strategy

Description:
This program creates a simple trading/investment strategy using support vector classifier (SVC).
SVC is used classify & predict whether todays closing price will be higher then tomorrows if so it is classified as 1 else 0. 1 indicates tomorrows close price will be higher then todays hence we hold on this signal. 0 indicates tomorrows close price will lower hence we sell on this signal.

Results:
I found that using this strategy that returns were 48.3% than a buy and hold strategy. How ever after investigating the confusion matrix I found 83/157 false positives, this would increase positive gains significantly. Hence this strategy should be further optimised and back tested before being used for investing.

Improvements:
GridSearch for best SVC parameters, create different independant variables
