# Voteapp Worker

This Dotnet Core app pulls data from Redis and writes the data to Postgres.  This app is meant to be run on a Windows VM.  This version of the app can replace the dockerized Work app that is part of the Voteapp.

> Note: This application is for demonstration purposes only

## Configure the app to talk to redis and Posgres
The `appsettings.json` file contains  two keys (RedisConnectionConfig and DatabaseConnectionConfig).  The values for each of those keys will need to be updated for the app work properly.

## Run locally
Exuectue the app locally via `dotnet run` from the project folder:

```
docker-compose up
```
