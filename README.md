go-cjdns
========

This is a group of packages for working with cjdns using Go. 

go-cjdns/config
---------------

Package config allows easy loading, manipulation, and saving of cjdns configuration files. It can load, parse, and save the standard cjdns file as well as a file with custom data added. This enables you to store additional information with your peer connections and server details. 

go-cjdns/admin
--------------

Package admin provides methods to access a running cjdns instance via the admin tcp socket. It not only allows you to send any command and receive the response but it also provides convenience functions. It relies on go-cjdns/config for loading of the configuration data and getting the IP address, port, and password for the admin interface.

