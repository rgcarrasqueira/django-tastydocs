django-tastydocs
================

Automatic Web Documentation for django-tastypie

How to use
==========

- Add `tastydocs` to the `INSTALLED_APPS` tuple on `settings.py.
- Add a reference to the `tastydocs` URLs in `urls.py`
    (r'^docs/', include("tastydocs.urls"), {"api": api}) # api must be a reference to the TastyPie API object.