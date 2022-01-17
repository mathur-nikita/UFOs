# UFOs 

## Overview of UFOs Project

For this project, Dana has been given the opportunity to write an article on the topic of UFOs.  The information on UFO sightings is contained in a JavaScipt file, and Dana would like to use this file to create an HTML page that not only presents her article, but also displays a dynamic table of the UFO sightings.  The table will have filters that will update sightings information as a user enters specific search criteria.

Dana would like to have the table of findings have filters for the following information:
1) Date of UFO sighting
2) City where the UFO was seen
3) State where the UFO was seen
4) Country where the UFO was seen
5) Shape of the UFO seen

## Resources 

 - app.js, data.js
 - nasa.jpg
 - style.css

## Results

When the index.html is first loaded, you will see the following initial view:

![initial_view.PNG](https://github.com/mathur-nikita/UFOs/blob/main/screenshots/initial_view.PNG)

In order to filter for results, on the left side of the webpage you can see several text fields to enter search criteria.  You can enter your criteria in the text fields and then hit Enter on your keyboard, and the table on the webpage will automatically update to show a new table that has a filter applied to it based on what was entered.  There are default values shown in the text boxes, but they are only there to show the format in which you should supply your input.

For example, if you would like to search for a specific date (in this case "1/11/2010", you can enter the date in the "Enter Date" field and you will see the following results:

![date_filter.PNG](https://github.com/mathur-nikita/UFOs/blob/main/screenshots/date_filter.PNG)

If you would then like to search for information using a different category, you can delete the information from the field you were previously using and then enter your search criteria in another text box.  For example if you were to delete the date and instead search by a state ("fl"), you would see the following results:

![state_filter.PNG](https://github.com/mathur-nikita/UFOs/blob/main/screenshots/state_filter.PNG)

The ability to search by more than one category also exists.  In the following example both a date and a state were entered and the following results were produced:

![date_and_state.PNG](https://github.com/mathur-nikita/UFOs/blob/main/screenshots/date_and_state_filter.PNG)


## Summary

### Drawbacks
1) One of the drawbacks of this webpage is that while the user can search for multple criteria by type, the user can't search for multiple criteria of the same type.  For example if the user wanted to search for multiple cities at once or search within a range of dates, there is currently no way of doing that.

2) Another drawback is that the data presented in the table is not uniform.  There are fields that need cleaning so the data makes sense.  For example in the "duration" column some times are listed as "min" while some are listed as "minutes", and at least one item doesn't have a unit of time mentioned.


### Recommendations for any future updates to the webpage:
1) A suggestion is to allow for multiple searches across the same category type.  For example, allow the user to enter a list of multiple states to return sighting information across those states instead of only one state at a time.

2) For the date field, it would be nice to include the option to enter a range of dates instead of a single date.  This is different from the previous suggestion as the user isn't listing out each date to search individually.  The webpage would be able to take a start date and an end date as a range and return results of all sightings in that range.  

3) Another suggestion would be to include the remaining column types as search criteria (duration, comments).  The user should have the ability to search through all of the findings based on any bit of information they can go on.
