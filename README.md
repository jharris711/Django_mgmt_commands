# Django_mgmt_commands

-> Create a 'management' dir in your core app, next to admin.py, apps.py, models.py,...:
  ```
  -Django-App
  ---app
  -----settings.py
  -----urls.py
  -----wsgi.py
  ---core
  -----management
  ...
  ```

-> Download this repo and move the 'commands' directory into the 'management' directory.

-> To quickly rename your app:
 ```
 $ ./manage.py rename OLD_APP_NAME NEW_APP_NAME
 ```
 
 -> To quickly create superuser named 'Admin':
 ```
 $ ./manage.py makesuper
 ```
