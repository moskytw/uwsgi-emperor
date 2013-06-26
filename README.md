# Initialize uWSGI Emperor

It is the a LSB init script for uWSGI Emperor mode.

## Installation

    sudo cp uwsgi-emperor /etc/init.d/

## Usage

Put your uWSGI configs into `/etc/uwsgi-emperor`, then run:

    sudo service uwsgi-emperor start

It also supports `stop`, `restart`, `force-reload`, `reload`, and `status`.

## Log

The log of the uWSGI emperor will be placed at `/var/log/uwsgi-emperor.log`.
