# Tesla_stock_prediction
Using time series analysis and natural language processing to predict Tesla stock price changes


# Executive Summary

Utilizing natural language processing on Twitter data from Elon Musk and the corporate Tesla account as well as news headlines from the news aggregate site Techmeme, I was able to suppliment a SARIMAX time series model and make predictions on whether the closing price would be higher or lower than the openning price at the beginning of the day. I developed a tool to look at how effective the model would have been over 2017 after being trained only on data from 2014 to 2016.  This was ultimately able to provide a profit that was proved better than merely holding onto the stock. Further analysis will be needed to see if this higher profit holds over longer time periods and how it handles a downturn (Tesla stock has largely trended upward throughout its history).

I also constructed a model that constantly updates itself with daily information that could be deployed with further work (mainly automating the information gathering technics). This was simulated over 2017, but needs further tuning to ensure effectiveness.
