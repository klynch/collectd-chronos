chronos-collectd-plugin
=======================

A [collectd](http://collectd.org) plugin for [Chronos](https://github.com/mesos/chronos) running on
[Apache Mesos](http://mesos.apache.org) using collectd's
[Python plugin](http://collectd.org/documentation/manpages/collectd-python.5.shtml).

This plugin is inspired by the [Mesos Python plugin](https://github.com/rayrod2030/collectd-mesos).

It collects data from Chronos's `/metrics` API endpoint.

Install
-------
 1. Place `chronos.py` in /opt/collectd/lib/collectd/plugins/python (assuming you have collectd installed to /opt/collectd).
 2. Configure the plugin (see below).
 3. Restart collectd.

Configuration
-------------
 * See `chronos.conf`

Requirements
------------
 * collectd 4.9+
 * Chronos 2.1.0 or greater

License
-------
This software is released under the Apache License
