# Use an existing docker-image as base

FROM alpine


# download and install dependency
RUN apk add --update redis
RUN apk add --update gcc

# tell thye image what to do when run
# as an container
CMD ["redis-server"]