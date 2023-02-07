# Sauto Python Project 

## Background

This program is used to recommend second-hand private cars to users in Prague. As a tourist city, Prague has beautiful scenery, which not only attracts many tourists, but also attracts many international students. In order to facilitate people's lives, especially some students who are not well-off, our program can help them buy affordable second-hand cars. Through the user's input of their own preferences (for example, gasoline/diesel, the highest accepted price, the highest accepted mileage), the five most suitable cars are screened and automatically recommended, and they are displayed visually.

In the project, we clean the data through the API of www.sauto.cz, and write the cleaned data into the database. Our database is built on our Alibaba cloud server, and we refresh and update the data of the database regularly. We also design the user interface through tkinter, through which the user enters user parameters in the user interface, screens in the database, and finally presents the detailed information of the private car that meets the conditions and the best cost performance for the user.

## Install

The project uses pandas, requests, tkinter, sqllite3, pymysql packages. Please check if the packages are installed on your laptop. If not, please refer to the instruction below.   
Here using pandas for an example:  
Enter the command “pip install pandas” on the terminal. 

## Usage 
The project is designed in tkinter toolkit. By running the project, customer can enter the parameters and have a list of automobiles that meet their requirement. 

## API
The project is built from the JSON API from www.sauto.cz. 



## Contributing 
If you want to work on this application we’d love your pull requests or raise a tickets on GitHub!
If you open up a ticket, please make sure it describes the problem or feature request fully.

