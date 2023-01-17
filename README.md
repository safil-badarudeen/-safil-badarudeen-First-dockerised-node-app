
# First dockerised node app
 




## Used

 - [docker](https://www.docker.com/) to make images
 - [node](https://nodejs.org/en/) for app
 - [npm](https://www.npmjs.com/) for packages
 

## Knowledge and exprience

To make  this app run on localhost 3000 , I dont needed to install npm modules
i was able to make this server up without installing npm packages , quite amazed by it , Now i need to learn more about this container system


## Run Locally

Clone the project

```bash
https://github.com/safil-badarudeen/First-dockerised-node-app.git
```

Go to the project directory

```bash
  cd First-dockerised-node-app
```

#### make sure you have installed docker and started in your system

To create a image for container to be lauch

```bash
  docker build .
```

run a container
```bash
  docker run -p 3000:3000 <image id>
```



#### at this point the terminal will get stuck
#### it means server is up even without npm packages.. hoooray

#### you can click + button above terminal and open new terminal

To know which containers are  running
```bash
  docker ps
```

#### select and copy container name

To stop container
```bash
  docker stop <container name>
```
