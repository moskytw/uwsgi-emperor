# Initialize uWSGI Emperor

It is a LSB init script for [the uWSGI
Emperor](http://uwsgi-docs.readthedocs.org/en/latest/Emperor.html) mode.

## Installation

    sudo cp uwsgi-emperor /etc/init.d/

## Usage

Put your uWSGI configs into `/etc/uwsgi-emperor`, and then run:

    sudo service uwsgi-emperor start

It also supports `stop`, `restart`, `force-reload`, `reload`, and `status`.

## Log

The log of the uWSGI emperor will be placed at `/var/log/uwsgi-emperor.log`.
