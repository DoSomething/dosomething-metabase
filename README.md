# DoSomething-Metabase

Basic config for self-hosted metabase with docker / docker compose. Added support for DuckDB.

# Usage

## Build the custom metabase docker image

`docker build metaduck/ --tag metaduck:latest`

## Set environment variables
Create `.env` using `.env.example`

## Run Docker Compose
`docker compose up`