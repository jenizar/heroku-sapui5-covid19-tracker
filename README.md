# heroku-sapui5-covid19-tracker
Deploy SAPUI5 apps Covid-19 Global Data to Heroku cloud


# Deploy to Heroku cloud

$ git clone `https://github.com/jenizar/heroku-sapui5-covid19-tracker.git`

$ cd heroku-sapui5-covid19-tracker (make sure you are in heroku-sapui5-covid19-tracker directory)

$ heroku login 

$ heroku create jenizar-sapui5-covid19

$ git push heroku main

$ heroku open

--> if problem use:

$ git remote rm heroku

$ heroku create jenizar-sapui5-covid19

$ git push heroku HEAD:master

Note:

- jenizar-sapui5-mockd is name your apps in the url, open your browser: https://jenizar-sapui5-covid19.herokuapp.com

- cause this apps using html static therefore utilize php buildpack. 

![alt text](https://github.com/jenizar/heroku-sapui5-covid19-tracker/blob/main/Screenshot/Screenshot%20from%202021-12-19%2016-59-19.png)

![alt text](https://github.com/jenizar/heroku-sapui5-covid19-tracker/blob/main/Screenshot/Screenshot%20from%202021-12-19%2016-59-24.png)


  format data api :
 
 {"data":[

{"updated":1587257780909,"country":"USA","countryInfo":{"_id":840,"iso2":"US","iso3":"USA","lat":38,"long":-97,"flag":"https://raw.githubusercontent.com/NovelCOVID/API/master/assets/flags/us.png"},"cases":738792,"todayCases":0,"deaths":39014,"todayDeaths":0,"recovered":68269,"active":631509,"critical":13551,"casesPerOneMillion":2232,"deathsPerOneMillion":118,"tests":3722145,"testsPerOneMillion":11245,"continent":"North America","confirmed":738792,"countryCode":"US"},

{"updated":1587257780910,"country":"Spain","countryInfo":{"_id":724,"iso2":"ES","iso3":"ESP","lat":40,"long":-4,"flag":"https://raw.githubusercontent.com/NovelCOVID/API/master/assets/flags/es.png"},"cases":194416,"todayCases":0,"deaths":20639,"todayDeaths":0,"recovered":74797,"active":98980,"critical":7371,"casesPerOneMillion":4158,"deathsPerOneMillion":441,"tests":930230,"testsPerOneMillion":19896,"continent":"Europe","confirmed":194416,"countryCode":"ES"},

{"updated":1587257780911,"country":"Italy","countryInfo":{"_id":380,"iso2":"IT","iso3":"ITA","lat":42.8333,"long":12.8333,"flag":"https://raw.githubusercontent.com/NovelCOVID/API/master/assets/flags/it.png"},"cases":175925,"todayCases":0,"deaths":23227,"todayDeaths":0,"recovered":44927,"active":107771,"critical":2733,"casesPerOneMillion":2910,"deathsPerOneMillion":384,"tests":1305833,"testsPerOneMillion":21598,"continent":"Europe","confirmed":175925,"countryCode":"IT"} ]
 
 References:
 
 1. worldometers api : `https://corona-stats.online?format=json`
 
 2. `https://github.com/sagarkarira/coronavirus-tracker-cli?fbclid=IwAR0h0WPHflSW5q9bRlo3IdjRwUXf9wd0_LsBGgNensyfG8UWpG2xH-7-MuM`
