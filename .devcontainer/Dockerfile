FROM python:3.11-slim

WORKDIR /code

RUN apt-get update && \
    apt-get install -y \
    curl \
    git

# Install crewai and python-dotenv
RUN pip install crewai python-dotenv poetry platformdirs --no-cache-dir

COPY ../ /code/
