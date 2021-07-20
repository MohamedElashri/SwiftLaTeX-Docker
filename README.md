## SwiftLaTeX-Docker



SwiftLaTeX, a WYSIWYG Browser-based LaTeX Editor


To deploy run the following command on your docker installed machine. 

``` bash
docker run -it  -p 3011:3011 melashri/latex:v1
``` 

or via `docker-compose.yml` 

``` bash
version: "3"

services:
    image: melashri/latex:v1
    #build: . # to build the image
    container_name: swiftlatex
    ports:
     - "3011:3011"
```

You can change the port from 3011 to your choice. 

Open your browser and head to http://domain.tld:3011 

My up to dated image is available on Dockerhub [SwiftLaTeX](https://hub.docker.com/r/melashri/latex)

