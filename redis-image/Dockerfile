# comments 

# Use existing docker image as base. Alpine is base image that contains preinstalled set of programs
FROM alpine

# Download and install dependencies
RUN apk add --update redis
RUN apk add --update gcc

# Tell image what to do when it starts container (startup command)
CMD ["redis-server"]