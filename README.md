# UFO

## Overview 

The overview of this project was to help our friend share information about UFO sightings around the United States. She asked for our help to create an interactive website where the end user can filter the data set and return only values the user is interested in. 

## Results 

The photo below is a snap shot of the filters and the data site that the end user will see when they go to our website. 

### Website View
![Website View](https://github.com/mccoycory/UFO/blob/main/Filter%20Overview%20Page.png)

The photo below is a snap shot of the returned data with two filtered data. The data is filter by both city and date. 

### Website View with filtered data

![Website Filtered Data](https://github.com/mccoycory/UFO/blob/main/Filter%20with%20Search.png)

This front end view was created using Java and HTML. HTML was used for spacing and style of the website; whereas, Java was used to perform the actual filtering of the data. Our friend did a wonderful job creating the HTML website for us; however, she needed some help with the actual filtering of the data. The first thing we needed to complete was grabbing user input from the website. We did this below by using the d3.select(this) method, which basically grabs anything from that the user inputs. After saving this input, and we grabbed the "value" of it and finally grabbed the location where it is stored in the HTML id tag. Please reference below for sample code. The last part is saving the user input into a key,value pair.

### Grabbing user input 

![Grabbing User input](https://github.com/mccoycory/UFO/blob/main/Filter%20Code.png)

Once the key,value pair is saved from the user input, we created a Foreach loop that would look over the whole data set and return only an exact match of the key,value pair in table form. 

### ForEach Loop over Table 

![For Each Loop](https://github.com/mccoycory/UFO/blob/main/Filter%20For%20Each%20Loop.png)

## Summary 

Overall this website is very interactive with the user. However, one of the main drawbacks is the whole data frame shows up when you open up the website. As this data set grows, it will take pages and pages of the website. This could be better if there was a "show more" bottom for the user to keep the page simple when you open it up. A couple more additional functions would be an automated "fill" as the user starts typing in the filter. Also, an export to csv would be great as well. This would allow the user to export all the data if they wanted to. 

