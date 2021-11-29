# Next.js with system environment

## Description

This is a way to replace build environments with custom dynamic environment variables.

## How to test

Build a Docker image
```
docker build -t next-with-system-env .
```

Run the Docker image
```
docker run --env-file .env next-with-system-env
```

Go to http://localhost:3000

The console should display values from `.env`
