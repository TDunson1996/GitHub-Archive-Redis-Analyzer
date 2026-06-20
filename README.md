# GitHub-Archive-Redis-Analyzer
A Python application that imports GitHub Archive data into Redis and allows users to perform CRUD operations while analyzing repository activity, programming languages, and commit information.

# GitHub Archive Redis Analyzer

## Description

This project demonstrates integration between Python and Redis using GitHub Archive data.

The application imports GitHub repository information into Redis and allows users to perform CRUD operations on stored records.

## Features

### CRUD Operations

- Create records
- Read records
- Update records
- Delete records

### Analytics

1. Top programming languages
2. Top contributors
3. Repository commit visualization

## Technologies

- Python 3.12+
- Redis
- Pandas
- Matplotlib

## Dependencies

pip install -r requirements.txt

## Running

Start Redis:

redis-server

Run application:

python app.py
