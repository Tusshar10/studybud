--> Create a virtual environment :

# Let's install virtualenv first
pip install virtualenv

# Then we create our virtual environment
virtualenv envname <br/>
--> Activate the virtual environment :
envname\scripts\activate
<br/>
--> Install the requirements :
pip install -r requirements.txt
<br/>
Running the App
<br/>--> To run the App, we use :
python manage.py runserver
<br/>
⚠ Then, the development server will be started at http://127.0.0.1:8000/
