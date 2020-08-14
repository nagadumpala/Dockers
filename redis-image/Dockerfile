#define base image
FROM alpine

#specify download and install dependencies
RUN apk add --update redis

#run command once container starts update
CMD ["redis-server"]

