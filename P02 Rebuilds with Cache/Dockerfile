FROM alpine:3.18.3
RUN apk add --update redis
# Uses Cache above this point, as they are identical. If any order of the RUN is changed, it will not use cache and rebuild the process.
RUN apk add --update gcc 
CMD [ "redis-server" ]