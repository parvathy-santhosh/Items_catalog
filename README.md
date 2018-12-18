# Udacity Item catalog Project

## About

RestaurantMenu App for Item catalog project This is a python module that creates a website and JSON API for a list of restaurants. Each restaurant displays their menus and also provides user authentication using Google. Registered users will have ability to edit and delete their own items. This application uses Flask,SQL Alchemy, JQuery,CSS, Javascript, and OAuth2 to create Item catalog website.

## Installation 
- virtualBox 
- Vagrant  
- python 

## Instructions to Run the project

Clone or download the repo into vagrant environment.
Type command vagrant up, vagrant ssh.
In VM, cd /vagrant/catalog
Run `python database_setup.py` to create the database.
Run `python lotsofmenus.py` to add the menu items
Run `python project.py`
open your webbrowser and visit http://localhost:5000/