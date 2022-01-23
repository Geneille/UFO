# UFO

## Project Overview

Creating dynamic tables on webpages where users can interact with the data and filter to their specifications can create a rewarding experience for the user. The main aim of this project was to create a dynamic webpage and table of UFO sightings that allow users to filter for multiple criteria at the same time.

## Tools, Resources and Language

* VS Code 1.63.2
* Javascript ES6, HTML
* D3.js JavaScript library, Bootstrap CSS

## Analysis

1. The data source used in this project (filename: data.js) contains an array of data
related to UFO sightings.

2. A webpage was created for the data and written in HTML (see file index.html). Within this file specific styles was referenced for use and modifications were made to make the webpage more visually appealing. In addition, links and 'script' tags were used to reference/link to other code to build the webpage.

3. Code was written in Java (see app.js file) to parse the data and interact with the HTML script using the D3 library. Within this file, functions were created to parse the data and information to the webpage and to ensure the table data loads accurately on the webpage. Additionally, script was written to allow the user to filter the table information based on a set of criteria. This was achieved by using d3 'Eventlisteners'.

## Results

The following image (Figure 1) shows the webpage without any filter applied for the table information. This is the default view when the webpage loads. 

Figure 1: The default unfiltered table

The following images illutrates how the user can interact with the information. The user inputs their filter criteria and the resulting filtered information is then displayed in the table. The user can use the 'filter' button to initiate the search and the 'reset' button to reset the table to the defalut unfiltered table.

Figure 2: Image showing filtered table with criterion "light".


Figure 3: Image showing filtered table with two criteria "light and el cajon".


## Summary

The webpage in its current state effectively displays the information provided. However, one drawback is that the information is static and not regularly updated based on current events/sightings. Two recommendations to improve the webpage and hence user experience would be: 

* utilize webscpraping, from open source websites, to search for current updates and sightings. This would ensure current information is displayed for the user.

* allow users to log their sightings and or images, or a link/contact information where users can input their sightings for review and validation by the development team.
