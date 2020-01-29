# Use an existing docker image as base
FROM alpine

#Download and install all dependencies
RUN apk add --update redis
RUN apk add --update gcc


#startup command
CMD ["redis-server"]
