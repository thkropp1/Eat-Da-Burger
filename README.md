# Eat-Da-Burger
Eat-Da-Burger is a restaurant app that lets users input the names of burgers they'd like to eat. 

I created a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM. I followed the MVC design pattern; I used Node and MySQL to query and route data in my app, and Handlebars to generate the HTML.

Whenever a user submits a burger's name, the app will display the burger on the left side of the page -- waiting to be devoured.

Each burger in the waiting area also has a Chomp Da Burger! button. When the user clicks it, the burger will move to the right side of the page.

The app stores every burger in a MySQL database, whether devoured or not.
