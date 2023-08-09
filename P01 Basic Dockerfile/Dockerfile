# Use an existing Docker Image as a base image
FROM alpine:3.18.3

# Dowloading and Installing Dependencies
RUN apk add --update redis

# Telling the image what-to-do when it starts as a container
CMD [ "redis-server" ]

