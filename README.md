# Mission-to-Mars
## Overview
This project involved web scraping methods to extract information about Mars from the NASA Science Mars Exploration website using Chrome Developer tools to identify HTML components, Beautiful Soup/Splinter to automate a web browser and perform the scrape, MongoDB to store the data, and finally Flask to create a web application to display the data. Our app scraped the following information about the planet Mars:

* Latest News
* Featured Image
* Facts about the planet
* Images of the hemispheres

## Procedure and Results

We created a file in Jupyter notebook to perform the scraping activity and pull the requested information needed to build the app. We used splinter’s browser to visit the url and along with BeautifulSoup, we parsed the data.  We used the code to get the latest Mars news article, featured Mars Image , and Mars facts.  Below is a glimpse of out jupyter notebook code:
 ![Screen Shot 2022-04-29 at 4 14 48 PM](https://user-images.githubusercontent.com/98566486/166066479-93802ac5-1fbc-4a4c-89ed-fd537aa8417e.png)



Then we saved our code as a python code to use to build our Flask app.  In VS code editor, we initiated a Flask instance and configure it to the PyMongo database.  We also started an index.html file and saved in templates folder to serve as the backbone for running our web application.  
 
Then we enhanced our web app by using Bootstrap styling sheets.  Our app header looks like this:
 
![Screen Shot 2022-04-29 at 4 43 40 PM](https://user-images.githubusercontent.com/98566486/166066716-0a4c38f3-6213-4185-8857-2f811beb565b.png)


## Summary
Web scraping is fun yet time consuming project.  There is a lot of coding and data handling involves in the final outcome.  


