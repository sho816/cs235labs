# CS235 LAB05
## Notes:
- familiarise creating virtual environment for Python
- familiarise with Jinja HTML templating
- building list and item views using Flask Blueprint
- building search form uusing WTForms

## Reflection: 
I found this lab quite challenging with initialising my code and accessing it.
I am still in the process of utilising and committing my codes onto github as I do require more practice for further assignments down the line.

## Questions:
 
#### 1. All templates in the app extend from `layout.html`. What is the syntax for extending from a layout template
  the syntax for extending from layout would be: `{% extends "layout.html" %}`

  
#### 2. What method should you call to generate a dynamic URL for `localhost/people/40`
to generate a dynamic url for `localhost/people/40`, we would use the function url_for(); 
- url_for(localhost)
- url_for(people)
- url_for(40)

#### 3. what is the benefit of using blueprint compare with using the default route (app.route())?
 you are able to use blueprint and apply it to your application in several places, does not require an application object ahead of time
 blueprints are sets of operations that can be registerd onto an application.
