FROM mcr.microsoft.com/devcontainers/python:3.10
RUN apt-get update && apt-get install -y --no-install-recommends git screen psmisc && rm -rf /var/lib/apt/lists/*
RUN pip3 install --no-cache-dir dronekit dronekit-sitl pymavlink
