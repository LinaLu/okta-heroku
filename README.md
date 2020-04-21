# Calling a resource
http://127.0.0.1:5000/getmsg/?name={ryan}

(venv) Linas-MBP-2:okta-heroku fy6963$curl 'http://127.0.0.1:5000/' 
(venv) Linas-MBP-2:okta-heroku fy6963$ curl -v --data "name=shawn" http://127.0.0.1:5000/post/