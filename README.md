
# Financial Planning with APIs and Simulations   
---
In this project, I decide to launch a tech consulting firm focused on projects benefiting local communities and secured the first contract with a large credit union. The project involves creating a tool to help credit union members evaluate their financial health by assessing their monthly budgets and forecasting effective retirement plans based on their current holdings of cryptocurrencies, stocks, and bonds. The goal is to develop a prototype application for the credit union's CTO to present at the next assembly.


## Technologies

1. Daily Returns
   1. 
   2. 
   3.
2. 
   1. 
   2.  
      > 
3. Rolling Data
   1. 
   2. 
   3.  
      > 
---

## Installation Guide

```python
# To run this analysis, you need serveral libraries from Python, such as Pandas, matplotlib, and requests
import os
import requests
import json
import numpy as np
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation
```

---
## Usage

#### Description
This project involves developing a financial health assessment tool for a large credit union. The tool will enable credit union members to evaluate their monthly budgets and forecast effective retirement plans based on their current holdings of cryptocurrencies, stocks, and bonds. The goal is to create a user-friendly prototype application that the credit union's CTO can present at the upcoming assembly, demonstrating its potential to improve financial planning and well-being for the members.
  
#### Processing
**Cumulative Returns of four whale funds and S&P 500**   
![Cumulative Returns](./Pics/CumulativeReturns.png)   
**For whale funds volatility and S&P 500**   
![Volatility](./Pics/Boxplot.png)   
**21-day Rolling Average for four whale funds and S&P 500**   
![Rolling Average](./Pics/RollingAverage.png)   
**Sharpe Ratio Data Analysis**   
![Sharpe Ratio](./Pics/SharpeRatio.png)   
**Berkshire Rolling Beta**   
![Rolling Beta](./Pics/RollingBeta.png)

---

## Contributors

Shu Liu   
shu@liu.net

---

## License

MIT License

Copyright (c) 2024 Shu

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
