# About [![HitCount](http://hits.dwyl.com/panaceya/nginx-quic.svg)](http://hits.dwyl.com/panaceya/nginx-quic) [![Docker Pulls](https://img.shields.io/docker/pulls/panaceya/nginx-quic?style=flat-square)](https://hub.docker.com/r/panaceya/nginx-quic) ![GitHub](https://img.shields.io/github/license/panaceya/nginx-quic)

Production-ready images [nginx] with [QUIC] support. Based on [nginx-build-quic] repo.

[![DockerHub](https://dockeri.co/image/panaceya/nginx-quic)](https://hub.docker.com/r/panaceya/nginx-quic)
 



# Requirements
* Docker

# Usage
[All tags](https://hub.docker.com/r/panaceya/nginx-quic/tags)


`docket pull panaceya/nginx-quic:tag` where `tag` is one of:

* ubuntu-18.04
* ubuntu-20.04
* centos-7
* centos-8

## Docker file
```
FROM panaceya/nginx-quic:<tag>
#
# some stages
#

# start Nginx
CMD ["nginx"]
```




# Links 
* [nginx]
* [QUIC]

[nginx]: https://nginx.org/
[QUIC]: https://quic.nginx.org/

