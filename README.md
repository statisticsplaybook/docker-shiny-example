# docker-shiny-example

## Image build

```
docker build -t my-shinyapp-image .
```

## Run docker container

```
docker run -d --rm -p 3838:3838 my-shinyapp-image
```