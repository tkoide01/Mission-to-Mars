# Mission-to-Mars
Utilize web application and MongoDB to scrape, store, display Mars's Information

## Overview of the Project
Create a web application that scrapes Mars's Hemisphere images and title by utilizing BeautifulSoup and Splinter modules. Then store the scraped data on a Mongo database and further use a web application to display the data on a web browser.
In order to do so, below technical analysis are performed:

Deliverable 1: Scrape Full-Resolution Mars Hemisphere Images and Titles

Deliverable 2: Update the Web App with Mars Hemisphere Images and Titles

Deliverable 3: Add Bootstrap 3 Components

## Resources
- Used Codes: Mission_to_Mars_Challange.py, scraping.py, app.py
- Software: Jupytor Notebook, MongoDB, Python, Visual Studio Code

## Process

#### Deliverable 1: Scrape Full-Resolution Mars Hemisphere Images and Titles
  
  Scraped below data by coding `Mission_to_Mars_Challange.ipynb`: 
  - NASA Mars News: The latest News Title and Paragraph Text
  - JPL Mars Space Images: Featured Mars Images and URL to the full size image
  - Mars Facts: Table containing facts about the planet as Pandas DataFrame and HTML table string
  - Mars Hemisphere: image URL string and the Hemisphere title with the hemisphere name
 
#### Deliverable 2: Update the Web App with Mars Hemisphere Images and Titles

  Created below files to convert Jupytor Notebook file to Python and create a new HTML page:
  - `scraping.app`: converted Jupytor Notebook file into Python code. Added codes to define scraping scripts as function to run smoothly.
  -  `app.py`: created Flask app with `/` route and `/scrape` route that import the `scraping.py` script and query the Mongo database and convert the Mars Data into HTML template
  -  `index.html`: created HTML file that will display the Mars Data Dictionary
