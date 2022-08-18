# Mission-to-Mars

Web scraping using Python and Flask and storage with MongoDB.

## Overview

This project was undertaken in order to help Robin, a junior data scientist. Robin dreams of working for NASA, so, in order to impress them, she has decided to gather information about the Mars program and consolidate it on a website. Specifically, she wishes to create an app that will scrape data about the mission to Mars from several sources and, furthermore, will store the data in a NoSQL database. 

After some initial success with her web app, she wishes to expand it in order to feature Mars' hemispheres and upgrade it with Bootstrap 3 components.

## Resources

- Flask
- Jupyter Notebook
- MongoDB
- BeautifulSoup
- Splinter

## Deliverable One

The first task was to scrape full-resolution images of Mars' hempspheres as well as the titles of those images. 

Code was written in Jupyter Notebook to scrape data from https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars. This included finding the html tags that hold the proper links and looping through them. The results were put in a [dictionary]().

## Deliverable Two

The second task was to update the web app with the hemisphere information gleaned in the first component, as well as import that information into MongoDB.

The Jupyter Notebook file was converted to a python script and a function was created in order to do the same scraping of the hemisphere data automatically. A app.py script was created in order to run the scraping script in flask. Finally, the information was added to a [Mongo database]().

## Deliverable Three

Finally, in order to spruce up the webpage, Bootstrap 3 was utilized to both make the web app mobile-friendly and make it more visually appealing. Specifically, some red elements were added to the site to make it look more Mars-appropriate. The web scraping button [was enlarged and shaded deep red](), while the article summary [was shaded light red]().

## Summary

The project was a success overall; the web app looks great, and the information gleaned from the web scraping is now safe in a database.