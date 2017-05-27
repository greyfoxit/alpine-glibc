# Alpine GNU C / Docker

[![Docker status][docker-shield]][docker-link] [![Layers][layers-shield]][layers-link] [![Version][version-shield]][version-link]

A minimal [Alpine Linux](https://hub.docker.com/r/_/alpine/) based [Docker](https://www.docker.com/) image with [GNU C library](https://www.gnu.org/software/libc/) (glibc)

## Content &nbsp;/

- Alpine Linux ( **v 3.5** )
- GNU C ( **v 2.25** )

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
$ git clone https://github.com/greyfoxit/alpine-glibc.git
$ cd docker-alpine-glibc
$ docker build -t greyfoxit/alpine-glibc .
```

### as running container

```sh
$ docker run --rm -it greyfoxit/alpine-glibc
```

## Credits

`glibc` compatibility layer [package](https://github.com/sgerrand/alpine-pkg-glibc) prepared for Alpine Linux by [@sgerrand](https://github.com/sgerrand)

## Support

Please [file an issue](https://github.com/greyfoxit/alpine-glibc/issues) on Github

## License

Released under the [MIT License](#LICENSE) by Greyfox, Inc.

[docker-shield]: https://img.shields.io/docker/build/greyfoxit/alpine-glibc.svg
[docker-link]: https://hub.docker.com/r/greyfoxit/alpine-glibc/

[layers-shield]: https://images.microbadger.com/badges/image/greyfoxit/alpine-glibc:alpine3.5_glibc2.25.svg
[layers-link]: https://microbadger.com/images/greyfoxit/alpine-glibc

[version-shield]: https://images.microbadger.com/badges/version/greyfoxit/alpine-glibc:alpine3.5_glibc2.25.svg
[version-link]: https://microbadger.com/images/greyfoxit/alpine-glibc
