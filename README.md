# Django html5 Boilerplate
Django HTML Boilerplate incl. Bootstrap v5.3, JQuery v3.6.1 and Normalizer v8.0.1

## Install

1. Put template and static folder in to a root of your project
2. Open settings.py and do following changes:

```
TEMPLATES = [
    {
        'BACKEND': 'django.template.backends.django.DjangoTemplates',
        'DIRS': [
          BASE_DIR / 'templates'
          ],
        'APP_DIRS': True,
        'OPTIONS': {
            'context_processors': [
                'django.template.context_processors.debug',
                'django.template.context_processors.request',
                'django.contrib.auth.context_processors.auth',
                'django.contrib.messages.context_processors.messages',
            ],
        },
    },
]

STATIC_ROOT = os.path.join(BASE_DIR, 'static')
STATIC_URL = 'static/' 
```

## License

MIT © Eduard Ritt
