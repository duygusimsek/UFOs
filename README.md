# UFOs


## Overview  
 
The purpose of this project was to build a webpage to display information about UFO sightings. The webpage had designed dynamically which accepts the user’s inputs and adjusts accordingly to indicate the information that was searched. To perform the analysis, the user will be able to filter the UFO sightings information table, based on the date of the event, city, state, country, and shape criteria. 

## Result

The [Truth is Out There](https://github.com/duygusimsek/UFOs/blob/main/static/Images/image_1.png) webpage was created to help the users to find out about UFO sightings. To attract attention, the page view was designed with an opening passage about UFOs, and at the bottom of the page, users input the filter table, and the sighting information table was displayed.

![The page view](https://github.com/duygusimsek/UFOs/blob/main/static/Images/image_5.png)

Using JavaScript and HTML, the [index. html](https://github.com/duygusimsek/UFOs/blob/main/index.html) file was modified to create more table filters. In addition to the date filters that had been created before, the city, state, country, and shape filters were added. [Filter table](https://github.com/duygusimsek/UFOs/blob/main/static/Images/Filter_table.png)

In order to react to an element that was changed, the Javascript functions were used to loop through the data to build the table and create a customized dashboard. [app.js](https://github.com/duygusimsek/UFOs/blob/main/js/app.js)

The user will be able to filter one or all of the search criteria that are shown.  If,  they search by “city”, the information table’s display will be updated to only the reported sightings that were recorded for that specific city.

![City_Filter](https://github.com/duygusimsek/UFOs/blob/main/static/Images/image_3.png)

If the user uses the shape filter, the table will update filtering further to only display the information containing that shape.

![Shape_Filter](https://github.com/duygusimsek/UFOs/blob/main/static/Images/image_4.png)

Or if they delete the previous entries and enter new filters, the table will be updated by using the new criteria.

## Summary


## Sources

* Data Source: [UFO Sightings Data - data.js](https://github.com/duygusimsek/UFOs/blob/main/js/data.js)
* Software: [Visual Studio Code, 1.65.2](https://visualstudio.microsoft.com/downloads/)
* Language: JavaScript 
