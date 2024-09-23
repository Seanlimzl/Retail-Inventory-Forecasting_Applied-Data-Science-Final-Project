# RetailInventoryForecasting

This was the final project for YSC4224 Applied Data Science at Yale-NUS College. It was a Kaggle competitionto provide a 21-day-forecast of the unit sales at the store, product level for 10 stores and 3049 SKUs given 1920 of history. We were provided dates, prices, and sales volume. I was on a team of four and lead the ARIMA modelling efforts and explored Prophet/NeuralProphet. I particularly learnt to scale AutoARIMA methods across a large number of time series via Polars and multiprocessing methods. Collaborating with a team mate I wrote HPC compatible AutoARIMA pipelines that made it possible to fit models on a per store per SKU level, which would have been impossible single-threaded on common hardware.

Technologies/Techniques: Time Series Analysis, ARIMA, AutoARIMA, SARIMAX, parallel computing, Dask, Polars, Prophet, NeuralProphet, GitLFS 

Competition link: https://www.kaggle.com/competitions/ysc4224-2023-final-project/data
