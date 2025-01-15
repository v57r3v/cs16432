java c
Empirical Finance Spring II 2022 
Assignment 1Data   are   from   the   Center   for   Research   in   Security   Prices   (CRSP).   The   two   monthly   series   from CRSP are the value-weighted with-, RNt, and without-dividend nominal returns, RXt, of   CRSP   stock   market   indexes   (NYSE/AMEX/NASDAQ/ARCA).   The   sample   period   is   from   1946:M1   to   2020:M12.   The   monthly   nominal   dividend   series   are   constructed   as   follows.
• A normalized nominal value-weighted price series is produced by initializing P0   =   1   and recursively setting Pt = (1 + RXt)Pt-1,
• A   normalized   nominal dividend series, Dt, is obtained   by   recognizing   that Dt = (RNt − RXt)Pt-1   .
You will find “dividends.xlsx” that explains how to construct Pt (Price) and Dt (Div).
Q1. (70pts) Constructing dividend growth rates and log pd ratio
1. (10pts) Compute log dividend growth rates, Ad= In(D/Dt-1), and plot Ad.
2. (10pts) Compute the sample average and standard deviation of Ad in the range between 1947:M1 and 2020:M12.
3. (20pts*) Discuss the time series properties of △d.
4. (10pts) Aggregate the monthly dividends Dat = Σi11=o Dt-i. It is important to understand that for each December, we are aggregating the 12-months of dividends. Thus, T runs in annual frequency (i.e., December of each year) while t runs in monthly frequency. Compute the annual log growth rates Adta = In(D/Dat-1) and provide its sample average and standard deviation.
5. (10pts*) Plot the time series of Ad and compare with Ad (you could evenly distributeAd over the 12 months). 代 写Empirical Finance Spring II 2022 Assignment 1SQL
代做程序编程语言Discuss the sample standard deviation of the two series.
6. (10pts) Consider the December value of price P as P. Therefore, the length of time series of P matches that of D. Construct the log pd ratio pd- = In(P/D) and compute its sample average and standard deviation in the range of 1948 to 2020.
Q2. (60pts) Predictability 
1.    (20pts) Run   the   following   OLS   regression
∆dτ+h = αh + βhpdτ+ τ+h  (1)for h ∈ { 1, 2, 3, 4, 5} using   the   most   available   sample. For   example,   ∆dτ+5      is   available from   1953 to   2020 whereas pdτ is   available   from   1948 to   2015.   Report   the   estimate   of βh and   the   implied R2   value   for   each h.
Q3. (20pts) Reading on dividend/return    predictability 
Read Binsbergen and Koijen (2010) and summarize the paper.   The   summary   should be   not   more than two   paragraphs
Q4. (50 pts) Correlation between stock and bond returns 
You will find   "returns.csv" that includes two daily series of   stock returns   and bond returns   (of   maturity   1-year) which   range   from   1971 to   2020. 
1. (20pts) Compute the rolling correlation between stock returns and bond returns bysetting window interval to w. That is, you are to compute corr(R, Ro,) for each t where 2/w + 1 ≤ t ≤ T - 2/w 

Plot the time series of rolling correlation for w=60 and =900. 
2. (30pts*) Describe the correlation pattern and provide potential explanations. (Hint:feel free to search online). The explanation should be not more than two paragraphs. 







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
