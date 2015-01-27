Daily Stock Forecast
=======

Daily Stock Forecast is a cloud based machine learning tool 
for day trading professionals. The site pulls from a current
list of ~7,000 stocks across the AMEX, Nasdaq, and NYSE
exchanges and performs epsilon-Support Vector Regression based
machine learning on historical values to forecast the open,
close, high, low, and volume of the next business day for each
stock in our expanding universe.

Daily Stock Forecast is currently in development, a proof of
concept version of the site can be viewed here:<br />
<http://1.daily-stock-forecast.appspot.com/>

Concept images of the in development Polymer site:<br />
<https://www.dropbox.com/s/91ddg50jnbkw7pc/DSF1.png?dl=0> <br />
<https://www.dropbox.com/s/keflbdkzq5u7wr5/DSF2.png?dl=0>

Features
========

* Transparency of results. Each forecast comes with a 90 day performance
analysis to expose the Slope and R2 values of past predictions for each
metric.

* Frontend powered by Google App Engine and Google NDB Datastore,
Google Charts, and in development is a new Polymer based site.

* Backend powered by Google Compute engine and scikit-learn to
perform machine learning on historical stock prices.

* Statistic and machine learning libraries like matplotlib, scipy,
pandas, and scikit-learn support development, analysis and
in development visualization of stock forecasts.

Installation
============

The frontend runs on a Google App Engine instance. It utilizes
python, WebApp2, Jinja2 templating, JQuery, Google Charts, and 
soon Polymer and web components.

The backend and analysis can run locally if the datastore writing 
is disabled, but the current datastore exchange expects that the 
forecast is performed "inside the project" on a Google Compute 
Engine instance with the ability to securely access the Datastore.

Dependencies
------------

* Python 2.7
* numpy 
* pandas
* pytz
* sk-learn
* googledatastore
* Polymer (5.2+)


Credits
============

Daily Stock Forecast was developed by Derek M Tishler,<br />
<https://www.linkedin.com/profile/view?id=263507105>

Contact
=======

For other questions, please contact <dmtishler@gmail.com>.
