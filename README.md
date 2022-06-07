# UFOs
JavaScript, Bootstrap, and UFOs
# Project Overview
The purpose of this project is to continue to build on a UFO webpage created by Dana, a client of our company. While she already has the table built that will allow users to filter through UFO sightings by data, she has tasked us with adding to those filter parameters. This will allow users to filter for multiple criteria in addition to date at the same time. At the completion of this project, users will be able to search by city, state, country, and the shape of the UFO all from the same site. 
We have been tasked with the following two deliverables for this project:
-	Deliverable 1: Filter UFO sightings on multiple criteria
-	Deliverable 2: A written report on the UFO analysis 

## Project Resources
-	VS Code
-	HTML
-	JavaScript
-	D3.js
-	CSS
-	Bootstrap

## Results
The webpage Dana has created allows users to view data on UFO sightings with a filter table that allows users to easily filter on various criteria such as date, city, state, and shape of the UFO sighting. A global unfiltered view can be seen below.


![Pic_1]( https://github.com/smithsh14/UFOs/blob/main/Resources/images/Initial_Picture.png)

The displayed results are dynamically filtered as you update the form field entries. There is no needed Submit or Refresh button as the tables update in real time. The filtered parameters are neatly positioned within the webpage so that you do not have to go far to find it. This gives the webpage a more user-friendly feel.


![Pic_2]( https://github.com/smithsh14/UFOs/blob/main/Resources/images/SearchFilter.png)

Users will be able to filter on the parameters to navigate through the data. 
As an example, we filtered the data to show results of UFO sightings in North Carolina only.


![Pic_3]( https://github.com/smithsh14/UFOs/blob/main/Resources/images/filter_nc.png)

The results of the filter returned 4 UFO sightings in the cities of Waxhaw, Rockwell, Cary and Deep Run.

## Summary:

### Advantages of the Webpage
The additional filter parameters we added to the webpage provides users a huge advantage. Users will not need to shift through rows and rows of data to find the information they are looking for. This keeps the website free of any unnecessary clutter that may make the ease of navigating through this webpage harder. The fact users can search through multiple parameters is also a huge advantage. The initial page only allowed for users to filter by date which returned a wealth of data in the table. Having these additional filters increases the usability of this site.  

## Drawbacks of the Webpage
The biggest drawback of this webpage is that the search filters are case sensitive. Let’s review the search we preformed earlier with North Carolina. We entered “nc” as our search parameter and it returned 4 items in the table. However, if we were to put in “NC” with both the letters capitalized, we will see that the search returns no results. It does not even provide an error message to let users know why there is no data returning inside the table.


![Pic_4]( https://github.com/smithsh14/UFOs/blob/main/Resources/images/Case_Sensitive_NC.png)


Likewise, what if we spell the state out and search for “north carolina”. The same thing occurs, there is no results returned into the table. This may lead users to assume there were no UFO sightings in North Carolina during that time and that is simply not accurate.


![Pic_5]( https://github.com/smithsh14/UFOs/blob/main/Resources/images/Case_Sensitive_NorthCarolina.png) 

## Recommendations for further development
There are a few areas I would focus on in aiming to improve the usability of this webpage…
1)	Widening the search parameters to include various non-case sensitive search options. This will allow for users to input either “nc”, “NC”, or “North Carolina” and still return accurate results.
2)	For the data search engine field, using a calendar option as opposed to typing out the date in a required format could improve on the user’s ability to use this webpage more efficiently
3)	Adding a message that simply says “No results found with this search” or some message of the same manner will help users know if their really is no data to be returned or if they just need to update their search parameters


