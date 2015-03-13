# Opentracker WebUI

It’s a minimalist responsive web interface for [Opentracker](https://erdgeist.org/arts/software/opentracker/) BitTorrent tracker that you can put on your [Tomato](http://tomato.groov.pl/) router (provided it’s got PHP installed) and use from anywhere with any device.

## NGINX configuration

Because of restrictive cross-origin request JavaScript policy you need to configure your web server properly in order for real-time statistics display to work.

Example NGINX configuration can be found [here](https://github.com/garnetius/opentracker-webui/blob/master/nginx.conf).

## Screenshot

![Screenshot](https://raw.github.com/garnetius/opentracker-webui/master/screenshot.png "Screenshot")
