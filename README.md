# code301-lab02
We are creating a photo gallery styling it with floats.

# Build Process

#Feature #1: Display images
Start time:
Finish time:
Actual time needed to complete:

##Why are we implementing this feature?
As a user, I want to view the images on the page so that I can browse the photo collection.
##What are we going to implement?
Given that a user opens the application in the browser
When the user navigates to the home page
Then the photo gallery should display all of the images in the gallery
##How are we implementing it?
Use AJAX, specifically $.get(), to read the provided JSON file.
Each object should become a new instance of a constructor function. Refer to the data to determine the necessary properties.
Use jQuery to make a copy of the HTML template of the photo component. For each object, fill in the duplicated template with its properties, then append the copy to the DOM.


#Feature #2: Filter images
Start time:
Finish time:
Actual time needed to complete:

##Why are we implementing this feature?
As a user, I want to be able to filter the images so that I can view only images that match a keyword.
What are we going to implement?
Given that a user clicks on the dropdown menu
When the user selects one of the options
Then only the images whose keyword matches the option should be displayed
##How are we implementing it?
Create a <select> element which contains unique <option> elements extracted dynamically from the JSON file, one for each keyword.
Use an event handler to respond when the user chooses an option from the select menu. Hide all of the images, then show those whose keyword matches the option chosen.
  
  
#Feature #3: Style the application
Start time:
Finish time:
Actual time needed to complete:

##Why are we implementing this feature?
As a user, I want a simple, clean looking UI so that my photo gallery clearly displays the images in a grid like pattern.
##What are we going to implement?
Given that a user opens the application in the browser
When the user navigates to the home page
Then the images should be displayed in rows across the screen
##How are we implementing it?
Style your application using floats.
Utilize at least one Google font.


#Stretch Goal: Sort the images
Why are we implementing this feature?
As a user, I want to be able to sort the images so there is an order to how they render.
What are we going to implement?
Given that a user is presented with sort options
When the user clicks on one option
Then the images should be sorted accordingly

##How are we implementing it?
Add the ability for the user to sort the images by either title or by number of horns.
Sort the images by one of the properties on page load. This should also apply to the second page of images.

#Code style
js-standard-style

#Credits
Pair-programming with Corey and Sarah

#License
MIT © Sarah Fisher
