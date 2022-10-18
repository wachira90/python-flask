# python-flask
python-flask

## example

````
virtualenv env

env\Scripts\activate

pip install Flask
````

## python app.py

file : app.py

````
#! python
from flask import Flask
app = Flask(__name__)

@app.route('/')
def hello_world():
	return 'Hello World'

if __name__ == '__main__':
	app.run()
````  

## URL

````
http://localhost:5000/
````

## start with pm2

````
pm2 start app.py --name app1 --interpreter python

pm2 start app.py -i 4 --name app1 --interpreter python
````
