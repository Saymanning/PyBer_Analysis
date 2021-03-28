# PyBer_Analysis
There is a title, and there are multiple sections
Each section has a heading and subheading
Links to images are working and displayed correctly
# Overview of the analysis:
The purpose of this analysis is was to create a summary DataFrame of the Pyber ride-sharing data by city type. For visualization of the analysis, a multiple-line graph that shows the total weekly fares for each city type was created using Pandas and Matplotlib.
# Results: 
Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
There is a description of the differences in ride-sharing data among the different city types. Ride-sharing data include the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type.

**Ride-sharing summary DataFrame by city type

-Used the Pandas groupby() function with the count() and sum() methods on PyBer DataFrame columns, to get the total number of rides, total number of drivers, and the total      fares for each city type. 

-Next, the average fare per ride and average fare per driver for each city type was calculated.

-Finally, this data was added to a new DataFrame and columns were formatted.


A DataFrame was created using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time.
A DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare."
A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-29.
A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week.
An annotated chart showing the total fares by city type is created and saved to the "analysis" folder.

**Multiple-line chart of total fares for each city type

-Using functions, pivot() and resample(), create a multiple-line graph that shows the total fares for each week by city type.

# Summary:
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types.
