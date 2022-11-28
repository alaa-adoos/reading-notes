# Django Models
## Django web applications access and manage data through Python objects referred to as models.
### Models define the structure of stored data, including the field types and possibly also their maximum size, default values, selection list options, help text for documentation, label text for forms
## Model definition:
### Models are usually defined in an application's models.py file. They are implemented as subclasses of django.db.models.Model, and can include fields, methods and metadata.
## Fields
### A model can have an arbitrary number of fields, of any type — each one represents a column of data that we want to store in one of our database tables. Each database record (row) will consist of one of each field value
## COMMON FIELD ARGUMENTS:
- help_text: Provides a text label for HTML forms (e.g. in the admin site), as described above
- verbose_name: A human-readable name for the field used in field labels
- default: The default value for the field. This can be a value or a callable object, in which case the object will be called every time a new record is created
- null: If True, Django will store blank values as NULL in the database for fields where this is appropriate (a CharField will instead store an empty string). The default is False.
# Django Admin
## Registering models
```
from django.contrib import admin
```
## Creating a superuser
```
python3 manage.py createsuperuser
```
## run the server
 ```
 python3 manage.py runserver
```
