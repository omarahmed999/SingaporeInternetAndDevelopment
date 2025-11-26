# Singapore Internet And Development
As a part of my learning journey I used Singapore as a case study to apply EDA and see the relation between how internet affects and shapes nations and if there is a relationship between internet and country development.
I used the world bank api (wbgapi) as my main source of data
Indicators included:
- GDP growth (annual %)
- GDP per capita (constant 2015 US$)
- Foreign direct investment, net inflows (% of GDP)
- Life expectancy at birth, total (years)
- Mortality rate, under-5 (per 1,000 live births)
- Research and development expenditure (% of GDP)
- High-technology exports (% of manufactured exports)
- Individuals using the Internet (% of population)
- Mobile cellular subscriptions (per 100 people)

After cleaning:
- Dropped columns with very low data coverage
- Converted Year to integer and other columns to float
<img width="1000" height="600" alt="heatmap_SNG" src="https://github.com/user-attachments/assets/4ac9e413-c3f3-4d4b-94b2-c96e9f91bdd7" />
The heatmap shows strong correlations between Internet usage and several key development indicators:
- **+0.97** with Year
- **+0.95** with GDP per capita
- **+0.98** with Life expectancy
- **-0.93** with Under-5 mortality
- **+0.73** with Foreign Direct Investment
<img width="640" height="480" alt="NOrmaized" src="https://github.com/user-attachments/assets/777ea3e2-b258-48d9-ad1c-dabfbb665dc2" />
- When normalized, internet usage, life expectancy, and GDP per capita all show parallel growth curves, reinforcing the idea that digital access supports both economic prosperity and human development.
  
  
<img width="640" height="480" alt="internetvsGDPperCapita" src="https://github.com/user-attachments/assets/b2f61765-3a0e-423d-8462-b1038f6cb6ba" />

This plot shows the relation between internet and GDP per capita
In Egypt today (2025), most citizens still rely on **limited monthly internet packages**, often paying **210 EGP (~4.44 USD)** for just **140GB** per month at speeds up to **30 Mbps**.  

In contrast, in Singapore, unlimited home internet plans start at **17 SGD (~12.50 USD)** — with **3 Gbps** speeds.  

Singapore’s success highlights a critical lesson: affordable and accessible internet is not a luxury — it’s infrastructure. It connects education, innovation, health, and investment. For Egypt to replicate similar progress, expanding affordable, high-speed internet access nationwide is essential.

