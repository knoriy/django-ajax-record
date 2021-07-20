# Django Ajax recording

This is the follow-up repository for the [live recording tutorial](https://dev.to/sirneij/django-and-ajax-building-a-recording-application-4j0a) on dev.to
## Run locally
 To run locally
 - Clone this repo:
  ```
  git clone https://github.com/Sirneij/django-ajax-record.git
  ```
 - Change directory into the folder:
  ```
  cd django-ajax-record
  ```
 - Create a virtual environment:
  ```
  virtualenv -p python3.8 env
  ```
 - Activate the environment:
   - For Linux and Mac machines
     ```
     source env/bin/activate
     ```
   - For Windows machine:
     ```
     .\env\Scripts\activate
     ```
 - Install the dependencies:
   ```
   pip install -r requirements.txt
   ```
 - Make migrations and migrate the database:
  ```
   python manage.py makemigrations
   python manage.py migrate
  ```
 - Finally, run the application:
  ```
   python manage.py runserver
  ```
 Visit http://localhost:8000 in your browser
