# UFOs - Interactive Webpage
## Project Overview
### Purpose of the analysis
This project aims to help Dana, a data journalist, showcase her UFO-sighting information by implementing JavaScript and HTML to create a webpage displaying the UFOs data as a table, wherein the data can be filtered by the user-input criteria such as date, city, state, country, and UFO's shape.

### Resources[^1]
+ **Languages:** JavaScript, HTML, CSS
+ **Editor Tool:** Visual Studio Code
+ **Data source:** [data.js](https://github.com/asama-w/UFOs/blob/main/static/js/data.js)
+ **Scripts:**
	+ [index.html](https://github.com/asama-w/UFOs/blob/main/index.html) 
	+ [app.js](https://github.com/asama-w/UFOs/blob/main/static/js/app.js)
	+ [style.css](https://github.com/asama-w/UFOs/blob/main/static/css/style.css)

## Project Results
### How to filter the webpage
#### 1. Webpage Overview
The following image shows the outline of the webpage displaying all information in the table without any filter applied. <br/>Users can input the desired filters in the white boxes as indicated under the Filter Search section on the left-side of the webpage.

<img src= https://github.com/asama-w/UFOs/blob/main/Additional_images/webpage_challenge_before_filter.png width="100%" height="100%">

#### 2. Filter Box 
The close-up image of the Filter Search section. 
+ Input the desired filters following the sample input-data template in the white boxes, the press enter or click elsewhere on the webpage. The UFOs information in the table will then displayed as filtered.
> Please note that the input is case-sensitive.
<img src= https://github.com/asama-w/UFOs/blob/main/Additional_images/filter_box.png width="30%" height="30%">

#### 3. Examples of Tables Outputs After Applying the Filters
+ **Applying Country Filter:**
When users want to filter the country, input country abbreviations into the country filter box. <br/> As shown in the following example, filtering only "ca" in the country filter box, the table returns UFOs data for "ca" or Canada.
<img src= https://github.com/asama-w/UFOs/blob/main/Additional_images/country_filter.png width="100%" height="100%">

+ **Applying Date:**
Input date in the D/MM/YYYY format, as shown in the Date filter box.
<img src= https://github.com/asama-w/UFOs/blob/main/Additional_images/date_1.png width="100%" height="100%">

+ **Applying Date and Shape Filters:**
To also filter the shape, input user's desired shape, such as triangle, circle, light, etc., in the Shape filter box.
<img src= https://github.com/asama-w/UFOs/blob/main/Additional_images/date_shape_2.png width="100%" height="100%">

+ **Applying Date and State Filters:**
Input the state abbreviation in the State filter box.
<img src= https://github.com/asama-w/UFOs/blob/main/Additional_images/date_state_3.png width="100%" height="100%">

+ **When The Applied Filter Returns No Matches:**
The table shows no data when there is no match with the inout filters.
<img src= https://github.com/asama-w/UFOs/blob/main/Additional_images/filters_no_match.png width="100%" height="100%">

## Project Summary

### Drawback of the Webpage Design
+ The design of the filter section is not clear, there is no button for the user to click, such as "Apply Filter" or "Filter Table" button that indicates the application of the input filters when pressing enter on the keyboard.
+ The input filters are case-sensitive and require an exact match, for example, if the users input a capital letter for the city name, no information will be displayed in the table as it does not match with any data.

### Recommendations for Further Development
+ We can modify the scripts to display a message such as "No Results Found, please try another search" instead of displaying a blank table for the no-match results when the input filter does not match with any data in the database.
+ For the filter section, a dropdown list can also be added for each filter to guide users of the filter options, as well as two addtional buttons, one to "Apply Filter(s)", and another one to "Clear All Filter(s)".

[^1]: `.gitignore` template for JavaScript is from [here](https://github.com/asama-w/UFOs/blob/main/Additional_images/filters_no_match.png)
