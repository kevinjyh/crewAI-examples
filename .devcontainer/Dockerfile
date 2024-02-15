FROM python:3.11-slim

WORKDIR /code

# Update apt repository and install dependencies for chromedriver
RUN apt-get update && \
    apt-get install -y \
    wget \
    curl \
    unzip \
    git 

# Install crewai and python-dotenv
RUN pip install poetry

COPY . /code/
