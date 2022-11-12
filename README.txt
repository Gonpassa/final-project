Final Project for CS50 

Idea - Web application to find cities that an individual would like to live in. 

Concept:
User visits web app. Prompted with introduction on how to use application. 
Giving set of parameters that user is able to manipulate if he so chooses.
According to the parameters set, display interactive map of cities that match the parameters. 

Maybe using NUMBEO as the dataset.
DOCUMENTATION:

app.py: Back-end using python and Flask as a framework. Will control the actions of inputs by the user as well as recording the query in a database
to allow users to revert back to a query they decided to save. 

static folder: this is where css lives.

templates folder:
-layout.html- Will serve as a layour for all other html pages in the web application, allowing me to save time by not having to recreate
the nav bar and essential aspects of the application that will remain constant no matter which path the user visits. 

-index.html- Home page for application. This will include the name of the application and ideally i will be able to make this pretty looking. 
The home page will include short instructions as to how to use the software. 

-Search.html- Webpage that users will use to fill in their desired parameterers to create a query. Run button will run the query and open a map below the query parameterers
that will be populated with cities that match the criteria. 

-queries.html- This is where the queries that were previously ran by the user will live. A list of clickable queries that runs the program and redirects the user
to a map with locations of cities that meet the criteria of the query.

