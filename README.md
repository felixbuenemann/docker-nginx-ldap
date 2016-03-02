# NGINX with HTTP/2 and LDAP Auth

Build based on official nginx alpine linux Dockerfile with the following config:

Enabled non-default modules:

* http\_ssl\_module
* http\_realip\_module
* http\_gunzip\_module
* http\_gzip\_static\_module
* http\_stub\_status\_module
* http\_v2\_module
* ipv6

See the [official nginx image](https://hub.docker.com/_/nginx/) for configuration options and [example.conf](https://github.com/kvspb/nginx-auth-ldap/blob/master/example.conf) for available ldap auth options.
