#define base image
FROM alphine

#specify download and install dependencies
RUN apk add --update redis

#run command once container starts update
CMD ["redis-server"]

