# WordPress + Docker

Create a docker container with a WordPress development environment.

## Images

The images used in the docker-compose are:
- [WordPress (latest)](https://hub.docker.com/_/wordpress)
- [MariaDB (10.5.6)](https://hub.docker.com/_/adminer) as database engine
- [Adminer (latest)](https://hub.docker.com/_/adminer) to manage the database easily

## Volumes

To persist the data and files you must create the following folder structure:

- /mysql
- /src
  - /plugins
  - /themes
  - /uploads

## Up & Running

Run this command to start the container (it will create the container if not exists):

```
> docker-compose up
```