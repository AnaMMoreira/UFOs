# UFOs
## Module 11 challenge

## Overview of Project: Purpose of this analysis.

In this module, a table was created to organize UFO data that is stored as a JavaScript array, or list. This table was displayed in an interactive webpage and had the potential to filter and parse the data by date.

Building a page that contains JavaScript will required linking additional JavaScript files to an index.html file that will allow users to view the data and JavaScript was used to manipulate filter it and present it.  In this project organizing and keeping track of HTML file, JavaScript files, images (for customizing the webpage) and a CSS style sheet was necessary.  To make the page and parsing of the data interactive D3.js was used.

Data-Driven Documents or D3 is a JavaScript library that adds interactive functionality to webpage. It works by "listening" for events and can execute code linked to user imput.

The webpage and dynamic table were working as intended but allowing users to filter for multiple criteria at the same time was much more efficient and impressive.  So, in addition to the date, filters for the city, state, country, and shape were added and the results are displayed in the following section.

## Results: 

The website displayed in the following image shows how bootstrap and other text and information can be nicely displayed and a Table can be seen containing all the data.

home_page_UFOs_data.png

It can be seen that a box containing multiple input fields is contained next to the table displaying all the data.  There are placeholders displayed as examples of input but the data will not be filtered and parse and propagated to the table until the user input some specific "values" 

In the following image it can be seen that inputting a date in this case 1/5/2010 and hitting enter filtered our data down to only 4 rows of data.  

home_page_UFOs_data_Onefilter

The fields are flexible in that they don't necessarily have to be entered to yielded a filtered result and is not dependent on input order.
for example, the following figure shows you can filter by State only and it still works nicely!

home_page_UFOs_data_NYfilter


Adding a location filter of new paltz was enough to boil our data set down to one data point, as seen in the following figure.

home_page_UFOs_data_Multiplefilter


## Summary: 

Overall, this was an attractive display and user friendly website.

However, a couple of drawbacks might be that it is hard for the user to decide which filter to use that might yield some quick results instead of blindly "poking around" trying to get hits on the data.  I would suggest adding drop down menus w some of the available data points.

Also it would be nice to be able to filter the data by year for example instead of particular days/dates.  So further improvements might include splitting up the date filter into its components.
