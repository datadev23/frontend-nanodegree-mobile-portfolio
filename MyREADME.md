The purpose of this project was to generate an optimization for the portfolio page and optimize the change in a pizza size.



Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this on line portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

To get started, check out the repository and inspect the code.

### Getting started

####Part 1: Optimize PageSpeed Insights score for index.html


1. Check out the repository

git clone "https://github.com/alexdev23/frontend-nanodegree-mobile-portfolio.git"
navigate into the 'frontend-nanodegree-mobile-portfolio' directory
cd c:/frontend-nanodegree-mobile-portfolio

2. Download and install [ngrok](-) to the top-level of your project directory to make your local server accessible remotely.


  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8089
  ```

  ``` bash
  $> cd /path/to/your-project-folder
  $> ./ngrok http 8080

Your web address will be similar to this. 
https://92832de0.ngrok.io -> localhost:80

The 92832de0 will be a randomly generated number letter combination. 

Now you need togo too the https://developers.google.com/speed/pagespeed/

Type in your generated eg url https://92832de0.ngrok.io -> localhost:80

Run the test.

You will be asked to apply various fixes. 

Part One Fixes

* add inline css to the index.html file
* Add media query to print.css
* reduce the size of profile images
* change size of pizza image
* Make google analytics async
* Minify Html
* optimise image for pizza.jpeg and 
* optomise image for pizzeria.jpeg




####Part 2: Optimize Frames per Second in pizza.html



Part A

If you want to see how efficient the processes is for the pizza loading on the page. You can look at the the inspect tab. You can get the inspect tab by clicking your menu button on the mouse and choosing the menu item inspect. The inspection menu will open on the page and then you need to go to the time line tab. From here you need to choose time line There is a red dot to the side of the timeline menu click this. This will start record a session now press F5 to reload the page. Once the page has been reloaded stop the record and a chart will be visible. 

Part B
To use the application you need to load the index file located in views/js/index.html.

Once the application has been loaded to test the pizza is working correctly you need to go to the location menu item.
This will take you down to a slider where you can alter the size of the pizza.
From here you can alter the size of the pizza.


* Move all constants out of the for loop in the updatefunction.
* Move math.Sin out of for loop due to it being recalcuated 
* Set number of pizzas in document.addEventListener to  36.
* Changes the value for the size of the pizza above the slider
* document.getElementById optomisation made
* function changeSliderLabel(size)
* document.getElementsByClassName('randomPizzaContainer') outside the loop (e.g. var container = document.
* getElementsByClassName('randomPizzaContainer')), so the DOM is not explicitly touched in every iteration!
* optimisation array length operator will not be accessed after each loop iteration.
* transform: translateZ(0) activates the gpu
* pizzasDiv variable outside the loop, so only DOM call is made
* web api getElementsByClassName is faster for accessing mover class
* Declaring the phase variable (var phase;) in the initialisation of the for loop will prevent it from being created every time the loop is executed.
* Declaring the elem variable (var elem;) in the initialisation of the for-loop will prevent it from being created every time the loop is executed
* The document.getElementById() Web API call is faster for movingPizzas1






