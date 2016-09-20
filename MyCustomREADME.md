####Part 1: Optimize PageSpeed Insights score for index.html

Some useful tips to help you get started:

1. Check out the repository
1. To inspect the site on your phone, you can run a local server

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```

1. Open a browser and visit localhost:8080
1. Download and install [ngrok](https://ngrok.com/) to the top-level of your project directory to make your local server accessible remotely.



  ``` bash
  $> cd /path/to/your-project-folder
  $> ./ngrok http 8080
  ```

1. Copy the public URL ngrok gives you and try running it through PageSpeed Insights! Optional: [More on integrating ngrok, Grunt and PageSpeed.](http://www.jamescryer.com/2014/06/12/grunt-pagespeed-and-ngrok-locally-testing/)


Optomise the FPS 60



Image Minification
CSS & javascript inline & minification
HTML Minification

####Part 2: Optimize Frames per Second in pizza.html

To use the application you need to load the index file located in views/js/index.html.

Once the application has been loaded to test the pizza is working correctly you need to go to the location menu item.
This will take you down to a slider where you can alter the size of the pizza.
From here you can alter the size of the pizza.

Part A

If you want to see how efficient the processes is. You can look at the the inspect tab. You can get the inspect tab by clicking your menu but on the mouse and chosing the menu item inspect. From here you need to choose timeline There is a red dot click this. This will start record a session now press F5 to reload the page. a chart will be generated. You will be able to see the time frames that have been generated. 

Part B
If you want to see how efficient the processes is. You can look at the the inspect tab. You can get the inspect tab by clicking your menu but on the mouse and chosing the menu item inspect.  If you choose the console tab and then reload change the size of pizza you can see the speed of it changing. 

To optimize views/pizza.html, you will need to modify views/js/main.js until your frames per second rate is 60 fps or higher. You will find instructive comments in main.js. 

