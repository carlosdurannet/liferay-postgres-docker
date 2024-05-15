# Liferay + PostgreSQL Docker File

## Requirements
This project requires a Docker engine installed in the system

## Use
Execute following command:
`docker compose up -d`

## Folders
* **deploy**: Copy modules jar files and themes war files to deply to the Liferay installation
* **files**: Files and folders located in this directory are copied the `/opt/liferay` container folder keeping structure. If file exists in the container, it will be replaced
* **scripts**: If you need execute a script before Liferay starts, place the file in this folder

## Documentation
* [Liferay Docker Hub](https://hub.docker.com/r/liferay/portal)
* [PostgreSQL Docker Hub](https://hub.docker.com/_/postgres)

