# docker-mockmock
Files to create a Docker image for the cross-platform SMTP server [MockMock](https://github.com/tweakers-dev/MockMock).

# Docker images
The images for this repo can be found at [Dockerhub](https://hub.docker.com/r/robinong79/mockmock/)

## Options

| ENV Variable | Default | Purpose |
| ----- | ----- | ----- |
| MOCKMOCK_SMPT_PORT | 25 | The mail port number to use|
| MOCKMOCK_HTTP_PORT | 8282 | The http port number to use|
| MOCKMOCK_MAX_QUEUE_SIZE | 1000 | The maximum size of the mail qeueue|