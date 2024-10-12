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


# Screenshots

![Screenshot showing the Django admin login screen (light mode) with an extra checkbox that reads "I am not affiliated with WP Engine in any way, financially or otherwise"](https://blog.bmispelon.rocks/files/django_wplogin_screenshot_light.png)
![Screenshot showing the Django admin login screen (dark mode) with an extra checkbox that reads "I am not affiliated with WP Engine in any way, financially or otherwise"](https://blog.bmispelon.rocks/files/django_wplogin_screenshot_dark.png)
