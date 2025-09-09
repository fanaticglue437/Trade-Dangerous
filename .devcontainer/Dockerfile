FROM mcr.microsoft.com/devcontainers/python:1-3.12-bullseye

# Update apt and install packages

RUN apt-get update -y

RUN apt-get install dnsutils -y

RUN apt-get install cloc -y

# Upgrade pip

RUN pip install --upgrade pip setuptools

# Install uv

RUN pip install uv
