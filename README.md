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

The scraping for the first three portions of the website were done through the module while the fourth part was part of the challenge.  The original html code was included in the module.  The code for the Mars Hemispheres portion was developed for the challenge.  Another part of the challenge was to make the website mobile responsive using Bootstrap 3 grid system system.  This was accomplished by adding a class of "div class" under each heading and using the codes in the grid system.

![image](https://user-images.githubusercontent.com/106293233/184765022-741878e3-ca90-494b-9a43-86e09a5d6a9a.png)

Two other Bootstrap 3.3 componenents were used:  a header and a page number.

Currently, the website looks like this:
![2022-08-15_21-04-30](https://user-images.githubusercontent.com/106293233/184769844-6d829f2b-43bb-48b0-92c5-269be3fccdcb.png)
