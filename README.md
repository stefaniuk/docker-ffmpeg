[![Circle CI](https://circleci.com/gh/codeworksio/docker-ffmpeg.svg?style=shield "CircleCI")](https://circleci.com/gh/codeworksio/docker-ffmpeg)&nbsp;[![Size](https://images.microbadger.com/badges/image/codeworksio/ffmpeg.svg)](http://microbadger.com/images/codeworksio/ffmpeg)&nbsp;[![Version](https://images.microbadger.com/badges/version/codeworksio/ffmpeg.svg)](http://microbadger.com/images/codeworksio/ffmpeg)&nbsp;[![Commit](https://images.microbadger.com/badges/commit/codeworksio/ffmpeg.svg)](http://microbadger.com/images/codeworksio/ffmpeg)&nbsp;[![Docker Hub](https://img.shields.io/docker/pulls/codeworksio/ffmpeg.svg)](https://hub.docker.com/r/codeworksio/ffmpeg/)

Docker FFmpeg
=============

Docker wrapper around FFmpeg.

Installation
------------

Builds of the image are available on [Docker Hub](https://hub.docker.com/r/codeworksio/ffmpeg/).

    docker pull codeworksio/ffmpeg

Alternatively you can build the image yourself.

    docker build --tag codeworksio/ffmpeg \
        github.com/codeworksio/docker-ffmpeg

Testing
-------

    make build test
