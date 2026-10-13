# Use an official Python base image from the Docker Hub
FROM python:3.15@sha256:3c24e0b3ef4c5e2409f918894ccd5e05756eea2015ae6ddd289179b20a049f9b

# Install browsers
RUN apt-get update && apt-get install -y \
    chromium-driver firefox-esr \
    ca-certificates

# Install utilities
RUN apt-get install -y curl jq wget git

# Declare working directory
WORKDIR /workspace/AutoGPT
