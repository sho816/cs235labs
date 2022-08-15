# CS235 LAB04
## Notes:
- drawing on basic HTML page again, we're shown HTML with external CSS
- install and understand flask app, how to import into your editor
- enable the environment variable, create new folder structure as well 
- static > css > styles.css
- templates > index.html
- main.py
- .gitignore
- texts in `{{}}` are rendered as variables
- 

## Reflection: 
 I am still in the process of wrapping my head around using the different terminals and installing the different software to use, however once i keep practicing with the hands
 parts i will familiarise myself with it and can make projects in the forseeable future. These labs are quite challenging and the videos do help.
 
## Questions:
 
#### 1. Whatʼs the terminal command for starting a Flask server?
  the command is flask run
  
#### 2. Why do we want to enable debug mode during development?
  during development enabling debug mode will allow it to automatically reload if in the case code changes and will show the debugger in the browser if an error occurs.

#### 3. If you put a python file under `./static/` directory, can you access it from the browser?
  No it is not accesible because your templates of html would be after the static in the structure, therefore a debug error will occur.
  we don't want users to be able to view the source code and putting it in static will allow that.

#### 4. What is URL encoding and why does it exist?
  URL encoding converts characters into a format that is transmittable over the internet, which is ASCII characters. IT exists because it is easier to define encoding for all characters in ASCII and URLs can only have certain characters from the ASCII set. Characters outside of ASCII need to be encoded anyways.
