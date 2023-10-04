# self-driving-car
The Udacity self-driving car engineer nanodegree projects

<br>

## Setting in Local
### Download zip file
1. Follow [the link](https://github.com/udacity/nd013-c1-vision-starter)
2. Download and unzip nd013-c1-vision-starter.zip

<br>

### Build the docker image
1. Run Window powershell as Admistrator
2. Move the directory of 'build'
3. Download 'cuda:11.2.2-base' version and change '{cuda_version}.1' to '{cuda_version}.2' in Dockerfile

<br>

### Create a container
Run the below command in Window Powershell
```
docker run --gpus all -v <PATH TO LOCAL PROJECT FOLDER>:/app/project/ --network=host -ti project-dev bash
```

<br>

### Attach to the running container in VSCode
1. Install the remote development
2. Click the connect button at Dev Conainter

<br>

### Install dependencies
```
pip install -r requirements.txt
```
