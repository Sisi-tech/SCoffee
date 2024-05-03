## Project Name: SCoffee
## Django

## Learned and Practiced 

 **Templates** :

 **Set up**

- [x] **Add "templates" to 'DIRS' on the settings.py file**

## Example:
TEMPLATES = [
    {
        'BACKEND': 'django.template.backends.django.DjangoTemplates',
        'DIRS': ['templates'],
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

- [x] **Add templates**