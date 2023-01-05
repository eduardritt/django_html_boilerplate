# Django html5 Boilerplate
Django HTML Boilerplate incl. Bootstrap v5.3, JQuery v3.6.1 and Normalizer v8.0.1

## Install

1. Put template and static folder in to a root of your project
2. Open settings.py and do following changes:

```
import os

TEMPLATES = [
    {
        ...
        
        'DIRS': [
            os.path.join(BASE_DIR, 'templates'),
          ],
          
        ....
     }
 ]

## Static Configuration
STATIC_URL = '/static/'

# STATIC_ROOT is the single root directory from where the Django application will serve the static files in production.
STATIC_ROOT = os.path.join(BASE_DIR, 'staticfiles')

# This tells Django the location of static files in our project.
STATICFILES_DIRS = [
    os.path.join(BASE_DIR, 'static'), 
]
```

## License

MIT © Eduard Ritt
