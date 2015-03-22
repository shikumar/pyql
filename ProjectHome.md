# pyql #

---

The module provides Python API to retreive stock information from Yahoo! Finance
using Yahoo Query Language.

The module uses Yahoo Query API, and sends REST to retrieve JSON, then converts
the result in a list of dictionary objects, and returns it.


Basic Usage:
```
>>> import pyql
>>> tickers = ['FFIV', 'MSFT', 'GOOG']
>>> print pyql.lookup(tickers)
>>> tickers = ['AAPL']
>>> print pyql.lookup(tickers)
```