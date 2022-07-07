# 3-Tier-React-Express-Mongo-Docker

## Description

Application having a three tier architecture. Frontend is in React. Backend is in Node (express). 
Database is in mongo.

## Important Note
At both backend and frontend there is .env file --> change localhost to your vm's ip_address

## Steps to follow

1) Install docker 
```
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh
```
2) Install docker-compose
```
sudo apt install docker-compose
```
2) Install git (if not installed)
```
sudo apt install git
```
3) Clone the git repo
```
git clone https://github.com/a-iftikhar/3-Tier-React-Express-Mongo-Docker.git
```
4) Execute docker-compose.yml file 
```
sudo docker-compose up
