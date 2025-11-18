# Use an official Python base image from the Docker Hub
FROM python:3.14@sha256:5b95b240f2db781f34a5da81e6e2301378495b3ab78d689df325c937be267e1c

# Install browsers
RUN apt-get update && apt-get install -y \
    chromium-driver firefox-esr \
    ca-certificates

# Install utilities
RUN apt-get install -y curl jq wget git

# Declare working directory
WORKDIR /workspace/AutoGPT
