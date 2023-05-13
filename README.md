The weather in any city in the world can be simply known with the use of this straightforward weather application. With the aid of JQuery, this design is simple to create. 
The basic structure of this Weather App has been created using the following HTML and CSS code. This structure will contain all the information.
The weather information for all towns and nations was fetched using the APIs in our weather app.
For the javascript part:We will first create a constant object variable, which will store our object base and key value.
Now using thedocument.queryselector We will select our input search box and we will add a Keypress EventListener to it, which we will attach to a function called setQuery.
Now, using the function, we will check if our key value is 13 digits long or not. If it is, then it will search for the city or country you are searching for using the search box.
Now we will create another function  which we fetch the weather details using the API, and then it will return the weather details using the.json() method.
Now we will create a function that will push all the output into our HTML element so that we can display the weather details on our webpage.
We will also create the function by which we will fetch the current date and year from the user’s browser.
Now inside that, we will create an array for the months in a year.
a week’s worth of days in an array
Now using the.getDay and date() methods, we will fetch the current date and store it into the variables, and using those variables, we will display it as our output.
