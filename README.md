# Victor Gomes

**CEO and co-founder [@tradingcomdados](https://www.tradingcomdados.com)**

We have recently launched our own Python library for quantitative finance. Check it out!

### I'm currently working on the Alternative Data module of our library


## Alternative Data
You can obtain alternative data from the Brazilian Market using this library

Examples:
* Indexes, such as IBOV, IFIX but also S&P 500
* Economy sectors of companies listed in the Brazilian stock exchange


```python
from tradingcomdados import alternative_data as ad

# General function
ad.index_composition()

# Obtaining composition of IBOV
ad.index_composition('ibov')

# Obtaining composition of S&P500
ad.index_composition('sp500')

# Obtaining sectors of Brazilian companies listed at B3
ad.get_sectors()

# Obtaining sector of a particular company
ad.get_sectors('PETR')

# Notice we are not using numbers at the end of tickers
ad.get_sectors('VALE')


```


If you want to check Trading com Dados' github, click the link below:
https://github.com/Trading-com-Dados






-------------------



## Page under construction!

Last update 16/03/2024



[![Victor Gomes's GitHub stats](https://github-readme-stats.vercel.app/api?username=victorncg&count_private=true&show_icons=true&theme=algolia)](https://github.com/victorncg/github-readme-stats)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=victorncg&layout=compact)
