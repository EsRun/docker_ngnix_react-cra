# Getting Started with Nginx and React with Docker

## Descript

This repository provides basic installation files to install ngnix and react using docker.

## Step 1

docker build -f Dockerfile-pord -t docker-nginx-react

## Step 2

docker run -it -p 80:80 docker-nginx-react
