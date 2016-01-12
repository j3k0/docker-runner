# docker-runner
Start a docker container, stop it on SIGTERM or SIGHUP, kill it on SIGKILL.

## Usage

Start a container (all options are sent to docker run)

    docker-runner ubuntu:14.04 sleep 3000 &

Stop the container

    kill $!

Or force-kill the container

    kill -9 $!

