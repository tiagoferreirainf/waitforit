# WaitForIt

### Description


wait-for-it.sh is a pure bash script that will wait on the availability of a host and TCP port. It is useful for synchronizing the spin-up of interdependent services, such as linked docker containers. Since it is a pure bash script, it does not have any external dependencies.

The original source code and documentation can be found on https://github.com/vishnubob/wait-for-it (commit id: 81b1373) with all useage instructions and procedures.

This repo is a simple maven project with docker containerization from the wait-for-it script on an alpine:3.14.0 using maven plugin https://github.com/spotify/dockerfile-maven.

