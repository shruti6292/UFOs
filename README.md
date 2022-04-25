# UFOs

## Overview of Project: 
In this Project, we are helping Dana to present the given data on UFOs both visually appealing and interactive while exploring the front end developement language - javascript. Javascript brings extra functionality and customisation to enhance user experience.We will be focusing on dynamic web pages.

## Procedure:

At first the list element that creates the button is removed, and there are five list elements for filtering in the index.html file.
Then the event listener is modified to detect changes to each filter in the app.js file.
Then the updateFilters() function saves the element, value, and the id of the filter that was changed.
The filterTable() function loops through all of the filters and keeps any data that matches the filter values.
The webpage filters the table correctly based on user input.
We built our dynamic web pages by inserting javascript into an html page. With our prior knowledge of bootstrap, css, and some chrome dev tools, we built a table to hold a neatly displayed data we wanted to work with.

## Results: 
We explained to Dana how someone might use the new webpage by walking her through the process of using the search criteria.We have added filters to the table so that users can refine their search on different levels. There are five filters and by combining or individual filters user can view data from different date, city, state, country,and shape as shown in below images:  

![alt text](https://github.com/RGK73/UFOs/blob/main/Images/whole_html.png)

We explained Dada about the filters that we have applied:

![alt text](https://github.com/RGK73/UFOs/blob/main/Images/filters.png)

And then walked her through the results by applying those different filters with different combinations as per the user requirements:

![alt text](https://github.com/RGK73/UFOs/blob/main/Images/city_country_filter.png)

![alt text](https://github.com/RGK73/UFOs/blob/main/Images/date_filter.png)

![alt text](https://github.com/RGK73/UFOs/blob/main/Images/shape_filter.png)

Finally, we showed Dada the results with all the filters applied:

![alt text](https://github.com/RGK73/UFOs/blob/main/Images/all_filters.png)

## Summary: 

Our current webpage has one main advantage in that users can search upon multiple criteria at one time and there is no submit button needed. However, there are also some drawbacks. The main draw backs all have to do with the fact that the search options don't provide much idea as to available options to search on. The current fields are all text boxes and these can allow for a lot of user errors or just simply misinterpretation. This makes the data analysis ineffective and time consuming.

Drawbacks:

The filter method is case sensitive. Therefore if a user entered any items in upper case, the search results would not return properly. For example, if the user entered a city as "Bonita" instead of "bonita", the city would not return in the filtered data.
The user may not know exactly what period the data is from, so the user might type in dates that we don't have data for. For the date filter, the user should be able to click through a calendar.
The same issue with the Shape field, without knowing what the shape options are, the user will not know what terms to search for.

![alt text](https://github.com/RGK73/UFOs/blob/main/Images/drawbacks.png)

Recommendations for further development:

Remove case-sensitivity in all the textbox search fields.
Add a calendar selection option instead of textbox field for the Date search.
Add a drop down menu for the Shape field. This would be more user friendly as a drop down option than the textbox.
The text in the Comments section should be parsed and cleaned as there are strange symbols that can appear. These should be eliminated to make reading the comments more user-friendly.
