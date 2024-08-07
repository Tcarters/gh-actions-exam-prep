# Use the official Debian image as a parent image
FROM debian:stretch-slim

# Copy the entrypoint script into the Docker image
COPY entrypoint.sh /entrypoint.sh

# Make the entrypoint script executable
RUN chmod +x /entrypoint.sh

# Define the command to run when the container starts
ENTRYPOINT ["/entrypoint.sh"]
