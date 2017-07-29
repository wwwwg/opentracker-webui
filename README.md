# Opentracker WebUI

It’s a minimalist responsive web interface for [Opentracker](https://erdgeist.org/arts/software/opentracker/) BitTorrent tracker to help manage its whitelist (or blocklist) via web browser.

## NGINX configuration

Because of restrictive cross-origin request JavaScript policy you need to configure your web server properly in order for real-time statistics display to work.

Example NGINX configuration can be found [here](https://github.com/garnetius/opentracker-webui/blob/master/nginx.conf).

## Screenshot

![Screenshot](https://raw.github.com/garnetius/opentracker-webui/master/screenshot.png "Screenshot")
