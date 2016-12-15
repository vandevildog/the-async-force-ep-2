# The-Async-Force-Ep-1
An **async** Exercise using **client side** XHR accessing the swapi API at https://swapi.co



## Excercise
*Remember to commit after each step.*

1. Make a `/js` folder and create an `app.js` file in it.
1. In the `index.html` file, load `app.js` via script tags.
1. Use live-reload to serve up the files to your browser.
1. Construct your XHR requests in the `app.js` file by scraping the value from the input field.
1. A request to the SWAPI api should be initiated when the button is clicked.
  Information from the data that comes back from the API should be displayed in
  the body of the html.  Additional html elements should be created to properly
  display and format the data in a presentable way.
1. Think of an elegant way of handling errors.  For example, if the SWAPI API returns an error due to incorrect an incorrect URL fragment.

Note: Go to https://swapi.co to find out what kind of data can be requested!



## Hints
1. Slides on Async HTTP Request with XHR: http://slides.com/sgnl/xhr#/
1. Documentation on 'XMLHttpRequest' method:
https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/Using_XMLHttpRequest
1. Remember that this is a **client side** excercise which means that all the code will be executed via the browser's javascript runtime, which means that our global context is the 'window' object.  Go ahead and type in 'window' in the browser console to inspect the methods on the 'window' object.  In there you will find a method named 'XMLHttpRequest' which you will be using for this excercise.