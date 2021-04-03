# Prototim Site
Static content for Prototim.com site

## Tools
* docker-compsoe - containerise development environment
* Hugo - for static content generation
* Toha - Theme pack for Hugo

## Use
Run test server locally with live reload

```bash
$ docker-compose up
```

Run arbitrary Hugo command (e.g. create a new site using YAML config)

```bash
$ docker-compose run --user $(id -u):$(id -g) --rm -it hugo new site ./ -f=yaml --force
```
