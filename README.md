# Website Performance Optimization Portfolio Project
The challenge provided was to optimize the online portfio for speed!.We have to optimize the critical rendering path and make the page render as quickly as possible by applying various techniques.

# Getting Started 
***
## Installation
* First check out the repository and clone or download the project.
* Then we need to install the local server, which can be done by various methods.In my case i used the fenix software and made a local server and inspected the site.
* By using the public url, try running it in PageSpeed Insights!
* Then you can test ,optimize,measure and repeat.
  
# Optimizations Performed
***
### Optimize PageSpeed Insights score for index.html

* The loading of javascript was asynchronised by using the async tag.
* The pizzeria.jpg image was optimized to Optimized-pizzeria.jpg using the online image opimization tool.
* The google web font css was removed .
* The minification of css and html files was done.

### Optimize Frames per Second in pizza.html

* Changed querySelector() to getElementById() ;
* Changed querySelectorAll() to getElementsByClassName() ;
* Reduce the  no. of background pizzas to 50.
* The loops were optimized in changePizzaSizes(size) function.
* Declaring the variable items outside the function so as to reduce the scripting time taken
* Moved var pizzasDiv = document.getElementById("randomPizzas"); outside the loop so that there is only one DOM call.
* Declare var elem outside the loop to prevent it being created at each iteration. 

## License

It is released under [MIT License](https://choosealicense.com/licenses/mit/).


