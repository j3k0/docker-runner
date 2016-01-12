# docker-runner
Start a docker container, stop it on SIGTERM or SIGHUP.

## Usage

Start a container (all options are sent to docker run)

    docker-runner debian:latest sleep 3000 &

Stop the container

    kill $!

