# UFO Sightings 

## Project Overview

Dana has a .js file with data about UFO sightings in the US, this data is stored as a JavaScript array. We created a fully dynamic table to organize UFO data that has the ability to filter data based on certain criteria entered by the user. The table was created using JavaScript as the primary coding language, it was then placed in an HTML file (webpage) for easy viewing, and finally, we used Bootstrap to customize the webpage visualizations.

## Results

When you first open the UFO Sightings webpage, you see an introduction that talks about the data that supports the existence of aliens and the table that holds evidence of UFO sightings. 

![]()

After the webpage summary, you find the table that lets you search for UFO sighting records across the US. The complete list of sightings is preloaded so you can see all the fields, but you can filter the table contents by date, city, state, country, and shape.

![]()

For example, let’s say you only want to see UFO sighting reports in Florida. You go to the “Filter Search” section, at the left side of the table, in the “Enter State” field, you enter “fl” and press “Enter” on your keyboard. As you can see in the image below, the table is now showing all the records for Florida only. 

![]()

You can further refine your search by applying any additional filters you’d like, for example, the image below now shows results for UFO sightings in Florida that were reported to have a “fireball” shape.

![]()

## Summary

See the bullets below for more details on the table’s drawbacks and recommendations for further development.

* Drawback:The search filter is case-sensitive. The user will usually try to type some filters using upper case values, for example, the in the state field. We’re used to type state abbreviations in upper case letters, but the table won’t show any results if the filter input is not an exact match. Recommendation: We could further develop the search filter code to be case-insensitive, edit the data.js to fix word capitalization, or add a message to the user advising them that the filter section is case-sensitive.

* Drawback: The search filter options are incomplete or can be improved. What if a user wants to filter by duration? Or how is the user supposed to know all the types of shapes?Recommendation: We can edit and clean the data.js file to make the duration field consistent and add a filter that lets the user select from a dropdown. Some options could be “less than a minute”, “1-15 minutes”, etc. The shape filter could also be edited to be consistent and changed to a dropdown so the user sees all the available options.

