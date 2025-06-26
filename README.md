# Basic Dockerfile for roadmap.sh

Basic Dockerfile Project for [Roadmap.sh](https://roadmap.sh/projects/basic-dockerfile)

## Prerequisites

Docker needs to be installed. If you don't have it, you can download from [here](https://www.docker.com/)

## Instructions

### 1. Clone the repository
``` 
git clone https://github.com/maggiesuero/basic-dockerfile.git
cd basic-dockerfile
```

### 2. Build the Docker Image
```
docker build -t hello-captain .
```

### 3. Run the Docker Container
```
docker run hello-captain
```

### 4. Output
`Hello, Captain!` should be printed on the terminal.