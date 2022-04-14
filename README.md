# vet-service
Python Django REST API service to ADD,UPDATE,VIEW,DELETE Vet details for pet-clinic app

# Pre-requisites
- Git 
- Docker

# Run the service

Checkout locally the code from repo
`git clone https://github.com/paulcleetus/petclinic.git`

Build the Docker Image
`docker build -t vet-service .`

Run the Docker Image, expose the containers 8030 port to the local machines 8030 port
`docker run -it -p 8030:8030 vet-service`

API uri
http://localhost:8030

Import vet-service.postman_collection.json into postman to run the APIs
