# UFOs
## Overview
The purpose of this analysis was to create a dynamic table on a webpage that can be filtered by the user of the website in order to see specific UFO encounters. Filters include: Date, city, state, country, and shape of UFO.
## Results 
The filter works by looking for exact matches of user input. Once data is entered from the user, our program looks for matches and only displays rows that match the filter. The website has been updated so that it allows for multiple filters at once
## Summary
When someone types in a date, for example, the data is saved and compared to each row of our table for an exact match. Only data that matches exactly will be displayed. This could be a problem if someone enters "California" for state instead of "ca". To fix this, we could use more placeholders to show what each entry should look like. We could also attempt to search for approximate matches instead of exact matches.
