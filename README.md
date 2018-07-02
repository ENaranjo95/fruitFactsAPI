# fruitFactsAPI
This runs a local host server 8000 and shows the different facts of our selected fruits in our API.

## How It's Made:

**Tech used:** HTML, CSS, JavaScript and Node-JS

In the index.html I used a select tag for the different fruits store in our API, a button tag to run our JavaScript function, heading tag, span tag, image tag to display the result in the DOM. The main.js runs when the user clicks on the button. When the button is clicked, the value stored in each option tag, stored in each fruit respectively, is passed as a parameter to the server.js. The fruit name is passed as a parameter, then the respective fruit information is passed through the JSON and sent to the main.js. The main.js receives this JSON and parses the information and displays it in the DOM for each respective bit of information called on.

## Optimizations
Still needs more fruit names to add to the API. Possible add another API when the fruit is not available in our database. As we increase our database fruits, I will switch to a user input and account for spelling errors and autofills to make it user friendly.

## Lessons Learned:
Will come back and add more when the changes are made to make it user friendly.
