PythonAnywhere Setup Instructions
=================================

- create a virtualenv (we tested it with python 3.13) and `pip install -r requirements.txt` into it
- create a new custom webapp on PythonAnywhere
- configure your webapp to use your virtualenv on the PythonAnywhere webapp dashboard
- setup your wsgi.py file as in the example in the repo, and make sure it can find and import the `dashing_demo_app`
- reload your webapp and go to your webapp url!

This is what it should look like:
<kbd><img src="https://raw.githubusercontent.com/conradho/dashingdemo/master/dashing_demo_webpage.png" alt="Picture of Dashing Demo Webapp"/></kbd>
