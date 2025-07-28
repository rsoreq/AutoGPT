# Use an official Python base image from the Docker Hub
FROM python:3.13@sha256:3480fd92acd9bb3d9db0d9c62a62350891434c282d2379f84597c3c3dd4beb2e

# Install browsers
RUN apt-get update && apt-get install -y \
    chromium-driver firefox-esr \
    ca-certificates

# Install utilities
RUN apt-get install -y curl jq wget git

# Declare working directory
WORKDIR /workspace/AutoGPT
