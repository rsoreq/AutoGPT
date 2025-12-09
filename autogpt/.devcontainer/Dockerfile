# Use an official Python base image from the Docker Hub
FROM python:3.14@sha256:6632dac1bc03ec8ea49547d866f0e5763db8fb4827bc91169ad8909248fd8190

# Install browsers
RUN apt-get update && apt-get install -y \
    chromium-driver firefox-esr \
    ca-certificates

# Install utilities
RUN apt-get install -y curl jq wget git

# Declare working directory
WORKDIR /workspace/AutoGPT
