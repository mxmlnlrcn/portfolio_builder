# portfolio_builder

This code create a portfolio minimizing the risk measured by Draw Down. The Draw Down is a way to identify how deep an asset can fall, that is very useful to battle against hard recoveries after heavy looses and it allow you to consider volatile but strong assets that the classical theory of building a portfolio put on the side trying to minimize the variance.

To build a portfolio you should provide a list of assets, a minimum desired yearly return and a time frame defined by two dates. 
This dates will be used to calculate the weights of the portfolio

In the end of the notebook you will have some charts that it will help you to visualize how the portfolio is performing