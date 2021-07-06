**Vector Auto Regression (VAR)** in levels just means without taking any differences of the data. If your data in levels (i.e. as-is without any differencing) is 𝐼(𝑑), then first-differencing will make your data 𝐼(𝑑−1), and thus differencing 𝑑 times will make the data 𝐼(0). Often times we estimate VAR in differences to make the data 𝐼(0), so that we can work with stationary data. The appropriate specification, if your data are 𝐼(1), will depend heavily on whether the series are cointegrated.

**Unit Root** A unit root (also called a unit root process or a difference stationary process) is a stochastic trend in a time series, sometimes called a “random walk with drift”; If a time series has a unit root, it shows a systematic pattern that is unpredictable. https://www.statisticshowto.com/unit-root/

The existence of unit roots can cause your regression analysis to have serious issues like:
- Spurious regressions: you could get high r-squared values even if the data is uncorrelated.
- Errant behavior due to assumptions for analysis not being valid. For example, t-ratios will not follow a t-distribution.

Unit root tests are tests for stationarity in a time series. A time series has stationarity if a shift in time doesn’t cause a change in the shape of the distribution; unit roots are one cause for non-stationarity.

- The Dickey Fuller Test (sometimes called a Dickey Pantula test), which is based on linear regression. Serial correlation can be an issue, in which case the Augmented Dickey-Fuller (ADF) test can be used. The ADF handles bigger, more complex models. It does have the downside of a fairly high Type I error rate.

> Stephanie Glen. "Unit Root: Simple Definition, Unit Root Tests" From StatisticsHowTo.com: Elementary Statistics for the rest of us! https://www.statisticshowto.com/unit-root/

**Delivery Month Futures Code:**
January = F, February = G, March = H, April = J, May = K, June = M, July = N, August = Q, September = U, October = V, November = X, December = Z
