**Run your application using Docker On VSCode**

### Build the docker image 
` docker build --rm -f Dockerfile -t docker-setup:latest .`

### Run the docker container
`docker run — rm -d -p 3000:3000 docker-setup:latest`

* Open http://localhost:3000/

