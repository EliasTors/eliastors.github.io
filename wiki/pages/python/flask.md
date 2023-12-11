# Flask

Flask i a web framework for python

## Setup
### Create and activate virtual enviroment
This creates a virtual enviroment called venv
`python -m venv venv`

This activates the env
`.\venv\Scripts\activate`

### Install flask in the venv

`pip install flask`

### Enviroment variables
Exchange *app* for the name of the python file
`set FLASK_APP=app`

`set FLASK_ENV=development`


## Code
This is a basic example to use the html file called *calculate* and set the template folder to root

'''python
from flask import Flask, render_template

app = Flask(__name__, template_folder='.')

@app.route('/')
def home():
    return render_template('calculate.html')

'''


## Run website
This runs the site on port 8000 and makes it avaliable to other computers on the network

`flask run --host=0.0.0.0  -p 8000`


