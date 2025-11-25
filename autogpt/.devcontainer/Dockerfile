# Use an official Python base image from the Docker Hub
FROM python:3.14@sha256:edf6433343f65f94707985869aeaafe8beadaeaee11c4bc02068fca52dce28dd

# Install browsers
RUN apt-get update && apt-get install -y \
    chromium-driver firefox-esr \
    ca-certificates

# Install utilities
RUN apt-get install -y curl jq wget git

# Declare working directory
WORKDIR /workspace/AutoGPT
