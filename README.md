# Victor Gomes

**CEO and co-founder [@tradingcomdados](https://www.tradingcomdados.com)**

We have recently launched our own Python library for quantitative finance. Check it out!

## Machine Learning
This library has a few machine learning models that you can use in your daily activities.

With our lib, you can easily implement machine learning models to your daily activities in the financial market.

```python
from tradingcomdados import unsupervised_learning as ul

ul.clustering_pipeline()
```

## Alternative Data
You can obtain alternative data from the Brazilian Market using this library

Examples:
* Indexes, such as IBOV, IFIX but also S&P 500
* Economy sectors of companies listed in the Brazilian stock exchange


```python
from tradingcomdados import alternative_data as ad

# General function
ad.ibov_composition()

# Obtaining composition of IBOV
ad.ibov_composition('Ibov')

# Obtaining sectors of Brazilian companies listed at B3
ad.setores_bolsa()

# Obtaining sector of a particular company
ad.setores_bolsa('PETR')

# Notice we are not using numbers at the end of tickers
ad.setores_bolsa('VALE')


```


If you want to check Trading com Dados' github, click the link below:
https://github.com/Trading-com-Dados

My CV: [Click Here](https://github.com/victorncg/victorncg/blob/main/20210513%20-%20Resume%20Victor%20Gomes.pdf)





-------------------



## Page under construction!

Last update 05/03/2023



[![Victor Gomes's GitHub stats](https://github-readme-stats.vercel.app/api?username=victorncg&count_private=true&show_icons=true&theme=algolia)](https://github.com/victorncg/github-readme-stats)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=victorncg&layout=compact&theme=algolia)](https://github.com/victorncg/github-readme-stats)
