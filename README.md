# UFO

## Overview 
### Background
A data journalist named Dana has a special interest in UFO sightings. Dana is from a small town named McMinville, which is famous for its UFO sightings. To write her story, Dana has created a JavaScript file full of the necessary information on sightings in the McMinville area. The data is organized by date, city, state, country, shape of object sighted, and a description of the sighting. Dana has created a website with the cleaned up data that serves readers the ability to search for sighting by date.
![dana_website](https://user-images.githubusercontent.com/94096530/164345726-50f75049-9a7b-40e2-888c-d36aa45bc3ab.jpeg)

### Purpose
The purpose of this project is to provide readers the ability to look deepy into the data on UFO sightings. Adding filter criteria will allow people to input specific values as filters and extract the exact data they want. The following filters will be added: city, state, country, and shape of the object sighted. 

#### Resources 
1. JavaScript
*   Used for the script files that contain the data of the sightings 
*   Used for the file that implements the (d3.js)-- the data driven documents library
2. HTML
*   Used to construct the website by implementing Bootstrap elements 
*   CSS styling to format the website 

### Process
To advance Dana's website to filter more specific data, we need to change a few things:
* 1. Filter the data by reading in the user input data. This is implemented in the app.js script. Next, the d3.select will be used to capture the filters that we want to use. 
* 2. The filtered data will come fom the "filtered data" function. The purpose of this function is the take the specified filters and return the corresponding values that match the filtered data.
* 3. We will format the filtered data on the webpage using the HTML CSS styling. This will properly format our website. The formatting can be found in the style.css file.

### Navigating the Website
If you want to filter specific sightings form the website, the user can select the specific date, city, state, country, or shape of object sighted. Then, the website will return a data table with the values that match the filtered data. The filter input can be found on the left hand side of the website. 
<img width="1440" alt="filter_input" src="https://user-images.githubusercontent.com/94096530/164347717-d981bf26-048a-42a5-8af6-bf97130b7e11.png">
To return back to the unfiltered data, te user can select the quick return button embedded into the HTML. In the upper-left corner of the webpage, the user can click "UFO Sightings" to return back to the unfiltered data page. 
#### Example (Using the Filter)
To see the sightings in California on 1/4/2010 the filter would read the following: 
![filtered_webiste](https://user-images.githubusercontent.com/94096530/164348284-cb56c2be-820b-4fa0-8944-4b7b8ae40a42.jpeg)

### Summary
Since JavaScript is case sensitive, the format of the user input in the filter must match the format of the placeholder that is in the original filter. For example, when the user inputs the filter for a particular city, all letters must be written in lowercase. If you were to input "Fresno" into the dataset, the data table would be empty since the city had a capital letter in it. 
<img width="1440" alt="incorrect_filter" src="https://user-images.githubusercontent.com/94096530/164349063-618985ee-07bd-4ed3-b0ab-bb20a33e782b.png">

### Recommendations
If Dana wanted to futher develop her website, she could consider adding a filter on the shape of the object sighted. She could do this by including a drop-down of the potential shapes that could be chosen and have a user select from the provided drop down list. 

Another recommendation would be to allow the user to download the filtered data sets so that they UFO experst can study the data and write an analysis on the information.

