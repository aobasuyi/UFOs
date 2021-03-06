# UFOs sightings with JavaScript 	
**Purpose:**  To build a dynamic table of data using Javascript and display it online using an HTML file.<br />

## Overview of the analysis

Javascript will be used to build a table of UFOs sighting information to support a data journalist's news article. The dynamic table of data and the news articles will be displayed online to support findings. The table will have easy to use filters to finetune the UFOs findings results. <br />

This project has one technical analysis deliverable as shown below, <br />

- Filter UFO sightings on multiple criteria

## Resources
- Data Source: This analysis was performed using the [data.js](https://github.com/aobasuyi/UFOs/blob/main/static/js/data.js) dataset.
- Software: ES6, Javascript;  Visual Studio Code, 1.56

## Results
An in-depth analysis of UFO sightings is made possible by allowing users filter the table for multiple criteria at the same time. <br /> <br />
**UFO Sightings News:** <br />
- Users will be presented with the news article and the unfiltered UFO sightings information table. They can scroll down the page to see all UFOs sightings.

<br /> ![Image](static/resources/UFO_webpage.png) 
<br /> ![Image](static/resources/Unfiltered_table.png) <br />

**UFO Sightings - search by date:** <br /> <br />
Users have the option to filter the table of UFOS sightings information using multiple criteria at the same time or they can search using one criterion such as date only (as shown below) <br />
<br /> ![Image](static/resources/Search_date.png) <br />

**UFO Sightings - search by date:** <br /> <br />
For more in-depth analysis of UFOs sightings, users can filter the table by entering a date, a city of interest, a state, and a shape. The result below shows the filtered table using the following search criteria: (**Date:** 1/1/2010,  **State:** ca and **Shape:** light).<br />

<br /> ![Image](static/resources/Search_date_state_shape.png) <br />


## Summary
- One drawback of this webpage is that users will need to refresh page either using the "enter" button or clicking the page "refresh" button each time they initiate a new query. 
- Two recommendation for further development include
    - Option to further refine search by adding more search elements within a unique criterion (e.g **State:** ca, fl).
    - Option to select time range (e.g **Duration:** > 1 minute)
