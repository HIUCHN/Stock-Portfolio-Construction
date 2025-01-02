# Stock-Portfolio-Construction
## Methodology
Heading to 2024, inflation, economic downturns, elections, and geopolitical risks are all potential reasons for disruption in the stock market. According to The Conference Board, aggressive rate increases by major central banks around the world over the last 18 months or so have led to weakening in global housing, bank lending, and industrial activity. From an economic downturn perspective, stock screening for investment will be based on quality factors, which have received significant interest among academic researchers and practitioners since the global financial crisis. According to recent research by Lepetit F., Cherief A., Ly Y., Sekine T. (2021), high-quality companies are likely to outperform significantly in down-markets and can dampen sudden falls in market prices.
Based on the research by Asness C., Frazzini A., Pedersen L. (2017), factors that contribute to a high-quality company encompass profitability, growth, and safety. The stock selection approach will be conducted as follows:
•	Using time series data of stock price and financial report data.
•	Calculating, ranking, and normalizing metrics.
•	Calculating 3 factors: profitability, growth, and safety.
•	Calculating quality score by averaging 3 factor scores.
Based on the ranking results of quality score, I will go long on 5 stocks with quality scores in the top. After stock screening, the portfolio allocation optimization will be conducted using the method of maximizing the Sharpe ratio.

## Results
With the client's request to select 5 technology company stocks for investment, we will simulate our investment strategy based on a set of input stocks of technology companies with medium market capitalization or above, traded on NASDAQ and NYSE exchanges. Stock filtering will be carried out on nasdaq.com.
The strategy will be simulated for the third quarter and fourth quarter of 2023. The portfolio will be executed on the 15th day of the first month of each quarter to ensure companies disclose their quarterly financial reports. Then, the cumulative return of each quarter will be compared to the S&P 500 index, along with standard deviation and maximum drawdown in order to evaluate the strategy.
The stock portfolios selected based on quality factors for the third and fourth quarters of 2023 are respectively (META, QLYS, JKHY, GOOGL, GOOG) and (QLYS, APPF, MANH, META, LOGI). Subsequently, the investment proportions in these portfolios are optimized using the Sharpe ratio, resulting in the weights for the third and fourth quarter portfolios of (1.2%, 18%, 0.8%, 40%, 40%) and (40%, 7.1%, 40%, 12.9%, 0%).

![image](https://github.com/user-attachments/assets/53890a5d-568e-4996-a338-d1a0d91cfd07) 
![image](https://github.com/user-attachments/assets/1dc1dab1-6f6c-418e-b886-e075dfb9430c)

Overall, despite showing weaker performance in the initial periods of both quarters, the cumulative returns of the investment portfolio based on the quality factors consistently outperformed the cumulative returns of the S&P 500 index throughout the investment horizon. Notably, the cumulative returns of portfolio in third quarter of 2023 exhibited significant outperformance, whereas the S&P 500 index saw a slight decline of 3.3% in the same quarter after a robust 16.9% increase in the first half of 2023.

![image](https://github.com/user-attachments/assets/5710a46f-cb7d-42fe-a019-184661101ee4)




