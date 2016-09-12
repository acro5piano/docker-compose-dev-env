# docker-compose-dev-env

Development environment built with docker-compose

## setup

### Clone this repository

```
git clone https://github.com/acro5piano/docker-compose-dev-env.git
cd docker-compose-dev-env
docker-compose up
```

### It's done!

Go to http://localhost:3000/ and you can see PHP works.

### Useful commands

- `docker-compose ps` shows the status of containers
- `docker exec -it [web|db|elasticsearch|memcached] bash` enter the shell of a container
- `mysql -u root -p root -D app -h 127.0.0.1` enter the MySQL console
- `alias dc='docker-compose'` is useful
