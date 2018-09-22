# Domestic Violence in Colombia - Trend and Outlier Analysis (What happend on april 21 of 2018)

![alt text](https://github.com/cjcarvajal/domestic-violence-viz/blob/master/img.png)

I wanted to make this project to analyze domestic violence incidents in my country using visualization technologies, my motiviation was to help gaining insights on this social issue. In 2018 the incidents rose in just the [first three months](https://www.eltiempo.com/colombia/medellin/ninos-de-0-a-5-anos-son-las-principales-victimas-de-maltrato-en-medellin-205052) surpassing the numbers for the same period in the 2017, Colombia is a country wounded by constant violence, a war of fifty years, narcoterrorism, common crime, the crude reality is this violence is not just outside in the streets, but is in the homes, affecting childrens. I hope this visualization helps fighting against it.

You can check the insights I founded in the project, maybe you could find more.

## Dataset

The data was taken from an official goverment page [Datos Abiertos](https://www.datos.gov.co/Seguridad-y-Defensa/Violencia-intrafamiliar-2018/s9rg-bzb5)

## The Technology Used

In order to run this project, you just need to download the index.html file an open it in your browser, although not necessary, you could install a local http server on your machine, and serve the index html file from there, the easiest way (I think) is using the [SimpleHTTPServer](https://docs.python.org/2/library/simplehttpserver.html) Python utility, just be sure to have Python installed in your machine, go to the folder where you download the index.html and run:

```
python -m SimpleHTTPServer 8080
```

Open your browser and type http://localhost:8080/ and voila!

Although is not necessary to run the project, you may want to learn this technologies which were used to build the visualization.

* [Javascript](https://www.w3schools.com/js/)
* [D3 version 5](https://d3js.org/)
* [css](https://www.w3schools.com/Css/)
* [html](https://www.w3schools.com/html/)

### The Components

* **tweet_retriever.py** is a python script that reads a file called properties.json (see below for details),
this scripts searches for tweets with specific characteristics as mentions for some accounts and some keywords in the tweet content, it use the [Twitter Search API](https://dev.twitter.com/rest/public/search). In order to use the script you must generate your own bearer token, [here](https://dev.twitter.com/oauth/application-only) you can find the instructions, possible (as it happend to me) you will face a common problem obtaining the token, so here i let a useful [link](https://stackoverflow.com/questions/23183050/twitter-1-1-oauth-authenticity-token-error99).

### License

This project has MIT license which can be consulted in the LICENSE of this repository.