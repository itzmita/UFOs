# UFO Sightings
# Learning Javascript, Bootstraps

## Project Overview
The purpose of this project was to learn how to use JavaScript to store data in list or arrays or objects and display UFO sighting data in html file. We learnt how to make a dynamic webpage where an user can input a search box and with the click of a button the page should refresh to consider that filter criteria and display the data accordingly. The filters were modified with event listeners that can record when a change happens and take an action on that event. We used HTML, Bootstrap, CSS to create a webpage that make a page aesthetically look good, has search boxes and images etc.
Topic
Are humans alone in this universe? For millennia, humans have turned to the sky to answer this question. UFO sightings have been an obsession among many for centuries.  In this assignment we are helping Dana to craete a webpage in which others can access information of reported sightings and see for themselves. This webpage should include:

* A description or summary of the topic
* A table to display all of the information from a static data source
* Search filters that will allow for users to search the table based on the search criteria they enter.
	
## Results
Below is a snapshot of the webpage that was created which has the above 3 points displayed.


![image](https://user-images.githubusercontent.com/3753839/174229324-af521dbf-7ed2-429c-ab44-8ca3937b1385.png)




The following part is where the searches can be done by a date, city, state, country or shape.
![image](https://user-images.githubusercontent.com/3753839/174229737-a0b08006-232f-4af9-9b2e-205c7aa4ea19.png)




Users can filter by one or all of the search criteria shown. For example, if you search by "City", you will see that the table updated to show the reported sightings that was recorded for that specific city.
![image](https://user-images.githubusercontent.com/3753839/174229836-93220187-4931-416c-b2be-73abd5dfbb18.png)



If you search by a state, the table will update filtering further to only display the information containing that state.

![image](https://user-images.githubusercontent.com/3753839/174229859-53f6c791-7dba-4883-b9ed-35f0edba5213.png)



If you search by a country, the table will update filtering further to only display the information containing that country.

![image](https://user-images.githubusercontent.com/3753839/174229882-59cce7e8-2fc8-4fea-9c0c-da70dd09526c.png)


If you search by a shape, the table will update filtering further to only display the information containing that shape.
![image](https://user-images.githubusercontent.com/3753839/174229894-e2d6af1f-728f-41ab-bdc1-fa7c75dc382d.png)


You can also search by multiple criterion 
For example if you search by shape triangle and state as ca the following shows up

![image](https://user-images.githubusercontent.com/3753839/174229908-d5ea690d-3722-4924-9e3c-964ff3e6c858.png)


## Summary
### Drawbacks:
Unfortunately, the page has few drawbacks of which one is 
* The source data is taken from data.js which is static. It would be nice if we can connect to a live website and scrape the data and then present in the screen. 
* The search can be made case insensitive for ease of users.

### Recommendations for further development:
We can do some more changes to make it more user friendly.
* In the search box, if we could have added a functionality to have a prompted search as the data is static here. We know the list of states, countries, shapes etc. We can make an array of these elements and prompt them when a user tries to enter a data.
* Search could have been extended to more countries
* Latest UFO sighting can be displayed in a separate section.
* It would be also nice if there is a button to say "click me" or "enter" etc.
	

