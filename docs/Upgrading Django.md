```py
  python -m django --version
```

(How to upgrade)[https://docs.djangoproject.com/en/4.2/howto/upgrade-version/]

(Django Release Process)[https://docs.djangoproject.com/en/4.2/internals/release-process/]
Versions are numbered in the form A.B or A.B.C.
A.B is the feature release version number.
C is the patch release version number,

(Release Notes)[https://docs.djangoproject.com/en/4.2/releases/]

(Deprecation Timeline)[https://docs.djangoproject.com/en/4.2/internals/deprecation/]
Before upgrading, it’s a good idea to resolve any deprecation warnings
In Python, deprecation warnings are silenced by default. You must turn them on using the -Wa 
```py
  python -Wa manage.py test
```

Django Upgrade
```py
  python -m pip install -U Django
```