# django_wplogin
Enhance your Django admin login page.

Based on an idea by [@alexgmin](https://github.com/alexgmin)


# Installation

1) Install the package:
```
pip install django_wplogin
```

2) Add the application to your `INSTALLED_APPS`. Make sure it's **before** `django.contrib.admin`:
```
INSTALLED_APPS = [
    ...
    "django_wplogin",
    "django.contrib.admin",
    ...
]
```

3) That's it. Your login page is now enhanced.
