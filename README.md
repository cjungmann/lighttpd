# LightTPD Knowledge Stash

This simple project starts with the ambition of being a
beginner's collection of discoveries about the [LightTPD](www.lighttpd.net)
web server.

## Installing Scripts

Install with the following command:

~~~sh
sudo ./install
~~~

Uninstall with the following command

~~~sh
sudo ./uninstall
~~~

## Scripts

As a novitiate of the LightTPD platform with experience using Apache, I
will attempt to create LightTDP utilities that mimic corresponding Apache
utilities.  The list is very small to start.  Perhaps it will grow as I
gain experience with LightTPD.

If either **lensite** and **ldissite** is called without a site name,
the program will run interactively if running as root, or will show the
status of sites-available sites if not root.

Apache Utility | LightTPD Equivalent | Function
-------------- | ------------------- | ---
a2ensite       | lensite             | Enable site
a2dissite      | ldissite            | Disable site




