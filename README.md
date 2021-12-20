# Crypto_Arbitrage_Script
Here is some python code to automate the search for historical arbitrage opportunities in cryptocurrencies. The analysis examines changes in the frequency and size of profitable arbitrage trades through a case study focus on 3 dates out of a span of 3 months in early 2018. Simple descriptive statistics, line graphs, and box plots support the thesis that the cryptocurrency exchanges are less prone to information gaps and price dislocation as blockchain technology matures and investor knowledge becomes more diffuse.

---

## Technologies

This program was written in python 3.7. It uses the following libraries:

* [pandas](https://github.com/pandas-dev/pandas) - For dataframe tools and quantitative analysis.

* [pathlib](https://github.com/budlight/pathlib) - For importing and reading csv files.

* [matplotlib](https://github.com/matplotlib/matplotlib) - For creating graphs and charts.

---

## Data

Data are available as 2 CSV files: bitstamp.csv and coinbase.csv. The index is a datatimestamp field called Timestamp. The column Close represents the closing price and is the main focus of the analysis. Data span from January 1, 2018 to March 31, 2018.


---

## Contributors

Rachael Donham
rachaeldonham@gmail.com


---

## License

MIT