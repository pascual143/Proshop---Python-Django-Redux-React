PROSHOP

# Aplication in React-Django

#   FRONT END
    - React
    - Django
    - React-router-dom
    - React-router-bootstrap
    - React-bootstrap

#   BACKEND
    - $ pip install virtualenv
    - $ virtual env  (we call environment how we want)
    - $ source env/bin/activate (to go inside env)(it will appear (env))
    - $ pip install django
    - $ django-admin stratproject backend
    - $ cd backend 
    - $ python manage.py runserver
    - $ python manage.py startapp base
    -in backend setting.py =>configure INSTALLED APPS and we write 'base.apps.BaseConfig'


#   FETCHING DATA (AXION AND CORS(cross-origin resource sharing))
    -connect urls and views
    -INSTALL AXIOS
    -IMPORT useEffect AND useState
    - $ pip install django-cors-headers
    -add in settings.py whatever django-cors-headers documentation tells you

    - add proxy into the front end package.json and we can remove http://127.0.0.1:8000 url form HomeScreen

#   SETUP ADMIN PANEL AND DATABASE
    -migrate all the data => $ python manage.py migrate
    - $ python manage.py createsuperuser  => to apply the migrations

#   MODELING DATA
    -Create model in models.py
    - $ python manage.py makemigrations
    - $ python manage.py migrate
    -see in the dajngo/admin

#  Image
    -Adding the Product models.ImageField
    -install Pillow 
        $ pip install pillow
    -configure static files in settings.py (to the end)

#  Serializing data
    - create serializers.py

#  INSTALLING REDUX
    - INSTALL: redux, react-redux, redux-thunk, redux-devtools-extension(for google extension)
    - create store.js and import provider and store.js to indexjs. Now u can see the redux-devtools-extension working
    - 








