# `whisper.cpp` on Docker

Modified from https://gist.github.com/reitzig/6582edd485a5d0a8b68600dab3b0861b

```{bash}
MODEL="medium.en"
VERSION="v1.2.1" #
docker build -t yosuketanigawa/whisper-cpp:${VERSION}.${MODEL} --build-arg model=${MODEL} --build-arg version=${VERSION} .
```

Images are on [DockerHub](https://hub.docker.com/r/yosuketanigawa/whisper-cpp)
