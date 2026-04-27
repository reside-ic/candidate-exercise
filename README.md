# RESIDE candidate exercise

We advise you to spend about half an hour on planning out the task, finding suitable libraries and bootstrapping. After that, please spend around an hour on this exercise, and get as far as you can. We're more interested in your approach rather than completion.

## Resources
`exerciseData.json` contains mean and standard deviation values for three indicators of dengue infection: force of infection, seroprevalence in 9 year olds and hospital admissions by 5 year age groups. These values are provided for "Admin 2" (district level) regions, indicated by their IDs as defined by [GADM](https://gadm.org). The Admin 0 (country level) ID is also provided for each value.

`exerciseMetadata.json` provides human-readable label and description metadata which can be used to construct a user interface from this data.

You shouldn't need to access any other data or APIs for this exercise.

## Exercise

Create a simple web application which uses this dataset and implements the following user story:

**As a public health worker I want to see indicator values for dengue infection for regions by country, in a table format.**

For the purposes of this exercise it is not necessary to provide labels for countries or regions - you can just display the IDs from the data.

In future versions of the data and metadata, the set of indicators and/or age groups may differ e.g. a new indicator, modified labels and descriptions, or age groups of 10 years rather than 5 years. Your application should be written in such a way that such changes would be reflected automatically in the user interface.

If you have time, think about how this data could be plotted in a useful way to the user, and implement this visualisation.
For the purposes of this exercise, this should not be a geographical map, but some other type of data visualisation.

You can return your submission by email or with a link to your code. Please provide instructions on how to run your application.
