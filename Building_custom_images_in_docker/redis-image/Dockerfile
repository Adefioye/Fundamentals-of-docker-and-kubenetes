# Use an existing docker image as a base
FROM alpine 

# Download and Install dependencies
RUN apk add --update redis 
RUN apk add --update gcc

# Tell image what to do when it starts as a container 
CMD ["redis-server"]