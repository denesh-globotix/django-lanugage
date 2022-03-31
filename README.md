# django-lanugage
Trying out translating pages in django

# Change the language in settings.py
`LANGUAGE_CODE = 'es'`

# Add the trans tag at the top of the html file: 
{% load i18n %}

# Create the translation file with .po extension 
django-admin makemessages -l es

# Create the actual translation 
django-admin compilemessages

