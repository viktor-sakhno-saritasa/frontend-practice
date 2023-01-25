# [Exercise 1] Simple backend into Docker

## Prerequisite
- To run this app on your local computer, it is required to install Docker and Docker compose.
- Run commands from the root of the project folder

## How to run
### Option 1: Using Docker compose.
- `docker compose up -d`.

### Option 2: Using Docker run.
- `docker build -t ex1 .`
- `docker run -dp 8000:8000 ex1`

## Usage
Application will run on `localhost:8000`.
