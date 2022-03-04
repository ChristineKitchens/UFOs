# UFOs
## Overview
The following project is part of a mock client assignment using JavaScript and HTML to make a dynamic webpage containing UFO sighting information. The client requested a webpage to 1) feature their article on UFO sightings and 2) a dynamic table of sightings that users can view and filter according to their criteria. Filter criteria include the following:

- Date (1/1/2010-1/13/2010)
- City
- State
- Country
- Shape
## Analysis
The client deliverable can be viewed by opening the [index.html](https://github.com/InRegards2Pluto/UFOs/blob/28f0901e87378c44f871cba3710697d8f3bfa7c7/index.html) file inside of a web browser. The user can scroll down the page to see all entries in the unfiltered table. 

### How to Filter Table
To filter rows, type the desired filter criteria into the filter form box to the left of the table.

![step1.png](https://github.com/InRegards2Pluto/UFOs/blob/28f0901e87378c44f871cba3710697d8f3bfa7c7/images/step1.png)

To add a filter criteria, click into any of the input boxes on the form and begin typing. For example, "1/13/2010" was entered into the date input box in the example image below. No button needs to be clicked. The table will update automatically after clicking out of the box.

![step2.png](https://github.com/InRegards2Pluto/UFOs/blob/28f0901e87378c44f871cba3710697d8f3bfa7c7/images/step2.png)

As many or as few filters can be used as desired. For example, "ackerman" was entered into the city input box in addition to the "1/13/2010" value already added. As seen in the below image, this further refinines table results.

![step3.png](https://github.com/InRegards2Pluto/UFOs/blob/28f0901e87378c44f871cba3710697d8f3bfa7c7/images/step3.png)

### How to Clear Filters From Table
To clear filters from the table, either refresh the browser or manually delete any values entered into input boxes.
## Summary
There are some drawbacks to the new design. For example, to reset the table after applying the filters, the user either needs to manually delete the filter values or refresh the browser. Also, it might not be apparent to the user the different values that can be chosen for a given filter. For example, while someone might be able to guess that one entry for the "shape" field could be a circle, it's challenging to guess what other options are available without sifting through the whole data set.

Therefore, for futher development, it's recommended that the filter input boxes be ammended to include a dropdown menu of potential values. It's also recommended to install a reset button that clears out all the filters on a click event.

## Resources
- Data Sources:
  - [index.html](https://github.com/InRegards2Pluto/UFOs/blob/28f0901e87378c44f871cba3710697d8f3bfa7c7/index.html)
  - [app.js](https://github.com/InRegards2Pluto/UFOs/blob/28f0901e87378c44f871cba3710697d8f3bfa7c7/static/js/app.js)
  - [data.js](https://github.com/InRegards2Pluto/UFOs/blob/28f0901e87378c44f871cba3710697d8f3bfa7c7/static/js/data.js)
  - [style.css](https://github.com/InRegards2Pluto/UFOs/blob/28f0901e87378c44f871cba3710697d8f3bfa7c7/css/style.css)
- Software:
  - VS Code

- Languages
  - Java Script, HTML, CSS
