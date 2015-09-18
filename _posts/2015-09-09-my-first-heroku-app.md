---
layout: post
title: "My first Heroku app"
date: 2015-09-09
---

As a passionate [R](https://www.r-project.org)-programmer, I recently undertook my first
excursion into the world of [Python](http://python.6.x6.nabble.com). While the debate is still open on whether 
[R or Python](http://www.kdnuggets.com/2015/05/r-vs-python-data-science.html) is the better choice for Data Scientists, both 
languages offer packages to turn analyses into interactive web applications. The R package is called [Shiny](http://shiny.rstudio.com) and the one for Python is called [Flask](http://flask.pocoo.org).

I created an app that pulls data for stock prices for the past month of [Quandl](https://www.google.com/url?q=https%3A%2F%2Fwww.quandl.com%2Fdata%2FWIKI&sa=D&sntz=1&usg=AFrqEzdSDoXsG4-eGvhdKTEjkTaHL1PF1g)
and presents different indicators in an interactive plot. The plot uses the [Bokeh package](http://bokeh.pydata.org/en/latest/) and the app was deployed using [Heroku](https://www.heroku.com). 

Check out the final result [here](http://spynx.herokuapp.com). The code is on [Github](https://github.com/bartholdja/stockPriceTicker).
