# comments 

# Use existing docker image as base
FROM alpine

# Download and install dependencies
RUN apk add --update redis

# Tell image what to do when it starts container (startup command)
CMD ["redis-server"]