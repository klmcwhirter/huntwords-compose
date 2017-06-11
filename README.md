# huntwords-compose
Docker compose project that starts up klmcwhirter/huntwords and klmcwhirter/puzzle-service

## Supported Architectures
* arm32v7 - e.g., Raspberry Pi 3
* x86_64 - e.g., macOS

The compose script detects the local architecture using the ```uname -m``` command.

## Bring it up
Issue the following command to pull down the images and start the application.

```bash
./compose up
```

## Bring it down
Issue the following command to stop the application.

```bash
./compose down
```

## Prerequisites
This project relies on docker-compose version 1.8+. It uses a version 2 docker-compose.yml file.

## External Dependencies
This project relies on the following container images hosted in Docker Hub.
* [klmcwhirter/puzzle-service](https://hub.docker.com/r/klmcwhirter/puzzle-service/):arm32v7
* [klmcwhirter/puzzle-service](https://hub.docker.com/r/klmcwhirter/puzzle-service/):x86_64

* [klmcwhirter/huntwords](https://hub.docker.com/r/klmcwhirter/huntwords/):arm32v7
* [klmcwhirter/huntwords](https://hub.docker.com/r/klmcwhirter/huntwords/):x86_64

# License
I have added an MIT license just so that it is clear that you can do whatever you like with this, but I provide
no warranty.
