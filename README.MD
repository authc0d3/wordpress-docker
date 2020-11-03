# WordPress + Docker

Create a docker container with a WordPress development environment.

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