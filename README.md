# riak-docker-fmke
This is a riak docker image for building the latest version of Riak (2.2.3). Based on Docker's documentation [page][1]

## What it adds
Before starting the container, this image makes sure that the "maps" bucket type is available.

## What it does
Each individual image of this spins a single Riak node. This will at least be useful in Travis-CI builds.

[1]: https://docs.docker.com/engine/examples/running_riak_service/#creating-a-dockerfile
