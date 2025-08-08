# Use an official Python base image from the Docker Hub
FROM python:3.13@sha256:68d0775234842868248bfe185eece56e725d3cb195f511a21233d0f564dee501

# Install browsers
RUN apt-get update && apt-get install -y \
    chromium-driver firefox-esr \
    ca-certificates

# Install utilities
RUN apt-get install -y curl jq wget git

# Declare working directory
WORKDIR /workspace/AutoGPT
