# DockerEnvironments
A collection of barebones docker environments. 


### Pre-requisites: 
 - Docker - https://docs.docker.com/get-docker/

## How to use this repo:
Each folder is a complete environment. It is best to navigate to a root-level folder (`PythonTensorflow`) from the command prompt to execute any of the commands. 

### Running an enviornment
Once docker is installed and running from a root-level folder:
`docker-compose up --build`

If you want a file to be available inside the environment then it needs to be in `notebook-storage`. That will map to `notebooks` inside the environment. Anything saved outside `notebooks` will not be preserved after stopping the environment. 
