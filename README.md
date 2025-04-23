# MQTT-Live-Monitor
Uses MQTT web sockets and shows both on the website and as a log in the console of your browser which topics are currently being subscribed to, as well as their messages.

# Customization

You have to change following line:

```
const client = mqtt.connect("ws://192.168.0.5:8083");
```

Depending on the broker configuration, you may not only have to add a username and password, but also certificates and other parameters.
