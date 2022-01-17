# Surfs Up Analysis

## Overview of analysis
We have been provided with weather data from Hawaii.  An investor is considering opening up a surf and ice cream shop in Hawaii and wants to make sure that the business will be viable year-round, and not just in the summer months.  
Using Python and SQLAlchemy, we were tasked with analyzing the weather data.

### Resources
* Data Source: hawaii.sqlite
* Software: Python 3.8.8, Jupyter Notebook, SQLAlchemy


## Results

### Three key differences in the weather between June & December
*  The weather in June is much more consistent than the weather in December.  The standard deviation for June is 3.26 while the standard deviation for December is 3.76.  That's a noticeable difference in predictability.
*  The maximum temperature doesn't fluctuate much year round.  The max in June is only 2 degrees higher than the max in December.
*  The minimum temperature is only 56 in December, while it's 64 in June.  There are (not surprisingly) many colder days in December than in June.

## Challenge Summary
On the surface, these results seem to make sense.  Hawaii is in the northern hemisphere so December should be colder overall than June.  It's not surprizing that there is more fluctuation in the temperatures during December.
Our wealthy investor will have to decide if that is an acceptable risk for moving forward with the business, or if that means that business will be bad in the winter months.
 
### additional query #1
The weather data that was provided also includes precipitation readings.  It could be useful to know how often it rains in each month as well, as rainy days could potentially affect the number of days that are good for surfing.  

### additional query #2
We have analyzed data from June and December, but the surf shop needs to be a viable business all year round.  It could be helpful to also get information from the months of March or April and September or October, so there are samples of data from the spring and fall seasons as well. 

