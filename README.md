# UFO Sightings

## Overview of the Project

Dana, a data journalist, is working on a research article about UFO sightings. In the end, she will be showcasing her article online, displayed on a webpage alongside a table of data to support her findings. The JavaScript file that holds the data that Dana will be using contains many pieces of information regarding UFO sightings, including countries, cities, states and the type of siting. 

The purpose of this assignment was to use JavaScript’s visual functionality to display this data as a table and provide more in-depth analysis of the UFO sightings by allowing the website users to filter the table by multiple criteria at the same time. 

## Results

<img align="right" src="https://github.com/hollyouellette/UFOs/blob/main/resources/filter_search_list.png" width=200>
<figcaption> Fig 1 - Empty filters showcasing the entire dataset on the table. </figcaption>
 
Using this new webpage, we are able to filter by one or multiple search parameters based on the user’s area or areas of focus in the dataset.<br> 

To start, the user enters their desired filter. By pushing ‘tab’ or ‘enter’ on their keyboard or simply clicking outside of the input box, the website responds immediately, showcasing only the rows of data that contain the filter entered by the user. The user is also able to refine their search by adding additional filters that are more specific to their data of interest.

After entering a filter, if the table showcases no data then one of the following errors has occurred:
1.	The filter entered is spelled or formatted incorrectly. 
2.	The filter entered does not exist in this table’s data.
3.	The filter parameters are too specific and there is no row within the table that matches all of the conditions.

Summary

A drawback of this table is that it requires a knowledge of the values that each column contains in order to use the filter function. For this reason, it would only be useful to an analyst who is seeking specific data from the table. This table would not be useful for exploratory research because the user must know exactly what they are looking for (and how it is formatted) prior to using the filters.

Two recommendations for further development:

1.	Introduce the functionality to sort the data based on the filter-able column values (eg. sort table by date). This would enable a user to identify trends in the data based on the column values they are using to sort.
2.	Introduce checkbox filters that list the data that exists in the table vs. requiring the user to type their input. This would make the table more friendly to exploratory analytics and will reduce potential human error in the filtering process. 
![image](https://user-images.githubusercontent.com/75281769/111088850-8c482f80-84ff-11eb-9621-5403d5dab17e.png)
