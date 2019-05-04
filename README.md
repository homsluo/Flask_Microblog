# Flask_Microblog
I've used Flask to develop the microblog website at the localhost  
You may experience these function on the microblog website:  
1.Register: Register as a new user.  

2.Reset Password: You may use the email send to you to reset your password.  

3.Profile: You can introduce yourself and see your last login time; You can see how many people following you and you followed.   

4.Home & Explore: You can see all your posts and make a new post at your Home; You can see all users' posts at Explore.  

5.Follow & Unfollow: You can follow or unfollow any other user.  
## Virtual Environment
You may `not` use the `venv` I upload, instead create your own `virtual environment`        
```$ python3 -m venv venv```              

To create your own virtual environment and activate it       
```
$ virtualenv venv
$ source venv/bin/activate
```        

Then you may need these packages to run the flask app.
## Packages:
```
(venv) $ pip install flask
(venv) $ pip install python-dotenv
(venv) $ pip install flask-wtf
(venv) $ pip install flask-sqlalchemy
(venv) $ pip install flask-migrate
(venv) $ pip install flask-login
(venv) $ pip install jinja2
(venv) $ pip install werkzeug
(venv) $ pip install flask-mail
(venv) $ pip install pyjwt
(venv) $ pip install flask-bootstrap
(venv) $ pip install flask-moment
(venv) $ pip install dateutil
```
## Run Flask App
You may run the app at the top directory
```
(venv) $ flask run
```
