# docker-parsecloud

A nice and easy way to run the parse cloud code client in a container. For
help on getting started with docker see the [official getting started guide][0].
You can simply take the image from the official repository with:

    docker pull izissise/parsecloud


## Running docker-parsecloud

docker run --rm -v <you app directory>:/app -it izissise/parsecloud <parsecloud parameters>

[0]: http://www.docker.io/gettingstarted/
