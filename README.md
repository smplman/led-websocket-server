#  led-websocket-server

## setup
```
python3 -m venv env
. ./env/bin/activate
sudo ./env/bin/pip3 install -r requirements.txt
sudo ./env/bin/python led.py
```
* you need sudo in order to use the PWM pin on the raspberry pi

## Links
python websockets https://websockets.readthedocs.io/en/9.0.1/intro.html
python as a service https://alexandra-zaharia.github.io/posts/stopping-python-systemd-service-cleanly/
asyncio event loops https://tutorialedge.net/python/concurrency/asyncio-event-loops-tutorial/