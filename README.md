# Domestic Violence in Colombia - Trend and Outlier Analysis (What happend on april 21 of 2018)


## The Technology Used

In order to run this project, you just need to download the index.html file an open it in your browser, although not necessary, you could install a local http server on your machine, and serve the index html file from there, the easiest way (I think) is using the [SimpleHTTPServer](https://docs.python.org/2/library/simplehttpserver.html) Python utility, just be sure to have Python installed in your machine, go to the folder where you download the index.html and run:

```
python -m SimpleHTTPServer 8080
```

Open your browser and type http://localhost:8080/ and voila!

* [Javascript](https://www.w3schools.com/js/)
* [D3 version 5](https://d3js.org/)
* [css](https://www.w3schools.com/Css/)
* [html](https://www.w3schools.com/html/)

### The Components

* **tweet_retriever.py** is a python script that reads a file called properties.json (see below for details),
this scripts searches for tweets with specific characteristics as mentions for some accounts and some keywords in the tweet content, it use the [Twitter Search API](https://dev.twitter.com/rest/public/search). In order to use the script you must generate your own bearer token, [here](https://dev.twitter.com/oauth/application-only) you can find the instructions, possible (as it happend to me) you will face a common problem obtaining the token, so here i let a useful [link](https://stackoverflow.com/questions/23183050/twitter-1-1-oauth-authenticity-token-error99).

### License

This project has MIT license which can be consulted in the LICENSE of this repository.