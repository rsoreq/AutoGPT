# Use an official Python base image from the Docker Hub
FROM python:3.15@sha256:20fe87d3bb1974b1c4e14d426b399b0e7209d8bbf3b6cae3ff51e09ddd490e73

# Install browsers
RUN apt-get update && apt-get install -y \
    chromium-driver firefox-esr \
    ca-certificates

# Install utilities
RUN apt-get install -y curl jq wget git

# Declare working directory
WORKDIR /workspace/AutoGPT
