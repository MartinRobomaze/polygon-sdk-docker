# polygon-sdk-docker
Dockerfiles for creating containers with Polygon SDK. It uses [golang](https://github.com/docker-library/golang) image.

# Usage
Clone the repository.  
`git clone git@github.com:MartinRobomaze/polygon-sdk-docker.git`  
### polygon-sdk
`docker build polygon-sdk -t <IMAGE_NAME>`  
This will install golang and clone polygon-sdk into the image.
### ibft-validator
`docker build ibft-validator -t <IMAGE_NAME>`  
This will install golang, clone polygon-sdk and init IBFT in the image.

# Warning
This is an unofficial Dockerfile - it is not supported by Polygon. 
