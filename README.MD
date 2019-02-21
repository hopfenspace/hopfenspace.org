# Hopfenspace Homepage

This repository stores the data that should be shown on our [web page](https://hopfenspace.org).

## Updating the web page

To update the web page, simply `push` to this repository. Anything in here will be shown on our servers (if it's on branch **master**).

The server pulls periodically from this repository, so it may take some time until your changes will take public effect.

It uses `crontab` to execute a little helper script `/usr/bin/web-update` every 30 minutes which takes care of publishing new content.
