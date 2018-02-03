## Website Performance Optimization portfolio project


### Getting started

#### Part 1: Optimize PageSpeed Insights score for index.html

for optimizing the index to get the highest score, the following was made:
1. css and js were minified
2. js was made async 
3. images were optimized
4. size of images was changed

#### Part 2: Optimize Frames per Second in pizza.html

1. changed selectorAll to getElementByClassName
2. changed Queryselector to getElementByID
3. Moved recuring functions and variables from the for loop to reduce the time
4. changed some of the calculations to make it faster

### How you open it

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
  



