# Use a more recent Alpine version
FROM alpine:3.18

# Install socat and clean up
RUN apk update && apk add --no-cache socat

# Set the default command to execute
ENTRYPOINT ["socat"]

# Optionally, you can set a default command to socat, for example:
# CMD ["-h"]

