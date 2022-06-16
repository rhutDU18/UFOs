# UFO Analysis Overview


The purpose of this analysis was to help Dana storyboard her UFO website so our first task involved creating a dynamic table of UFO data collected in 2010 and present it in a JavaScript library.  We added extra filters such as date, city, state, country, and shape to our table storing various properties and objects.  Once we built our table we developed an interactive webpage supported with bootstrap features to create an overall better visualization experience for the user.

## Results 

Users have 5 different filters they can chose from which can help better define and narrow down a search.  For example, a user interested in seeing accounts of UFO sightings in a specific state can scroll down to the 3rd filter and search a state by its abbreviation. In this case the user selects the filter "co" to access all logged UFO reports in the state from 2010 in our JavaScript library.

![This is an image](https://github.com/rhutDU18/UFOs/blob/main/static/images/UFO_Filter_CO_Screenshot.png)


Once a user has selected their desired filter they then select the second filter, our click function which tells our D3.js or Data-Driven Documents to listen for events such as a click. This tells the HTML page to filter the table and display a visualization of all reports of UFOs in Colorado for the interested user. 

![This is an image](https://github.com/rhutDU18/UFOs/blob/main/static/images/UFO_Table_CO.png)

### Summary Insight and Suggestions

 - One drawback about this webpage is that you need to reload the HTML to clear the filter. 

 - A larger dataset that included reports from other years could expand the number of ways you could visualize the data. Using plot.py to display UFO sighting trends between different years and areas could add more depth to the webpage for users. 


 - Developing a section of the HTML page that is devoted to updating users with the latest UFO related news using web scraping techniques such as using Splinter or BeatifulSoup to pull interesting data from Dana's favorite UFO related HTML pages assuming the selected websites don’t prohibit web scraping.   









