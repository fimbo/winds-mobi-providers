winds.mobi - real-time weather observations
===========================================

[![Follow us on https://www.facebook.com/WindsMobi/](https://img.shields.io/badge/facebook-follow_us-blue)](https://www.facebook.com/WindsMobi/)

[winds.mobi](http://winds.mobi): Paraglider pilot, kitesurfer, check real-time weather conditions of your favorite spots
on your smartphone, your tablet or your computer.

winds-mobi-providers
--------------------

Python 3.6 cronjobs that get the weather data from different providers and save it in a common format into mongodb. 
This project use Google Cloud APIs to compute any missing station details (altitude, name, timezone, ...).
Google Cloud API results are cached with redis.

### Requirements

- python >= 3.6 
- mongodb >= 3.0
- redis
- Google Cloud API key

See [settings.py](https://github.com/winds-mobi/winds-mobi-providers/blob/master/settings.py)

### Python environment

- `pipenv install`
- `pipenv shell`

### Run a provider

- `python jdc.py`

Licensing
---------

Please see the file called [LICENSE.txt](https://github.com/winds-mobi/winds-mobi-providers/blob/master/LICENSE.txt)
