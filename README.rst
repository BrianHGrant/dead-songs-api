=====
Grateful Dead Songs API
=====

Grateful Dead Songs API is a simple Django Rest Framework app to run an API for Grateful Dead Songs. Visitors can access song titles, and publishing information.

Detailed documentation is in the "docs" directory.

Quick start
-----------

1. Add "api" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = (
        ...
        'api',
    )

2. Include the polls URLconf in your project urls.py like this::

    url(r'^polls/', include('api.urls')),

3. Run `python manage.py migrate` to create the api models.

4. Visit http://127.0.0.1:8000/api/ to participate in the poll.
