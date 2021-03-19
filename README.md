#  ExpressJS  API  - Stock Trade App
#

##  Project 04

##  by  Nigel Sampath
    Florida Atlantic University
    Full-Stack Web Developer.


##  Description
    Stock Trade app.
    can look up current stock prices,
    simulate buy , and save to database.




##  Content:
    This app is in two separate parts Server and Client
    and function independently.

    The code in this repo is for the Trade App Client,
    see below:  

    Trade-Server - ExpressJS app that can route
                   API requests to look up real stock prices
                   using the yahoo-stock-prices API, and return
                   data back to client.
                   Also route API requests to buy stocks
                   and save to a Sqlite database.


    Trade-Client - Html, ReactJS, Javascript client
                   to handle User Interface, and API requests.


    Repo         - Server  at  project04-server                   
                 - Client  at  project04-client



##  Install:
    NodeJS will need to be installed first.
    Download all files to a directory,
    Server and Client should be installed in separate directories.

    then 'npm install' to install dependency modules.

    to start server app 'npm start'
    to start client app 'npm start'  


##  Technology used:
    Server :  nodeJS,  ExpressJS, Yahoo-stock-prices api.
              Sqlite database

    Client  : HTML , ReactJS for UI and single page application
              TailwindCSS styling and positioning.
              Javascript to make client API requests.





##
##
[END]
