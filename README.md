# django Products
django app adding products

##Installation

1.  Make sure you have Python 3.6.0 installed. See instructions for download here:
    https://www.python.org/downloads/

2.  Virtualenv is probably what you want to use during development, and if you have shell access to your production
    machines, you’ll probably want to use it there, too.

3.  Requirements.txt contains all the external dependencies for the api.

4.  Go into the project's root folder and follow the "How to Run" instructions below.

##Requirements
    * Django==1.10.5
    * djangorestframework==3.5.3

##How to Run

###MAC
Create a virtual environment
```
python -m venv venv
```
Activate the virtual environment
```
source venv/bin/activate
```
Install all dependencies in requirements.txt
```
pip install -r requirements.txt
```
To deactivate the virtual environment
```
deactivate
```

###WINDOWS
Install virtual env and wrapper
```
pip install virtualenvwrapper-win
```
Create a virtual environment
```
mkvirtualenv myproject
```
Activate the virtual environment
```
workon myproject
```
Install all dependencies in requirements.txt
```
pip install -r requirements.txt
```
To deactivate the virtual environment
```
deactivate
```

###After creating a virtualenv

```
Run the migrations script to create the database
```
./manage.py migrate
```
Now, run the server
```
./manage.py runserver
```

## Credits
Nick Chemsak Feb 2017

