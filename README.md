# UFOs

## Overview of Project
Dana has asked us to help explore UFO data. She wants us to use javascript to build a webpage that includes a dynamic table. This table will allow users to filter multiple criteria, including filters for city, state, country, and shape.

## Results
Below are two screenshots from the webpage:

![UFO_1](https://user-images.githubusercontent.com/91795475/147427883-34459be3-3436-48a8-8830-1ba28f3c0c8d.png)

![UFO_2](https://user-images.githubusercontent.com/91795475/147427886-00c0ba28-4d51-4ab8-9d6e-0cae37b4c43f.png)

We can see on the left hand side, there is the Filter Search. Searching is simple: all that is needed is an input into one of the white boxes. If you click on a box and type out the desired search, the table will update with any matches. To clear the search, all you have to do is delete the text and the table will revert back to its original form.

## Summary

As useful as this table is, it is not perfect. One drawback of this table is the strict parameters. For example, a search for the city "St. Louis" needs to be all lowercase and the decimal point after "st". If it does not match exactly, the desired results will not appear. I would recommend a couple things to improve the webpage. For one, allowing the filter to account for small human errors including case errors or a small spelling error would benefit the user tremendously. One last recommendation I would make would be to find a way to update the table over time as more UFO spottings happen. As of now, there is no way to update the data other than manually adding to the data.js file. Ideally, there would be a way to automatically import more data and update the table.
