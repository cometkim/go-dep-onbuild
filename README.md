# Go + Dep build time image

- Based on official Go image
- Pre-installed [dep](https://golang.github.io/dep/), the official-experimental dependency manager for Go
- Cacheable layer for the vendor directory

## Usage

Build a container easily with this command lines

```bash
echo "FROM cometkim/go-dep-onbuild" > Dockerfile
docker build -t [IMAGE_NAME] .
```
