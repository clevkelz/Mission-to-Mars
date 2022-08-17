# Mission to Mars

The purpose of this exercise was to scrape information from four different Mars-related websites using BeautifulSoup and Splinter.  The information gathered is as follows:
- Latest Mars news from NASA: https://redplanetscience.com/
- Featured Mars Image from Jet Propulsion Laboratory:  https://spaceimages-mars.com
- Galaxy Facts for Earth and Mars:  https://galaxyfacts-mars.com/
- Images of Mars' Four Hemispheres:  https://marshemispheres.com/

Beautiful Soup and Splinter were used to scrape the information, which was then stored in a Mongo database.  Finally, html code was developed to format the website showing the scraped information.  There are four files in this repository used to accomplish the analysis.
1.  Mission_to_Mars Challenge Jupyter Notebook File - Houses the code used to scrape the websites
2.  Scraping Python File - Stores a copy of the prior file to facilitate the transfer of the scraped data
3.  App.py Python File - Places the scraped data in the MongoDB, which is a a non-relational database
4.  Index.html File - Formats the design of the website 

The scraping for the first three portions of the website were done through the module while the fourth part was part of the challenge.  The original html code was included in the module.  The code for the Mars Hemispheres portion was developed for the challenge.  Another part of the challenge was to make the website mobile responsive using Bootstrap 3 grid system This was accomplished using div tags as presented in the grid system (see Image 1) and also by adding code to disable zooming capabilities (see Image 2).

_Image 1_

![2022-08-15_20-53-41](https://user-images.githubusercontent.com/106293233/185036531-4058d204-281b-4f31-939e-ff7cc4c7563b.png)

_Image 2_

![2022-08-17_00-50-08](https://user-images.githubusercontent.com/106293233/185037215-4f6dd9ca-e6fe-4677-8026-b45bc57fe649.png)

Two other Bootstrap 3 componenets were added as a requirement of the challenge:  the background color of the Jumbotron button was changed to "Success", which is green color (see Image 3), and the "Mission to Mars" text was made bold using the <Strong> option (see Image 4).
  
_Image 3_  

  
  
  
