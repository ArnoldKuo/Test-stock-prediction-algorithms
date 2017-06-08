# StockPredictions
Use classic tricks, neural networks, deep learning, genetic programming and other methods to predict stock and market movements.

Both successful and unsuccessful experiments will be posted. This section is things that are currently being explored. Completed projects will be wrapped up and moved to another repository to keep things simple.


<b>Data and the cleaning programs:</b>

https://github.com/timestocome/StockMarketData 



<b>Data sources:</b>

http://finance.yahoo.com/

https://fred.stlouisfed.org/



<b>Completed and spun off in another repository:</b>

https://github.com/timestocome/StockMarketMovingAverage  Moving average buy/sell under/over vs buy and hold 


<b>Completed but not useful:</b>

If it was this easy all statisticians would be rich. Still it's worth going through because sometimes faint signals can be found and amplified or combined with other faint signals to give useful information.

https://editorialexpress.com/cgi-bin/conference/download.cgi?db_name=SILC2016&paper_id=38  Stock Price Prediction using Hidden Markov Model --- meh, you have to feed it all the information and it doesn't work very well

http://www.investopedia.com/articles/financial-theory/09/bayesian-methods-financial-modeling.asp Bayesian predictions using gold, vix, 1 yrT, 10 yrB, Unemployment, trading volume, GDP. Everything is too entangled to produce new information

https://editorialexpress.com/cgi-bin/conference/download.cgi?db_name=SILC2016&paper_id=38  Stock Price Prediction using Hidden Markov Model --- meh, you have to feed it all the information and it doesn't work very well

https://en.wikipedia.org/wiki/Autoregressive_integrated_moving_average ARIMA, ARMA 



<b>Spun off, not yet fully finished:</b>

https://github.com/timestocome/Sunspots The Sunspot stuff works amazingly well on sunspot predicting, I haven't had a chance to try it on a stock index yet. Sunspots follow a pretty regular, albeit noisy pattern, which may be why it works so well?

https://github.com/timestocome/StockMarketClustering  Various clustering techniques 

https://github.com/timestocome/StockMarketLinearRegression  Experiments in various regression techniques 


<b>Looks promising, not yet fully finished:</b>

http://surface.syr.edu/cgi/viewcontent.cgi?article=1056&context=eecs_techreports Predict sunspot cycles with fully connected forward feed


The bull and bear markets have different histogram distributions. Daily changes in bull markets look like power distributions, bear markets are flatter, closer to guassians. The problem is a daily change needs lots of days to make a decent histogram. I need to think on this one more or try time slicing the data into smaller chunks and see if the effect is still there.


<b>Looks promising enough to test on financial data:</b>

https://github.com/openai/evolution-strategies-starter  Try some GA trading bots with and without NN 

http://www.kdnuggets.com/2017/04/time-series-analysis-generalized-additive-models.html  Time Series Analysis with Generalized Additive Models 

http://dl.acm.org/citation.cfm?id=1541882 (Anomaly Detection: A Survey 2009 ACM $$$$ --- excellent paper, I'm going to try several techniques it covers 


<b>Misc Reading:</b> 

http://www.e-m-h.org/Fama70.pdf  Efficient Market Hypothesis 

http://faculty.chicagobooth.edu/workshops/finance/pdf/Shleiferbff.pdf Bubbles for FAMA

http://www.unofficialgoogledatascience.com/2017/04/our-quest-for-robust-time-series.html  How Google does series predictions 


https://www.manning.com/books/machine-learning-with-tensorflow Meap Machine Learning with TensorFlow, excellent TensorFlow reference, not a good reference if you're looking to learn Machine Learning, I'm on my second pass, reworking all the example code with stock data, the stuff that shows promise is being loaded up here. I'll go deeper into all of them as time allows 

https://www.amazon.com/gp/product/B01AFXZ2F4/ Everybody Lies, Big Data, New Data, and What the Internet can tell us about who we really are

https://www.amazon.com/gp/product/B06XDWV2Z2 The Money Formula: Dodgy Finance, Pseudo Science, and How Mathematicians Took Over the Markets


<b>To read:</b>

http://lib.ugent.be/fulltxt/RUG01/001/315/567/RUG01-001315567_2010_0001_AC.pdf An empirical analysis of algorithmic trading on financial markets 

https://www.cs.elte.hu/blobs/diplomamunkak/bsc_matelem/2014/fora_gyula_krisztian.pdf  Predictive analysis of financial time series 

http://www.doc.ic.ac.uk/teaching/distinguished-projects/2015/j.cumming.pdf  An Investigation into the Use of Reinforcement Learning Techniques within the Algorithmic Trading Domain 

http://www.wiley.com/WileyCDA/WileyTitle/productCd-111909657X.html The ultimate algorithmic trading system toolbox 

http://quant-econ.net/_static/pdfs/py-quant-econ.pdf  Quantitative economics with Python 

https://research.google.com/pubs/pub41854.html Inferring causal impact using bayesian structural time series models


http://www.unofficialgoogledatascience.com/2017/03/attributing-deep-networks-prediction-to.html Attributing a deep network’s prediction to its input features 

I heard about a better way to attribute deep nets features to weights - take the same input and outputs and train a decision tree to match the deep network. As soon as I find the talk or paper, I'll add the link here.

https://www.r-bloggers.com/forecasting-markets-using-extreme-gradient-boosting-xgboost/amp/ X-Gradient Boosting for series predictions 

https://research.fb.com/prophet-forecasting-at-scale/  FB open source Prophet for series prediction 

https://blog.twitter.com/2015/introducing-practical-and-robust-anomaly-detection-in-a-time-series finding anomalies in time series 

https://medium.com/@harvitronix/lets-evolve-a-neural-network-with-a-genetic-algorithm-code-included-8809bece164 Let's evolve a neural network 


<b>Interesting Websites:</b>

https://www.wilmott.com/ Wilmott, Serving the qualitative finance community

http://www.nber.org/ The National Bureau of Economic Research 

https://fred.stlouisfed.org/ FRED, Federal Reserve Bank of St Louis

http://www.zerohedge.com/ ZeroHedge, mostly noise, occasionally something useful appears

