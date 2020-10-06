# minimial-flask

[Flask](https://flask.palletsprojects.com/en/1.1.x/foreword/) is a *microframework*.
The “micro” in microframework means Flask aims to keep the core simple but extensible. Flask won’t make many decisions for you.
There are many ways to setup a flask project, this is one example adapted from the excellent [The Flask Mega-Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world).

It sets up a flask project with a useful directory structure. It also includes bootstrap as a CDN miniming the custom CSS needed.

First use 

```bash
git clone  
cd 
```
to get the project and move into it. Then setup a virtual enviroment for the project, activate it and install the neccesary libraries.
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirement.txt
```
Finally Flask needs to be told how to import the app, by setting the `FLASK_APP` environment variable:
```bash
export FLASK_APP=microblog.py
```
If you are using Microsoft Windows, use set instead of export in the command above.

Now run the app with 
```
flask run
```
Now open the app in a browser, enter `http://localhost:5000/` to see the basic app.
