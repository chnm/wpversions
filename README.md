wpversions is a script that finds all of the WordPress installs on the server and puts them, as well as the version of WP and if it is an SVN install, into a file. You can use this file with wpupdate to quickly update all of the WordPress installs on your server.


Note: Relies on the 'locate' command, as such all installs are those existing on the system the previous day (or the last time the updatedb command was run).
