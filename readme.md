# How to build Laravel Docker Image

## 1. Using Dockerfile 

Example [Dockerfile link](laravel_dockerfile/Dockerfile)

## 2. Run Dockerfile with Docker Build using STDIN
~~~bash
$ docker build < Dockerfile
~~~

OR build from current folder where  Dockerfile is located
~~~bash
$ docker build .
~~~

## 
## Push the image to Dockerhub
~~~bash
$ docker push <docker hub profile>:<tag>
~~~



