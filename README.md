#### To run this locally:

Some useful tips to help you get started:

1. Check out the repository

  ```bash
  $> cd /path/to/your-project-folder
  $> python -m SimpleHTTPServer 8080
  ```
  For Python3

  ```bash
  $> cd /path/to/your-project-folder
  $> python3 -m http.server 8080
  ```

2. Open a browser and visit localhost:8080

#### To make your local server accessible remotely.

  ``` bash
  $> cd /path/to/your-project-folder
  $> ./ngrok http 8080
  ```

## Optimizations to index.html
1. Compressed Pizzeria.jpg to a smaller file size.
2. Added media query to print.css link.
3. Minify style.css and inline to index.html
4. Add rel=preload to web font, so it is no longer render-blocking.
5. Move js to the bottom of the html page.
6. Minified perfmatter.js

##Optimizations to main.js
1. Change number of pizza created from 200 to 25.
2. Move scrollTop outside of for loop in updatePositions.

1. Update sizeSwitcher to use percentages.
2. Move windowWidth from determineDx to changePizzaSizes so it's only calculated once.
3. remove newSize() and just add switch to determineDx.
4. Move pizzasDiv outside of for loop.

##Optimizations for pizza.html
1. Minified all CSS.
2. Declare viewport and utf encoding.
