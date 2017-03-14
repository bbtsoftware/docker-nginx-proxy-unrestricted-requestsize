![License MIT](https://img.shields.io/badge/license-MIT-blue.svg) [![Docker Automated build](https://img.shields.io/docker/automated/bbtsoftwareag/nginx-proxy-unrestricted-requestsize.svg)](https://hub.docker.com/r/bbtsoftwareag/nginx-proxy-unrestricted-requestsize) [![](https://img.shields.io/docker/stars/bbtsoftwareag/nginx-proxy-unrestricted-requestsize.svg)](https://hub.docker.com/r/bbtsoftwareag/nginx-proxy-unrestricted-requestsize) [![](https://img.shields.io/docker/pulls/bbtsoftwareag/nginx-proxy-unrestricted-requestsize.svg)](https://hub.docker.com/r/bbtsoftwareag/nginx-proxy-unrestricted-requestsize)

Derived docker containers from [jwilder/nginx-proxy] with additional unrestricted client body size.

```sh
client_max_body_size 0;
```

For information on how to use please see [jwilder/nginx-proxy].

[jwilder/nginx-proxy]: https://hub.docker.com/r/jwilder/nginx-proxy