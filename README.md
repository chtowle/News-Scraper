# News-Scraper
All the News That's Fit to Scrape

Pseudocode.

I have had difficulty with this assignment.  I even had trouble getting the examples to run. I will continue to work on it.  I could not get handlebars to run correctly

All the News That's Fit to Scrape:
setup required dependence: axios, cheero, jquery, express, express handlebars, request ect.

set up the model and schema  for the articles and notes data in the database using mongoose's model method

title: {
type: String,
required: true
},
summary:{
type: String,
required: true
},
link: {
type: String,
required: true
},

note: {
type: Schema.Types.ObjectId,
ref: "Note"
}

Setup the required routes:

 rout for scraping the wedsite
	axios.get(“http://www.echojs.com”) 
	scrape all h2 tags and save results in the results object and add to database

route for getting all the articles and comments in the database

route for leaving a comment on the article

route for deleting comment on the article

route for saving/updating an article notes

Create an  index.html page and app.js that displays the list on articles and comments and listeners for the actions commenting, updating, and deleting an article  in the list of articles. Also have a listener for updating the list of articles
