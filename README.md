# python-flask
python-flask

## example

````
virtualenv env

env\Scripts\activate

pip install Flask

nano app.py

python app.py

http://localhost:5000/
````

## start with pm2

````
pm2 start app.py --name app1 --interpreter python

pm2 start app.py -i 4 --name app1 --interpreter python
````
