# debian-pharo-docker-image

Docker image for Pharo Smalltalk.

## Status

> **:warning: Unmaintained**
>
> This repository has not received updates since November 2017 and is **not actively maintained**.
> The image builds on `debian:stretch`, which has reached end of life. No security
updates, bug fixes, or new Pharo versions will be published here.
>
> For up-to-date Pharo images and current installation instructions, see the
> [Pharo project](https://pharo.org/) and the official
> [Pharo getting-started guide](https://pharo.org/download).

## Usage

```bash
docker build -t debian-pharo .
docker run -it --rm debian-pharo
```

The image sets up a Debian-based environment with Pharo's stable VM and image fetched from
`get.pharo.org` (see [`Dockerfile`](./Dockerfile)). A [Seaside](https://github.com/SeasideSt/Seaside)
example is included under [`seaside/`](./seaside).