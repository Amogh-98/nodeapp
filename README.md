# Kubernetes Project


Prerequisites
Install minikube
Install kubectl --classic
Install docker

Deploying nodejs webapp with kubernetes and docker

Creating NodeJS App - Create a simple nodejs app
Dockerize the NodeJs App
Create a docker file with all dependencies
Build your Docker Image with dockerfile
	docker build -t <dockerhub_username>/nodeapp
Push your Image to Docker Hub
	docker push <dockerhub_username>/nodeapp
Create Kubernetes Deployment.yml
Create Kubernetes Services.yml
Deploy your application in Kubernetes
	kubectl apply -f deployment.yml 
	kubectl apply -f service.yml
