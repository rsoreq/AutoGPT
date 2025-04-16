# Use an official Python base image from the Docker Hub
FROM python:3.13@sha256:1f7ef1e8f35bc8629b05f4df943175f2851ba05f4a509f72304ebffde78178ee

# Install browsers
RUN apt-get update && apt-get install -y \
    chromium-driver firefox-esr \
    ca-certificates

# Install utilities
RUN apt-get install -y curl jq wget git

# Declare working directory
WORKDIR /workspace/AutoGPT
