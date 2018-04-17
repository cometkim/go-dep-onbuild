# Go + Dep build time image

[![GitHub license](https://img.shields.io/github/license/cometkim/go-dep-onbuild.svg)](https://github.com/cometkim/go-dep-onbuild/blob/master/LICENSE)
[![Docker Build Status](https://img.shields.io/docker/build/cometkim/go-dep-onbuild.svg)](https://hub.docker.com/r/cometkim/go-dep-onbuild/)
[![Docker Pulls](https://img.shields.io/docker/pulls/cometkim/go-dep-onbuild.svg)](https://hub.docker.com/r/cometkim/go-dep-onbuild/)

- Based on official Go image
- Pre-installed [dep](https://golang.github.io/dep/), the official-experimental dependency manager for Go
- Cacheable layer for the vendor directory

## Usage

Build a container easily with this command lines

```bash
echo "FROM cometkim/go-dep-onbuild" > Dockerfile
docker build -t [IMAGE_NAME] .
```
