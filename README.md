# Alpine GNU C / Docker 

[![Docker Status][docker-shield]][docker-link] [![Docker Pulls][pulls-shield]][pulls-link] [![Layers][layers-shield]][layers-link] [![Version][version-shield]][version-link]

A minimal [Alpine Linux](https://hub.docker.com/r/_/alpine/) based [Docker](https://www.docker.com/) image with [GNU C library](https://www.gnu.org/software/libc/) (glibc)

## Content &nbsp;/

- Alpine Linux ( **v 3.6** )
- GNU C ( **v 2.26** )

## Use this &nbsp;>

### as base image

exactly as you would with any other docker image inside `Dockerfile`

```Dockerfile
FROM greyfoxit/alpine-glibc
```

### as pull from Docker Hub

```sh
$ docker pull greyfoxit/alpine-glibc
```

### as local build

```sh
$ git clone https://github.com/greyfoxit/alpine-glibc.git && cd alpine-glibc 
$ docker build --no-cache -t greyfoxit/alpine-glibc .
```

### as running container

```sh
$ docker run --rm -it greyfoxit/alpine-glibc
```

## Credits

[@andyshinn](https://github.com/andyshinn) for `glibc` compatibility layer [package](https://github.com/sgerrand/alpine-pkg-glibc) prepared for Alpine Linux

## Support

Please [file an issue](https://github.com/greyfoxit/alpine-glibc/issues) on Github

## License

Released under the [MIT License](#LICENSE) by Greyfox, Inc.

[docker-shield]: https://img.shields.io/docker/build/greyfoxit/alpine-glibc.svg
[docker-link]: https://hub.docker.com/r/greyfoxit/alpine-glibc/

[pulls-shield]: https://img.shields.io/docker/pulls/greyfoxit/alpine-glibc.svg
[pulls-link]: https://hub.docker.com/r/greyfoxit/alpine-glibc/

[layers-shield]: https://images.microbadger.com/badges/image/greyfoxit/alpine-glibc.svg
[layers-link]: https://microbadger.com/images/greyfoxit/alpine-glibc

[version-shield]: https://images.microbadger.com/badges/version/greyfoxit/alpine-glibc.svg
[version-link]: https://microbadger.com/images/greyfoxit/alpine-glibc
