# `whisper.cpp` on Docker

Modified from https://gist.github.com/reitzig/6582edd485a5d0a8b68600dab3b0861b

```{bash}
VERSION="v1.2.1" #
docker build -t yosuketanigawa/whisper-cpp:${VERSION} --build-arg version=${VERSION} .
docker push yosuketanigawa/whisper-cpp:${VERSION}
```

Images are on [DockerHub](https://hub.docker.com/r/yosuketanigawa/whisper-cpp)
