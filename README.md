# Mission-to-Mars
## Overview & Usage
Created a webapp which scrapes various astronomical websites and displays relevant information on Mars. By clicking the "Scrape New Data" button the app will:
1.  Using splinter, visit Nasa's [Mars news website](https://mars.nasa.gov/news/) and pull the latest headline and description from that page
2.  Using splinter, visit the [jpl website](https://www.jpl.nasa.gov/spaceimages/?search=&category=Mars) and pull the feauture image to be displaye on the app.
3.  Visit http://space-facts.com/mars/ and obtain values for the Mars table adjecent to the feature image.
4.  Using splinter, visit the [usgs astrogeology website](https://astrogeology.usgs.gov) to pull 4 Martian hemisphere images to be displayed at the bottom of the flask app.

## Resources
- Data Sources: [astrogeology](https://astrogeology.usgs.gov/), [mars news](https://mars.nasa.gov/news/), [jpl](https://www.jpl.nasa.gov/spaceimages/?search=&category=Mars), [space facts](http://space-facts.com/mars/)
- Software/Tools: Jupyter Lab
- Languages: Python 3, HTML5, CSS
- Packages: Bootstrap 4, Flask, splinter, pandas

## Results
![](https://github.com/JasmeerSangha/Mission-to-Mars/blob/master/webapp.png)
### Future Analysis ###
More work can go into organizing the information and storing it rather than replacing all past information with the most recent pieces of news.
