<<<<<<< HEAD
# The-Async-Force-Ep-2
=======
# The-Async-Force-Ep-1
>>>>>>> bd33690988173700cb67b73c232a488e4cf28e87
An **async** Exercise using **client side** XHR accessing the swapi API at https://swapi.co



## Excercise
*Remember to commit after each step.*

1. Make a `/js` folder and create an `app.js` file in it.
1. In the `index.html` file, load `app.js` via script tags.
1. Use live-reload to serve up the files to your browser.
1. Construct your XHR requests in the `app.js` file by scraping the value from the input field.
1. A request to the SWAPI api should be initiated when the button is clicked.
  Information that comes back from the API should be displayed in
  the body of the html.  Additional html elements should be created to properly parse,
  display and format the data in a presentable way.

  1. If a `person` is requested, display the following information:
    - Name
    - Gender
    - Species
    - Homeworld
    - Films in
  2. If a `planet` is requested, display the following information:
    - Name
    - Terrain
    - Population
    - Residents
    - Film in
  3. If a `starship` is requested, display the following information:
    - Name
    - Manufacturer
    - Starship Class
    - Films in



1. Display any xhr errors in the dom, so the user can see. For example, if a user inputs `99999` as an id, or `potato`. Display the error on the page.

Bonus: The interface is not very user friendly. What you have so far can be considered a very rough MVP just to see things are working. People outside of the software engineering industry don't know what a URL fragment is and wouldn't know how to use the app.  Redesign the interface so that a non engineer can use it! An example would be to give them a list of categories to choose from instead of manually typing it in and another input field for the resource number.

Note: Go to https://swapi.co to find out what kind of data can be requested!



## Hints
1. URL Fragments are the parts of a URL that an API Endpoint parses to tell the server what resource to retrieve.
1. Slides on Async HTTP Request with XHR: http://slides.com/sgnl/xhr#/
1. Documentation on 'XMLHttpRequest' method:
https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/Using_XMLHttpRequest
1. Remember that this is a **client side** excercise which means that all the code will be executed via the browser's javascript runtime, which means that our global context is the 'window' object.  Go ahead and type in 'window' in the browser console to inspect the methods on the 'window' object.  In there you will find a method named 'XMLHttpRequest' which you will be using for this excercise.