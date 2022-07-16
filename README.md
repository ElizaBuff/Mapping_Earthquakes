# UFO Analysis 

## Overview of Project
### Purpose of Project
In this project, I demonstrated my proficiency with various JavaScript and HTML features including: using console.log() to debug code, d3.select(), arrow functions, forEach() with JavaScript objects, filters with d3.select(), if-else statements, list-group-item class, label, and input tags to add filtered data to an index.html file, and script tags to an index.html file. 

### Background of Project
Dana, a journalist, has a JavaScript datafile about UFO sightings that she wants to organize and display. I built a table using data stored in a JavaScript array. Then, I created filters that it will react to user input, and placed the table into an HTML file for easy viewing. Users will be able to search the data by date, city, state, country, and shape of the UFO sightings. 


---
## How to Perform a Filtered Search 
The “Filter Search” allows users to search for UFO sightings by date, city, state, country, or shape. The search can be done using any combination of filters. For example, a user could search by just the state of Oregon, just triangle shaped UFOs, or by a combination of the state of Oregon and triangle shaped UFOs.  

### FORMATING 
* Date is entered as MO/DA/YEAR
* State and Country are entered using their two letter abbreviations 

### HOW TO SEARCH 
ADD FILTER 
* Choose any filter  
* Type your criteria 
* Hit Enter [table will adjust] 
* OPTIONAL: repeat for remaining filters


REMOVE FILTER 
* Choose filter you want to remove
* Delete text
* Hit Enter [table will adjust]

    

### EXAMPLE
**Example 1: You want to search for sightings in the state of Oregon**
ADD FILTER 
* Choose any filter = "I want to search by the *state* of Oregon."  
* Type your criteria = The abbreviation for Oregon, "or", is typed under "Enter a State". 
* Hit Enter = The table will look like the image below. 
![filter_or](static/images/filter_or.png)

**Example 2: You want to adjust your search so the table displays sightings in the state of Oregon that were in the shape of a triangle**
ADD ANOTHER FILTER 
* Choose any filter = "I want to add triangle to the *shape* filter."  
* Type your criteria = Type "triangle" under "Enter a Shape". 
* Hit Enter = The table will look like the image below. 
![filter_or_triangle](static/images/filter_or_triangle.png)
 
**Example 3: You want to adjust your search so the table displays sightings that were in the shape of a triangle**
REMOVE FILTER 
* Choose filter you want to remove = "I want to remove the *state* of Oregon."  
* Delete text = Delete "or" typed under "Enter a State". 
* Hit Enter = The table will look like the image below. 
![filter_triangle ](static/images/filter_triangle.png)

---
## Summary
### Limitations 
The placeholder, a short hint that describes the expected value, is a useful visual affect for the user. However, it can be unclear what the table is displaying when the placeholders for unused filters remain after the initial filter is applied. My recommendations below, outline how to make the table easier to interact with and read. 

### My Recommendation 
To enhance readability, a line of text can be added above the table to outline what search results it is displaying. For example, if the user searches for "or" and "triangle", the line of text would read *This table shows all results for UFO sightings in the state of Oregon and triangle shaped.* 

To enhance user experience, the state, country, and shape filters can be changed from an entry to a dropdown. Users might struggle if (1) they do not know state or country abbreviations, (2) misspell something, or (3) don't know what shapes to search for. A dropdown would allow users to know every possibility in each filter and accurately search for them each time. 

