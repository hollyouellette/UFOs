# UFO Sightings

## Overview of the Project
<br>
  Dana, a data journalist, is working on a research article about UFO sightings. In the end, she will be showcasing her article online, displayed on a webpage alongside a table of data to support her findings. The JavaScript file that holds the data that Dana will be using contains many pieces of information regarding UFO sightings, including countries, cities, states and the type of siting. 
<br>
  The purpose of this assignment was to use JavaScript’s visual functionality to display this data as a table and provide more in-depth analysis of the UFO sightings by allowing the website users to filter the table by multiple criteria at the same time. 
<br><br>

## Results
<img align="right" width=550 src="https://github.com/hollyouellette/UFOs/blob/main/resources/multiple_filters.png">
Using this new webpage, we are able to filter by one or multiple search parameters based on the user’s area or areas of focus in the dataset.<br> 

<br>
To start, the user enters their desired filter. By pushing ‘tab’ or ‘enter’ on their keyboard or simply clicking outside of the input box, the website responds immediately, showcasing only the rows of data that contain the filter entered by the user. The user is also able to refine their search by adding additional filters that are more specific to their data of interest.
<br><br><br>

After entering a filter, if the table showcases no data then one of the following errors has occurred:
1.	The filter entered is spelled or formatted incorrectly. 
2.	The filter entered does not exist in this table’s data.
3.	The filter parameters are too specific and there is no row within the table that matches all of the conditions.
<br>

_Example:_<br>

<img width=600 src="https://github.com/hollyouellette/UFOs/blob/main/resources/no_matches.png">


## Summary
<br>
A drawback of this table is that it requires a knowledge of the values that each column contains in order to use the filter function. For this reason, it would only be useful to an analyst who is seeking specific data from the table. This table would not be useful for exploratory research because the user must know exactly what they are looking for (and how it is formatted) prior to using the filters.
<br><br>

**Two recommendations for further development:**
<br><br>
1.	Introduce the functionality to sort the data based on the filter-able column values (eg. sort table by date). This would enable a user to identify trends in the data based on the column values they are using to sort. <br><br>
2.	Introduce checkbox filters that list the data that exists in the table vs. requiring the user to type their input. This would make the table more friendly to exploratory analytics and will reduce potential human error in the filtering process. 

