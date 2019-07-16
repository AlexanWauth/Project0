# Project0

Web Programming with Python and JavaScript
 # Project0

dragon.html

contains the style settings for the title division class divtitle, the table division id divtable, body, and list.

The major div are centered to the page (this includes the title and the table).

The page has a title with a red border over a picture of Drogon. The title of the page changes colour (DarkMagenta >1000px, Darkgreen<1000px, and blue<1500px)This is followed by a table of contents that takes the user to the different parts of the page, helpful sites, dragon classification, famous dragons, and the sources used. The sites are used to include external hyperlinks while the table of contents contains internal hyperlinks. The classifcation of dragons table adjusts it size according to the screen size to fit it and max out at 1000px in size. The famous dragons section takes advantage of the bootstrap grid feature and adusts between large and small screen sizes. Sources simply contains the websites that were used for the pictures.

dragonstyles.css

contains nested style settings for the table and title's responses to size changes.
it contains the margin spacing for the division divlist.
contains the settings for the Table class redborder. As well as defining the text setting for table headers and data.

grid.scss

this was used to define the grid characteristics of class imgtab and famdragdiv (which uses nesting) to ensure that the photos fit within the cells created using bootstrap.
%button was created to define the properties of the table of contents while the ids ToC1, ToC2, ToC3, and ToC4 to show the use of inheritance.

I have added several new selectors to meet the requirement of at least 5 and added a bootstrap alert which displays the screensizealert.
