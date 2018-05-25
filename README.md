[![Deploy](https://cdn.wedeploy.com/images/deploy.svg)](https://console.wedeploy.com/deploy?repo=https://github.com/wedeploy-examples/django-example)

# Django

A example of [Django](https://www.djangoproject.com/) on [WeDeploy](https://wedeploy.com/).

## Instructions

1. Install the [WeDeploy CLI](https://wedeploy.com/docs/intro/using-the-command-line/).
2. Clone this repository.
3. Go to `/django-example/mysite/mysite/settings.py` and add the URL of your service (`serviceID-projectID.wedeploy.io`) to `ALLOWED_HOSTS`.
4. Go to `/django-example`.
5. Run `we deploy -p projectID -s serviceID`.

## License

[BSD-3-Clause](./LICENSE.md), © Liferay, Inc.
