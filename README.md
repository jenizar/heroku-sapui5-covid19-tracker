# heroku-sapui5-covid19-tracker
Deploy SAPUI5 apps Covid-19 Global Data to Heroku cloud


# Deploy to Heroku cloud

$ git clone https://github.com/jenizar/heroku-sapui5-covid19-tracker.git

$ cd sapui5-covid19-tracker (make sure you are in heroku-sapui5-covid19-tracker directory)

$ heroku login 

$ heroku create jenizar-sapui5-covid19

$ git push heroku main

$ heroku open

--> if problem use:

$ git remote rm heroku

$ heroku create jenizar-sapui5-covid19

$ git push heroku HEAD:master

Note:

- jenizar-sapui5-mockd is name your apps in the url, example: https://jenizar-sapui5-covid19.herokuapp.com

- cause this apps using html static therefore utilize php buildpack. 
