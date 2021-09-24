# CSCI 1170
## Project (Winter 2020)

### Website Topic: 
* Nature/wildlife tours and travels (the company's name is "In the wild").

### Design Decisions and Assumptions
IN THIS SPACE, INCLUDE THE DECISIONS AND ASSUMPTIONS YOU MADE WHEN REDESIGNING THE LAYOUT OF THE WEB PAGES.

1. type the basic code for the index page.
2. design the logo image. I plan use the image URL: https://upload.wikimedia.org/wikipedia/commons/e/ec/Nordic_Optical_Telescope_near_sunset.jpg as the basic part, and add some flowers and the company name on it. 
3. I plan the create three html in total. one index(main), services(including some travelling plans), and price(show the different price for plans).
4. use Helvetica as the primary font-family, and, Arial is the second font-family
5. For the <h2>, I use the text-transform: uppercase; and text-decoration: underline; For the <h4>, I use the border-bottom: 2px solid green; 
6. add the tree.png as the background-image to the services part in the home page, and set it to the bottom right. Set the background-size: 40% to let the image can change small as decreasing the width of the webpage.
7. Following the Moodboard, using #B6FFAB, #F1FF9E, #BBE890 as the main color for the website.
8. For the navigation bar, I tend to make a sub-menu. In order to do that, I need to creat two <ol> lists in the <nav> and hide the sub-menu. In the "a: hover", change the display property od sub-menu to block.
9. In order to keep the navigation bar always floating on the top of the webpage, I plan to set Nav's position to “sticky”; And the top distance is zero. 
10. use the "grid" property to layout the header, navigation, aside, and article following the wireframes.
11. use percentage to set the width for every part of the web page to make the webpage can change in the different viewport.

* For the viewport:
12. assume the mobile layout transitions occur at a width of 500px. assume the tablet layout transitions occur at a width of 1000px. So in "@media screen and (max-width: 500px) {" to hide the aside, in "@media screen and (max-width: 1000px) {" to hide the search form and change the grid-area of aside and article. 
13. Check that all hyperlinks are working properly, and the elements of the navigation bar can be navigated to the correct content section.

### Citations
1. logo image used to redesign from:
URL: https://upload.wikimedia.org/wikipedia/fr/thumb/1/1e/Logo_Wild_Minnesota.svg/1200px-Logo_Wild_Minnesota.svg.png
Date accessed: 11 Apr 2020

2. background image used from:
URL: http://www.wildernesstravel.com/images/trips/europe/switzerland/switzerland-the-via-alpina/1-slide-switzerland-via-alpina-lake-oeschinensee-hikers-pano.jpg
Date accessed: 12 Apr 2020

3. Tree image used from:
URL: https://i.pinimg.com/originals/fc/91/6b/fc916b4ad080073228255a6a6cd099c6.png
Date accessed: 13 Apr 2020

4. Text content downloaded from:
URL: https://www.naturewildlifetours.com/
Date accessed: 15 Apr 2020

5. Normalize.css
normalize.css v7.0.0 | MIT License | github.com/necolas/normalize.css 

