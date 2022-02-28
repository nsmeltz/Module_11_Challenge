# Module_11_Challenge

# Overview of Project: 
The purpose of this analysis was to use multiple languages to develop a webpage to display a collection of UFO sightings that a user could search through. I used JavaScript to build the data table and filter entries based on user input. I used HTML, Bootstrap, and CSS to create and stylize the webpage.

# Results: 
Upon opening the HTML file a webpage will display in your default browser. Here you will see a header with background photo (A), an article title(B) and summary(C), and filtering options(D) for the full UFO sightings data table (E).
![webpage](https://github.com/nsmeltz/Module_11_Challenge/blob/a45fd2883a7de59ebdae1376df8bbcbd757ac9f3/images/webpage.png)

Under "Filter Search" you will see 5 options for filtering the data table. You may choose to filter by any combination of the listed parameters (date, city, state, country, and shape). In each text box there is greyed out text showing the format that you must type your search parameters in. Note if the input format is not followed in EVERY box your search will not return any results(see image below).
![formaterror](https://github.com/nsmeltz/Module_11_Challenge/blob/03c44163342a79f75ce5cc66544fa55f8a51963a/images/formaterror.png)

**Example Search**
Parameters-> City = benton State = ar
![examplesearch](https://github.com/nsmeltz/Module_11_Challenge/blob/09a2b8ef5f74cbc053e381f141539fb77caf6842/images/examplesearch.png)

# Summary: 
One drawback of this design is that if you do not type the correct format in the filter boxes then the table returns nothing, which some users may interpret as there was no data for their search. I would add an error message propting the user to double check the format of the input or add a line in the code that will convert the input to the correct format to execute the search.

I think it would also be cool to take this data table and plot it on an interactive map where the user can click on a point and a pop up tells them the details that are stored in the table. The map vizualization would also help people see if there are trends on where the sightings occur.  
