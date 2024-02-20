# COMANDS

## Build the image
``` bash 
 docker build -t docker-react .
```

## Run the container with port mapping
``` bash 
docker run -t -p 5173:5173 docker-react
```
###NB: the command above runs our container on port 5173


## Run the container with port mapping and adding docker volumes using the -v flag
```bash 
docker run -t -p 5173:5173 -v "$(pwd):/app docker-react"
```
### the command above creates a local storage 

